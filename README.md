# Amélie

![Mesa da Amélie — exemplo com dados fictícios](img/readme-banner.jpg)

**Uma secretária pessoal de IA, pronta pra usar — não um projeto pra começar do zero.**

Se você já usa Claude e pensou em montar um agente que organiza sua vida pelo WhatsApp, Notion e Google Agenda, a parte difícil já está feita aqui: a personalidade, o design, a lógica de decisão. Baixe, conecte nas suas próprias contas, e Amélie já sabe quem ela é.

Amélie é parisiense, calma, culta, discreta. Ela conhece sua rotina — agenda, tarefas, a Roda da Vida (as 12 áreas da sua vida) — e cuida dos detalhes sem que você precise pedir. Nunca pergunta "o que você quer que eu faça" pra tudo; entende, decide dentro do que já foi pedido, e avisa o que fez.

**O que ela faz:**
- Organiza agenda e tarefas entre Google Agenda e Notion, sincronizados sempre juntos.
- Resolve sozinha conflitos de horário no mesmo dia — nunca pede permissão pra isso.
- Conversa pelo WhatsApp: briefings diários, semanais, mensais e anuais.
- Conduz o fechamento mensal da Roda da Vida, com nota e justificativa por área, e gera um resumo do mês com IA.
- Identifica o idioma de quem escreve (português ou inglês) e responde nele, sem perguntar.
- Sabe usar Gmail, Google Drive e um eventual agente financeiro, sempre com as mesmas regras de nunca agir sem autorização quando o assunto é sensível.

Gratuita, sob licença MIT (ver [`LICENSE`](LICENSE)) — use, copie, modifique.

## A Roda da Vida

O coração da Amélie é um jeito de olhar pra vida inteira em vez de só pra lista de tarefas: a **Roda da Vida**, 12 áreas agrupadas em 4 grandes eixos.

| Eixo | Áreas |
|---|---|
| 🔵 **Profissional** | Contribuição social · Finanças e bens · Realização e propósito |
| 🟢 **Pessoal** | Saúde e disposição · Desenvolvimento do intelecto · Equilíbrio emocional |
| 🩷 **Relacionamentos** | Família · Relacionamentos amorosos · Vida social |
| 🟡 **Qualidade de vida** | Espiritualidade · Plenitude e felicidade · Lazer e diversão |

Cada eixo tem sua própria cor, e cada área sua própria sombra dessa cor — é assim que o mapa do mês e os eventos do Google Agenda ficam coloridos no painel: de relance, dá pra ver em qual eixo da vida cada compromisso cai.

**Como isso integra com o resto:** essas 12 áreas não são um questionário solto — são a mesma classificação usada em *cada* tarefa e compromisso que a Amélie organiza no Notion e no Google Agenda. A Roda da Vida visual é só o resumo de tudo isso: cada fatia cresce ou encolhe de acordo com o que está acontecendo de fato na sua rotina.

**O ritual mensal:** no último domingo do mês, Amélie conduz o fechamento — cada uma das 12 áreas recebe uma nota de 1 a 10, e **a nota sempre vem com a justificativa de por que ela é essa e não outra** (nunca só o número). A partir daí, pra qualquer área que você sinta que merece subir, você propõe o que quer mudar — e essa proposta vira a prioridade do **mês seguinte**, não do mês que terminou. É o ciclo: olhar pra trás com honestidade, decidir um plano pontual pra frente, e deixar a Amélie lembrar disso ao longo do mês que começa.

## O que tem aqui

- **`AMELIE_PERSONA.md`** — quem a Amélie é: origem, voz, regras de comportamento, como ela trata agenda, Roda da Vida, ciclo menstrual, idioma e as ferramentas que ela sabe usar (Notion, Google Agenda, WhatsApp, Gmail, Drive). É a fonte de verdade da personalidade — tudo nela funciona para qualquer pessoa, nunca cita um dado específico de ninguém.
- **`mesa-da-amelie.html`** — o painel visual ("Mesa da Amélie"): agenda do dia, prazos, mapa do mês, Roda da Vida, e o Menu da Amélie (personalização, histórico por ano, resumo de cada mês). Bilíngue (português/inglês, detecta sozinho). Nenhum dado pessoal fica escrito neste arquivo — cada pessoa configura o próprio, uma vez, direto no navegador.
- **`img/`** — as ilustrações da identidade visual (ramo, azulejos, estrelas, selos, flores, e por aí vai). O painel depende delas para ficar com a cara da Amélie.
- **`CONECTAR_WHATSAPP.md`** — o caminho manual para a Amélie conversar pelo WhatsApp (bridge local + vigia + transcrição de áudio). Não é automático; é o mesmo caminho que qualquer pessoa usando esta base precisa seguir uma vez.

## Como começar

1. **Publique `mesa-da-amelie.html` como o seu próprio Artifact no [claude.ai](https://claude.ai).** Ele não funciona só abrindo o arquivo num navegador comum — precisa ser publicado como Artifact pra ter acesso aos conectores (Notion, Google Agenda) e ao recurso de IA que gera os resumos mensais. **Importante: publique sua própria cópia, nunca abra o link do Artifact de outra pessoa pra configurar o seu** — cada instalação precisa ficar independente das outras.
2. **Conecte Notion e Google Agenda** na sua própria conta, se ainda não tiver feito (Configurações › Conectores no claude.ai).
3. **Abra o painel publicado.** Na primeira vez, ele mostra uma tela de configuração pedindo os IDs das suas próprias bases do Notion (o ID está na URL de cada base, depois do nome do workspace) e da sua agenda. Preencha e clique em "Salvar e começar" — isso fica guardado só no seu navegador, nunca é enviado a lugar nenhum.
4. **Monte as bases no Notion**, se ainda não existirem: uma base de tarefas com o campo "Roda da Vida" (as 12 áreas, em 4 cores por quadrante — ver `AMELIE_PERSONA.md`), e uma base "Roda da Vida — Mensal" pras notas de cada mês. As demais (Ciclo, Perfil) são opcionais.
5. **Se quiser WhatsApp**, siga o `CONECTAR_WHATSAPP.md`.

## Por que nenhum dado pessoal está aqui

Este repositório foi pensado desde o início pra separar duas coisas: o que é a Amélie (personalidade, código, design — igual para qualquer pessoa) do que é informação de quem usa (nomes, e-mails, IDs de bases, rotina, projetos). A primeira fica neste repositório; a segunda nunca é escrita em código — fica no Notion/Agenda de cada pessoa, ou guardada localmente no navegador. Isso é o que torna esta base segura para ser pública e usada por qualquer pessoa, sem levar nenhum dado de quem a construiu primeiro.

## Aviso

Este software é distribuído "como está", sem garantias — ver [`LICENSE`](LICENSE). Cada pessoa é responsável pela própria instalação, pelas próprias conexões (Notion, Google, WhatsApp) e pelos próprios dados. Publique sempre a sua própria cópia do Artifact; nunca compartilhe ou reutilize o link de outra pessoa.
