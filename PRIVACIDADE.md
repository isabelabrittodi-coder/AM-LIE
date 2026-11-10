# POLÍTICA DE PRIVACIDADE — AMÉLIE

**Última atualização: 10 de novembro de 2026**

## 1. APRESENTAÇÃO E OBJETO

A Amélie é um projeto de software destinado à organização pessoal, ao gerenciamento de tarefas, ao acompanhamento de objetivos e à integração de ferramentas digitais, disponibilizado por meio de código-fonte e executado individualmente por cada usuário.

O projeto utiliza serviços e plataformas de terceiros para viabilizar determinadas funcionalidades, permitindo que cada usuário conecte suas próprias contas e configure o ambiente de utilização conforme suas necessidades.

A Amélie não opera uma infraestrutura centralizada destinada ao armazenamento das informações pessoais dos usuários, nem mantém banco de dados próprio para concentrar os conteúdos inseridos nas instalações individuais da aplicação.

Esta Política de Privacidade tem por finalidade informar quais informações podem ser utilizadas durante o funcionamento da Amélie, como ocorrem os fluxos de armazenamento e transmissão, quais serviços externos participam dessas operações e quais são os limites de atuação da pessoa responsável pela disponibilização do projeto.

A presente Política deve ser interpretada em conjunto com os termos de utilização e as políticas de privacidade dos serviços de terceiros integrados à aplicação.

## 2. NATUREZA DO PROJETO E ATUAÇÃO DA DESENVOLVEDORA

A Amélie é disponibilizada como projeto de software, cuja instalação, configuração e utilização são realizadas individualmente pelo usuário.

A pessoa responsável pela disponibilização do código-fonte não administra as contas particulares dos usuários nas plataformas integradas, não possui acesso ordinário aos respectivos ambientes privados e não mantém infraestrutura própria destinada à hospedagem, sincronização ou armazenamento centralizado dos dados inseridos na aplicação.

A configuração das integrações, a autorização de acesso às contas externas e a administração dos ambientes particulares são realizadas pelo próprio usuário, mediante os mecanismos disponibilizados pelos respectivos fornecedores.

A ausência de infraestrutura centralizada não significa, por si só, inexistência de operações de tratamento de dados pessoais. A identificação das responsabilidades de cada agente deverá considerar as atividades efetivamente desempenhadas, as decisões tomadas e as operações concretas de tratamento.

Assim, esta Política não pretende afastar responsabilidades legalmente atribuíveis à desenvolvedora, mas delimitar sua atuação em relação às operações realizadas diretamente pelo usuário e pelos fornecedores externos.

## 3. INFORMAÇÕES UTILIZADAS PELA APLICAÇÃO

O funcionamento da Amélie pode envolver o tratamento das seguintes categorias de informações, conforme as funcionalidades utilizadas:

### 3.1. Informações de configuração e preferências

A aplicação utiliza o armazenamento local do navegador para conservar determinadas configurações, incluindo:

- Identificadores de bases de dados do Notion;
- Identificador de agenda do Google Calendar;
- Listas de projetos, agentes e classificações;
- Preferência de idioma da interface.

Essas informações são utilizadas para configurar a interface e viabilizar as integrações selecionadas pelo usuário.

Os identificadores armazenados localmente podem ser utilizados na composição de solicitações encaminhadas às APIs dos respectivos serviços, quando necessários à execução das funcionalidades.

### 3.2. Informações de perfil

Quando preenchidas pelo usuário, podem ser utilizadas informações como:

- Nome;
- Apelido;
- Profissão;
- Informações pessoais que o usuário deseje fornecer para contextualizar o funcionamento da assistente.

Essas informações são encaminhadas ao Notion para armazenamento no ambiente particular do usuário e podem ser utilizadas em funcionalidades de inteligência artificial, conforme descrito nesta Política.

### 3.3. Informações relacionadas a tarefas e atividades

A utilização das funcionalidades de gerenciamento de tarefas pode envolver:

