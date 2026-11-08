# Conectar a Amélie ao WhatsApp

A Amélie não manda mensagem de dentro do navegador — ela precisa de um pequeno programa rodando no seu computador que fica ligado ao seu WhatsApp como um "dispositivo conectado" (igual o WhatsApp Web). Esse guia é o caminho manual que qualquer pessoa usando esta base precisa seguir uma vez, no próprio computador dela.

Nada aqui é automático e nada aqui exige dado de ninguém além de quem está configurando — é só infraestrutura.

## O que você vai montar

1. Uma **ponte** (bridge) que conecta ao WhatsApp como um dispositivo vinculado.
2. Um **vigia**: um script que fica de olho no grupo da Amélie e aciona a Amélie quando chega mensagem nova.
3. **Início automático**: pra tudo isso ligar sozinho quando o computador liga, com recuperação automática se algum dos dois cair.

## Pré-requisitos

- Python 3.12 e [uv](https://docs.astral.sh/uv/) instalados.
- Uma conta de WhatsApp (pode ser a sua própria) disponível pra ficar vinculada como dispositivo.
- O [whatsapp-mcp](https://github.com/lharries/whatsapp-mcp) (projeto de terceiros, não faz parte deste repositório) — é ele que faz a ponte Go + o servidor MCP em Python falarem com o WhatsApp.

## Passo a passo

1. **Baixe o whatsapp-mcp** numa pasta do seu computador (ex.: `~/amelie-whatsapp/whatsapp-mcp`), seguindo as instruções do próprio projeto para compilar a bridge (Go) e preparar o servidor MCP (Python).

2. **Crie um grupo de WhatsApp** só pra Amélie (pode se chamar "Amélie", com só você nele, ou com outras pessoas se quiser que ela leia o grupo de todo mundo). Anote o JID desse grupo — ele aparece nos logs da bridge na primeira vez que ela sincroniza as conversas.

3. **Rode a bridge e escaneie o QR code**: ao iniciar `whatsapp-bridge.exe` (ou o binário equivalente no seu sistema), ela mostra um QR code no terminal. Abra WhatsApp no celular → Configurações → Dispositivos conectados → Conectar um dispositivo → aponte a câmera. A sessão fica salva localmente; só precisa escanear de novo se o dispositivo for deslogado (acontece raramente, geralmente por inatividade longa ou logout manual).

4. **Aponte o servidor MCP pro JID do seu grupo** — o servidor precisa saber qual grupo é "o grupo da Amélie". Ajuste essa referência na configuração do servidor MCP conforme a documentação do whatsapp-mcp.

5. **Adicione o servidor MCP na sua configuração do Claude** (arquivo de conectores do Claude Code/Claude Desktop), apontando pro `main.py` do whatsapp-mcp-server, do jeito que qualquer servidor MCP local é adicionado.

6. **Monte o vigia**: um script que, a cada ~30 segundos, olha se chegou mensagem nova no grupo (lendo o banco local da bridge, sem gastar nada enquanto não há mensagem) e, quando chega, chama o Claude com as instruções da Amélie (`AMELIE_PERSONA.md` deste repositório) pra decidir e responder. Áudios podem ser transcritos localmente com [faster-whisper](https://github.com/SYSTRAN/faster-whisper), sem mandar nada pra nuvem.

7. **Deixe tudo ligando sozinho**: crie um atalho na pasta de Inicialização do seu sistema (no Windows: `shell:startup`) que abra a bridge e o vigia minimizados, cada um dentro de um laço que reinicia automaticamente se cair. Isso evita o problema mais comum: o processo parar silenciosamente e as rotinas diárias não saírem.

## Perguntas que a Amélie já sabe responder

Se você perguntar à Amélie "como conecto você ao WhatsApp?", ela deve te apontar pra este arquivo e resumir os 3 blocos (bridge, vigia, início automático) — não implementar nada por conta própria, porque isso depende do seu computador, do seu WhatsApp e das suas escolhas de onde instalar cada coisa.
