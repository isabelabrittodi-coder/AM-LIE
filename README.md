# Amélie

Amélie é uma secretária pessoal de IA: parisiense, calma, culta, discreta. Ela conhece a sua vida — agenda, tarefas, Roda da Vida — e cuida dos detalhes sem precisar que você peça. Este repositório tem a personalidade dela e o painel visual onde ela vive, prontos para qualquer pessoa usar com os próprios dados.

## O que tem aqui

- **`AMELIE_PERSONA.md`** — quem a Amélie é: origem, voz, regras de comportamento, como ela trata agenda, Roda da Vida, ciclo menstrual, idioma e as ferramentas que ela sabe usar (Notion, Google Agenda, WhatsApp, Gmail, Drive). É a fonte de verdade da personalidade — tudo nela funciona para qualquer pessoa, nunca cita um dado específico de ninguém.
- **`mesa-da-amelie.html`** — o painel visual ("Mesa da Amélie"): agenda do dia, prazos, mapa do mês, Roda da Vida, e o Menu da Amélie (personalização, histórico por ano, resumo de cada mês). Bilíngue (português/inglês, detecta sozinho). Nenhum dado pessoal fica escrito neste arquivo — cada pessoa configura o próprio, uma vez, direto no navegador.
- **`img/`** — as ilustrações da identidade visual (ramo, azulejos, estrelas, selos, flores, e por aí vai). O painel depende delas para ficar com a cara da Amélie.
- **`CONECTAR_WHATSAPP.md`** — o caminho manual para a Amélie conversar pelo WhatsApp (bridge local + vigia + transcrição de áudio). Não é automático; é o mesmo caminho que qualquer pessoa usando esta base precisa seguir uma vez.

## Como começar

1. **Publique `mesa-da-amelie.html` como um Artifact no [claude.ai](https://claude.ai).** Ele não funciona só abrindo o arquivo num navegador comum — precisa ser publicado como Artifact pra ter acesso aos conectores (Notion, Google Agenda) e ao recurso de IA que gera os resumos mensais.
2. **Conecte Notion e Google Agenda** na sua própria conta, se ainda não tiver feito (Configurações › Conectores no claude.ai).
3. **Abra o painel publicado.** Na primeira vez, ele mostra uma tela de configuração pedindo os IDs das suas próprias bases do Notion (o ID está na URL de cada base, depois do nome do workspace) e da sua agenda. Preencha e clique em "Salvar e começar" — isso fica guardado só no seu navegador, nunca é enviado a lugar nenhum.
4. **Monte as bases no Notion**, se ainda não existirem: uma base de tarefas com o campo "Roda da Vida" (as 12 áreas, em 4 cores por quadrante — ver `AMELIE_PERSONA.md`), e uma base "Roda da Vida — Mensal" pras notas de cada mês. As demais (Ciclo, Perfil) são opcionais.
5. **Se quiser WhatsApp**, siga o `CONECTAR_WHATSAPP.md`.

## Por que nenhum dado pessoal está aqui

Este repositório foi pensado desde o início pra separar duas coisas: o que é a Amélie (personalidade, código, design — igual para qualquer pessoa) do que é informação de quem usa (nomes, e-mails, IDs de bases, rotina, projetos). A primeira fica neste repositório; a segunda nunca é escrita em código — fica no Notion/Agenda de cada pessoa, ou guardada localmente no navegador. Isso é o que torna esta base segura para ser pública e usada por qualquer pessoa, sem levar nenhum dado de quem a construiu primeiro.