- Nome e descrição da tarefa;
- Tipo e categoria;
- Lista, classificação e projeto associado;
- Status;
- Área da Roda da Vida;
- Prioridade;
- Nível de energia;
- Observações;
- Origem;
- Datas de vencimento, planejamento ou execução;
- Informações relacionadas ao adiamento ou acompanhamento da atividade.

Essas informações são encaminhadas ao Notion para armazenamento e posterior consulta pela aplicação.

Nem todos os campos necessariamente são encaminhados a todos os serviços externos. O conteúdo transmitido depende da funcionalidade acionada, conforme descrito nas seções específicas desta Política.

### 3.4. Informações da Roda da Vida

A funcionalidade Roda da Vida permite registrar avaliações pessoais sobre diferentes áreas da vida do usuário.

O preenchimento pode envolver:

- Avaliações numéricas de doze áreas, em escala de 1 a 10;
- Justificativas associadas às avaliações;
- Identificação das principais necessidades do mês;
- Prioridades para o período seguinte;
- Alterações e objetivos propostos pelo usuário.

Essas informações são armazenadas no ambiente particular do usuário no Notion e podem ser encaminhadas à Anthropic para geração de resumos mensais, conforme a funcionalidade utilizada.

O usuário deve considerar que justificativas e avaliações pessoais podem revelar aspectos íntimos de sua vida. Recomenda-se evitar o registro de informações sensíveis ou excessivas quando não forem necessárias à finalidade pretendida.

### 3.5. Anotações locais

A aplicação disponibiliza um campo de anotações denominado "Notas", cujo conteúdo é armazenado no armazenamento local do navegador.

Conforme a estrutura técnica examinada, essas anotações não são encaminhadas ao Notion nem às funcionalidades de inteligência artificial da Amélie.

Por permanecerem no ambiente local do navegador, sua conservação depende da manutenção dos dados locais do dispositivo e do navegador utilizado. A limpeza desses dados, a troca de dispositivo ou a utilização de outro perfil de navegador poderá ocasionar sua perda.

O armazenamento local não equivale a armazenamento criptografado ou a um ambiente de segurança independente.

## 4. FINALIDADES E OPERAÇÕES DE TRATAMENTO

As informações utilizadas pela Amélie são tratadas de acordo com as funcionalidades acionadas pelo usuário, observadas as seguintes finalidades:

| Funcionalidade | Finalidade |
|---|---|
| Configuração | Personalizar a aplicação e estabelecer conexões com serviços externos |
| Gerenciamento de tarefas | Criar, consultar e atualizar registros no Notion |
| Perfil | Armazenar informações de personalização no Notion |
| Roda da Vida | Registrar avaliações e acompanhar objetivos pessoais |
| Google Calendar | Criar eventos na agenda selecionada pelo usuário |
| Inteligência artificial | Organizar informações, analisar tarefas e produzir resumos mensais |
| Anotações locais | Registrar informações pessoais no navegador |

A utilização de cada funcionalidade poderá envolver diferentes operações de armazenamento, consulta e transmissão, conforme descrito nas seções seguintes.

## 5. ARMAZENAMENTO E INTEGRAÇÃO COM SERVIÇOS EXTERNOS

A Amélie utiliza serviços de terceiros para armazenar e processar determinadas informações. A desenvolvedora não administra as infraestruturas desses fornecedores.

### 5.1. Notion

A integração com o Notion permite armazenar, consultar e atualizar informações relacionadas às funcionalidades da aplicação.

Conforme a funcionalidade utilizada, poderão ser encaminhados ao Notion:

- Dados de tarefas e atividades;
- Informações de perfil;
- Avaliações e justificativas da Roda da Vida;
- Registros de ciclo;
- Resumos mensais gerados pela inteligência artificial;
- Alterações realizadas pelo usuário em registros existentes.

A aplicação também realiza consultas às bases e páginas do Notion para recuperar informações necessárias à exibição e ao funcionamento da interface.

Os conteúdos persistentes são armazenados na conta particular do usuário, de acordo com a infraestrutura, as condições de utilização e as políticas de privacidade do Notion.

A desenvolvedora da Amélie não administra a conta particular do usuário nem controla as políticas internas de armazenamento, retenção e segurança da plataforma.

Política de privacidade do Notion: https://www.notion.com/privacy

### 5.2. Google Calendar

A integração com o Google Calendar permite a criação de eventos na agenda selecionada pelo usuário.

A criação de eventos poderá envolver o envio das seguintes informações:

- Título ou descrição do evento;
- Data e horário de início e término;
- Fuso horário;
- Identificação da área correspondente, utilizada para definição da cor do evento.

A descrição do evento poderá conter a indicação de que foi criado pela Amélie.

Conforme a auditoria técnica realizada, a aplicação consulta eventos existentes e permite sua visualização, mas não realiza, por meio do código examinado, alterações nos eventos previamente existentes.

Os eventos criados são armazenados na conta particular do Google vinculada pelo usuário.

A desenvolvedora não administra a agenda particular do usuário nem controla as práticas internas de tratamento de dados do Google.

Política de privacidade do Google: https://policies.google.com/privacy

### 5.3. Anthropic e Claude

Determinadas funcionalidades utilizam recursos de inteligência artificial disponibilizados pela Anthropic, por meio do Claude.

Quando o usuário aciona essas funcionalidades, informações relacionadas à solicitação são encaminhadas à infraestrutura do fornecedor para processamento e geração das respostas correspondentes.

Conforme a auditoria técnica, foram identificadas três operações principais de envio:

**a) Organização de mensagens e recados**

Podem ser encaminhados:

- Texto inserido pelo usuário, limitado a 2.000 caracteres na funcionalidade examinada;
- Nome ou apelido do usuário;
- Data atual e informações relativas aos sete dias seguintes;
- Listas de projetos e classificações utilizadas pela aplicação.

**b) Análise de tarefas**

Para a geração de comentários ou análises sobre uma tarefa, podem ser encaminhados:

- Nome e tipo da tarefa;
- Área da Roda da Vida;
- Lista e status;
- Prioridade e nível de energia;
- Datas de vencimento ou planejamento;
- Número de adiamentos;
- Observações;
- Conteúdo da página correspondente no Notion, limitado a 6.000 caracteres na funcionalidade examinada.

**c) Geração de resumo mensal**

Para a elaboração de resumos mensais, podem ser encaminhados:

- Nome do usuário;
- Mês de referência;
- Quantidade de tarefas por área da Roda da Vida;
- Quantidade de tarefas concluídas;
- Avaliações numéricas das doze áreas;
- Justificativas fornecidas pelo usuário.

O resumo produzido poderá ser posteriormente armazenado no Notion, conforme a funcionalidade implementada.

A desenvolvedora não administra os servidores da Anthropic nem determina unilateralmente suas práticas internas de processamento, armazenamento, segurança ou retenção de informações.

O tratamento realizado pelo fornecedor está sujeito às condições contratuais e à política de privacidade aplicáveis ao serviço utilizado.

Política de privacidade da Anthropic: https://www.anthropic.com/legal/privacy

Recomenda-se que o usuário evite inserir informações pessoais, confidenciais ou sensíveis que não sejam necessárias à funcionalidade acionada, especialmente informações de terceiros ou dados protegidos por sigilo profissional.

## 6. INTEGRAÇÃO OPCIONAL COM WHATSAPP

A integração com WhatsApp é opcional e depende de configuração individual pelo usuário.

Essa funcionalidade utiliza ferramenta externa denominada whatsapp-mcp, disponibilizada por terceiro e independente do código-fonte principal da Amélie.

A ferramenta externa estabelece uma conexão com a conta de WhatsApp do usuário por meio de mecanismo de dispositivo vinculado e poderá manter um banco de dados local com o histórico das conversas selecionadas para monitoramento.

Quando habilitada, a integração poderá envolver:

- Leitura de mensagens das conversas selecionadas;
- Armazenamento local do conteúdo das mensagens;
- Identificação de novas mensagens;
- Encaminhamento de mensagens textuais à infraestrutura do Claude;
- Transcrição local de mensagens de áudio, com posterior encaminhamento do conteúdo textual à infraestrutura do Claude.

Conforme a documentação técnica examinada, o arquivo de áudio é transcrito localmente e não é encaminhado diretamente à infraestrutura de inteligência artificial. Entretanto, o texto resultante da transcrição poderá ser enviado para processamento pelo Claude.

A integração pode envolver mensagens enviadas por outras pessoas, inclusive participantes de grupos. Dessa forma, o usuário deve avaliar previamente a legitimidade da coleta e do tratamento dessas informações, observar os deveres de confidencialidade aplicáveis e adotar providências adequadas de transparência perante os demais participantes.

**Tratamento de dados de terceiros nas conversas**

Quando a integração envolver mensagens de pessoas que não utilizam diretamente a Amélie, o usuário que habilitou e configurou o monitoramento deverá avaliar a legitimidade do tratamento, observar os deveres de transparência e disponibilizar aos participantes informações sobre a utilização de seus dados, inclusive quanto ao eventual encaminhamento de mensagens à infraestrutura de inteligência artificial.

O usuário responsável pela configuração da integração deverá atuar como canal inicial de comunicação para solicitações relacionadas às mensagens obtidas por meio das conversas monitoradas, adotando as providências necessárias para viabilizar o exercício dos direitos dos titulares perante os agentes responsáveis.

Essa disposição não afasta eventuais obrigações da desenvolvedora ou dos fornecedores externos, caso sejam identificados como agentes de tratamento em relação a operações específicas, nos termos da legislação aplicável.

A ferramenta whatsapp-mcp é desenvolvida e mantida por terceiro. Seu código interno, suas práticas de armazenamento, seus mecanismos de segurança e seus prazos de retenção não foram objeto de auditoria independente pela desenvolvedora da Amélie.

A desenvolvedora não administra o banco de dados local da ferramenta externa nem controla sua infraestrutura de funcionamento.

A utilização dessa integração também está sujeita às condições e limitações técnicas e contratuais do WhatsApp e da ferramenta externa. O usuário deverá verificar os riscos e as condições aplicáveis à utilização de soluções não oficiais de conexão.

## 7. COMPARTILHAMENTO E DESTINATÁRIOS DAS INFORMAÇÕES

A Amélie não possui mecanismo próprio de comercialização de dados pessoais nem prevê o compartilhamento de informações dos usuários para fins publicitários.

Entretanto, determinadas informações são encaminhadas aos fornecedores externos necessários ao funcionamento das funcionalidades selecionadas.

Os principais destinatários identificados na auditoria são:

| Fornecedor | Finalidade do acesso |
|---|---|
| Notion | Armazenamento, consulta e atualização de tarefas, perfil e registros pessoais |
| Google | Criação e consulta de eventos no Google Calendar |
| Anthropic | Processamento de informações por funcionalidades de inteligência artificial |
| Google Fonts | Disponibilização de fontes utilizadas na interface |
| whatsapp-mcp | Conexão com WhatsApp e gerenciamento local de mensagens, quando habilitado |

A utilização de fontes disponibilizadas pelo Google Fonts pode implicar o recebimento de informações técnicas, como o endereço IP do dispositivo utilizado, pelos servidores responsáveis pelo fornecimento das fontes.

Conforme a auditoria técnica, não foram identificados mecanismos próprios de publicidade, pixels de rastreamento ou ferramentas de análise comportamental implementados diretamente no código examinado.

Essa constatação se limita ao código e às funcionalidades examinadas, não abrangendo eventuais mecanismos próprios dos serviços externos utilizados.

## 8. TRANSFERÊNCIA INTERNACIONAL DE DADOS

Os serviços externos integrados à Amélie podem utilizar infraestrutura localizada fora do Brasil.

Consequentemente, determinadas operações poderão envolver o processamento ou o armazenamento internacional de dados pessoais, conforme a arquitetura, as condições contratuais e a localização da infraestrutura de cada fornecedor.

A identificação dos países de destino, dos mecanismos jurídicos aplicáveis e das garantias de proteção deverá observar as informações e os instrumentos disponibilizados por cada fornecedor.

As transferências internacionais de dados pessoais, quando caracterizadas, deverão observar os requisitos da Lei nº 13.709/2018 e da regulamentação da Autoridade Nacional de Proteção de Dados.

A desenvolvedora não define unilateralmente a localização dos servidores ou a arquitetura internacional dos serviços externos utilizados pela aplicação.

## 9. ARMAZENAMENTO, RETENÇÃO E EXCLUSÃO

As informações utilizadas pela Amélie podem permanecer armazenadas em diferentes ambientes, conforme a funcionalidade utilizada.

**a) Armazenamento local do navegador**

As configurações e anotações locais permanecem armazenadas no navegador do dispositivo utilizado, até que sejam excluídas pelo usuário, removidas por procedimentos de limpeza do navegador ou perdidas em razão de alterações no ambiente de utilização.

**b) Notion**

As tarefas, informações de perfil, registros da Roda da Vida e demais conteúdos encaminhados ao Notion permanecem armazenados na conta particular do usuário, conforme suas configurações e as políticas de retenção e exclusão da plataforma.

**c) Google Calendar**

Os eventos criados pela Amélie permanecem armazenados na agenda particular do usuário, sujeitos às configurações e políticas do Google.

**d) Anthropic**

As informações encaminhadas ao Claude ficam sujeitas às condições de processamento, retenção e exclusão estabelecidas pela Anthropic para o serviço efetivamente utilizado.

**e) WhatsApp e ferramenta externa**

Quando habilitada a integração, mensagens poderão permanecer armazenadas no banco de dados local mantido pela ferramenta whatsapp-mcp. A duração desse armazenamento depende da configuração e do funcionamento da ferramenta externa, não tendo sido identificado, na auditoria realizada, um prazo de retenção controlado pela Amélie.

A desenvolvedora não mantém mecanismo centralizado de exclusão dos registros armazenados nas contas particulares dos usuários ou nas infraestruturas de terceiros.

A exclusão de informações deverá ser realizada nos ambientes em que efetivamente estejam armazenadas, observadas as funcionalidades e os procedimentos disponibilizados pelos respectivos fornecedores.

A exclusão de um registro em determinado ambiente não implica, necessariamente, sua exclusão automática de outros serviços que tenham recebido anteriormente informações relacionadas àquele registro.

## 10. SEGURANÇA DA INFORMAÇÃO

A Amélie utiliza mecanismos de integração e armazenamento disponibilizados pelos serviços externos selecionados pelo usuário.

A segurança das informações depende, entre outros fatores, das configurações realizadas, das permissões concedidas, da proteção dos dispositivos utilizados, da segurança das contas particulares e das medidas adotadas pelos fornecedores externos.

A desenvolvedora não administra os dispositivos dos usuários, não controla suas credenciais particulares e não possui ingerência sobre todos os mecanismos de segurança empregados pelas plataformas integradas.

A utilização do armazenamento local do navegador não deve ser interpretada como garantia de criptografia, proteção contra acesso por terceiros ou segurança absoluta das informações.

Recomenda-se ao usuário:

- Utilizar dispositivos protegidos por senha ou mecanismo equivalente;
- Manter navegador e sistemas atualizados;
- Proteger as credenciais das contas conectadas;
- Conceder apenas as permissões necessárias às integrações;
- Evitar o compartilhamento de dispositivos e perfis de navegador sem proteção;
- Não inserir informações confidenciais ou sensíveis desnecessárias;
- Revisar periodicamente as autorizações concedidas aos serviços externos.

Nenhum sistema tecnológico pode assegurar proteção absoluta contra incidentes, falhas, acessos não autorizados ou vulnerabilidades.

## 11. RESPONSABILIDADES DO USUÁRIO

O usuário é responsável pelas informações que decide inserir, registrar, importar ou transmitir por meio da Amélie, devendo observar a legislação aplicável e os direitos de terceiros.

Compete ao usuário, especialmente:

- Verificar a legitimidade da utilização de dados pessoais de terceiros;
- Evitar a inserção de informações excessivas ou desnecessárias;
- Observar deveres de confidencialidade e sigilo profissional;
- Administrar as permissões concedidas às contas externas;
- Proteger suas credenciais e seus dispositivos;
- Consultar as condições de utilização dos serviços integrados;
- Avaliar a legitimidade do monitoramento de conversas e mensagens de terceiros;
- Adotar as providências de transparência e obtenção de autorização ou outra base legal adequada, quando exigidas pela legislação.

A disponibilização do código-fonte não representa autorização para a coleta, utilização ou compartilhamento indiscriminado de dados pessoais.

O usuário deve utilizar a aplicação de maneira compatível com as finalidades informadas e com as normas legais aplicáveis.

## 12. LIMITES DE ATUAÇÃO E RESPONSABILIDADE DA DESENVOLVEDORA

A Amélie é disponibilizada como projeto de software cuja execução depende da configuração individual do usuário e da integração com serviços externos.

A desenvolvedora não administra as contas particulares dos usuários, não controla a infraestrutura dos fornecedores externos e não determina unilateralmente suas políticas de armazenamento, retenção, segurança ou disponibilidade.

A desenvolvedora também não garante a disponibilidade contínua, a ausência de erros ou a compatibilidade permanente da aplicação com serviços e APIs de terceiros, que poderão sofrer alterações, interrupções ou descontinuações promovidas por seus respectivos fornecedores.

As consequências decorrentes exclusivamente de configurações particulares, permissões concedidas pelo usuário, atos de terceiros ou operações realizadas em infraestruturas que não estejam sob controle da desenvolvedora não lhe poderão ser atribuídas automaticamente.

A presente disposição não exclui nem limita responsabilidades legalmente atribuíveis à desenvolvedora por sua própria atuação, por operações de tratamento pelas quais seja responsável ou por violações de deveres legais aplicáveis.

Nenhuma disposição desta Política deve ser interpretada como renúncia aos direitos dos titulares de dados pessoais ou como exclusão de responsabilidade em hipóteses vedadas pela legislação.

## 13. DIREITOS DOS TITULARES DE DADOS PESSOAIS

Nos termos da Lei Geral de Proteção de Dados Pessoais, os titulares poderão exercer os direitos legalmente previstos perante os agentes de tratamento responsáveis pelas operações correspondentes.

Entre esses direitos, observadas as condições e os limites legais, estão:

- Confirmação da existência de tratamento;
- Acesso aos dados pessoais;
- Correção de dados incompletos, inexatos ou desatualizados;
- Anonimização, bloqueio ou eliminação de dados desnecessários, excessivos ou tratados em desconformidade com a legislação;
- Portabilidade, quando aplicável;
- Eliminação de dados tratados com consentimento, ressalvadas as hipóteses legais de conservação;
- Informação sobre entidades públicas e privadas com as quais tenha ocorrido uso compartilhado de dados;
- Informação sobre a possibilidade de não fornecer consentimento e suas consequências, quando essa for a base legal aplicável;
- Revogação do consentimento, quando aplicável.

Em relação às informações armazenadas nas contas particulares do usuário, as solicitações deverão ser direcionadas aos respectivos fornecedores, observados seus canais e procedimentos.

Em relação às informações encaminhadas à Anthropic, deverão ser consultados os mecanismos de atendimento e exercício de direitos disponibilizados pelo fornecedor.

No caso de mensagens de terceiros obtidas por meio da integração com WhatsApp, o usuário que habilitou o monitoramento deverá atuar como canal inicial para o recebimento e encaminhamento das solicitações relacionadas às conversas monitoradas, sem prejuízo das obrigações dos demais agentes eventualmente responsáveis.

A pessoa responsável pela disponibilização do código-fonte não possui acesso ordinário às contas particulares dos usuários ou aos conteúdos nelas armazenados. Caso receba solicitação relativa a operação de tratamento sob sua responsabilidade, a solicitação será examinada conforme sua efetiva participação na operação e a legislação aplicável.

A ausência de acesso técnico a determinadas informações não prejudica os direitos legalmente assegurados aos titulares perante os agentes de tratamento responsáveis.

## 14. PRIVACIDADE DE CRIANÇAS E ADOLESCENTES

A Amélie não foi desenvolvida especificamente para o público infantil.

Caso a aplicação seja utilizada por crianças ou adolescentes, o tratamento de seus dados pessoais deverá observar as disposições legais aplicáveis, especialmente o princípio do melhor interesse e as regras específicas previstas na legislação brasileira.

A utilização da aplicação não dispensa a observância das medidas de proteção exigidas para o tratamento de dados pessoais de crianças e adolescentes.

## 15. COOKIES E TECNOLOGIAS DE RASTREAMENTO

Conforme a auditoria técnica realizada no código examinado, não foram identificados mecanismos próprios de publicidade comportamental, pixels de rastreamento ou ferramentas de análise de utilização implementados diretamente pela Amélie.

A aplicação utiliza armazenamento local do navegador para conservar configurações e anotações, conforme descrito nesta Política.

Além disso, o carregamento de fontes externas pelo Google Fonts pode ocasionar o envio de informações técnicas do dispositivo aos servidores do fornecedor.

A utilização de tecnologias próprias dos serviços externos integrados permanece sujeita às respectivas políticas e configurações.

## 16. LEGISLAÇÃO APLICÁVEL E PROTEÇÃO INTERNACIONAL DE DADOS

Esta Política foi elaborada considerando, especialmente, os princípios e as disposições da Lei nº 13.709/2018 — Lei Geral de Proteção de Dados Pessoais (LGPD).

Caso outras legislações de proteção de dados sejam aplicáveis em razão da localização do usuário, da natureza da utilização da aplicação ou das atividades efetivamente realizadas, sua interpretação e aplicação deverão observar os respectivos requisitos legais.

A Amélie busca adotar práticas de transparência, segurança e respeito à privacidade compatíveis com os princípios internacionalmente reconhecidos de proteção de dados pessoais, sem que esta disposição represente declaração de submissão automática a regimes jurídicos cuja incidência dependa de requisitos específicos.

## 17. ALTERAÇÕES DESTA POLÍTICA

Esta Política poderá ser atualizada para refletir alterações no código-fonte, nas funcionalidades da Amélie, nos serviços externos utilizados ou na legislação aplicável.

A versão atualizada será disponibilizada no mesmo ambiente em que esta Política estiver publicada, acompanhada da respectiva data de revisão.

Recomenda-se que o usuário consulte periodicamente este documento para acompanhar eventuais alterações.

## 18. CONTATO

Dúvidas, solicitações ou comunicações relacionadas a esta Política poderão ser encaminhadas por meio do perfil da responsável pelo projeto na plataforma Reddit:

**Reddit: u/IsaBritto__**

As comunicações poderão ser realizadas por mensagem privada à conta indicada.

Para preservar a privacidade dos titulares, recomenda-se que não sejam encaminhados, por meio de mensagens no Reddit ou de outros canais públicos, documentos de identificação, credenciais, informações financeiras, dados pessoais sensíveis ou conteúdos confidenciais.

Quando uma solicitação exigir a apresentação de informações adicionais para verificação de identidade ou análise do pedido, a forma de encaminhamento deverá ser avaliada de maneira a preservar a segurança e a confidencialidade dos dados envolvidos.

O perfil indicado também poderá ser utilizado para dúvidas gerais, sugestões e comunicações relacionadas ao projeto.

---

Esta Política de Privacidade foi elaborada com base nas funcionalidades e nos fluxos técnicos identificados na auditoria do código-fonte da Amélie, devendo ser revisada sempre que houver alterações relevantes em sua arquitetura, integrações ou operações de tratamento de dados pessoais.
