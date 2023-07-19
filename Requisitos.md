Como e quais funcionalidades foram identificadas para iniciar este projeto, bem como quais estão previstos para incrementos futuros.

### Quadro de Funcionalidades
Parte dos requisitos propostos para o sistema foram obtidos a partir de funcionalidades identificadas em publicações sobre chatbots. A outra parte foi extraída a partir de histórias de usuários construídas durante ou após conversas com estudantes, professores e técnicos da coordenação, onde se buscou identificar que funcionalidades seriam de interesse para estes stakeholders. Estes requisitos permitiram a construção de um quadro de funcionalidades abaixo, classificadas em relação aos papéis ou atividades dos stakeholders envolvidos e hierarquizadas de acordo com a viabilidade e prioridade que teriam para as atividades de desenvolvimento.

Administração | Professores | Acadêmicos | Desenvolvedor
-- | -- | -- | --
\*Responder dúvidas cujas respostas sejam encontradas no Regimento Geral | \*Responder dúvidas quanto a ementa e bibliografia das disciplinas | \*\*Responder dúvidas sobre o centro acadêmico | \*\*\*Apresentar o projeto e responder dúvidas relacionadas ao mesmo
\*\*Responder dúvidas cujas respostas sejam encontradas no blog do curso | \*Orientar o aluno sobre como buscar informações relacionadas ao andamento da disciplina no SIGAA ou Blog (horários, datas de avaliação) | \*\*Responder dúvidas sobre a Atlética | \*Reconhecimento de fala
\*\*\*Responder dúvidas relacionadas ao regulamento para realização de TCC | \*Responder dúvidas quanto a formatação de artigos e trabalhos acadêmicos | \*Responder dúvidas relacionadas a normas de avaliação | \*\*\*Registrar interações com usuários
\*\*\*Responder dúvidas relacionadas ao regulamento para Atividades de Estágio | \*Auxiliar os alunos em estratégias de aprendizagem que podem ter sido usadas pelos veteranos | \*\*Apresentar ou encaminhar os acadêmicos aos departamentos, setores e serviços da universidade | \*Gamificar anotações de aula para revisão dos assuntos
\*Responder dúvidas sobre o uso do SIGAA |   | \*\*Auxiliar na localização de blocos de cursos, laboratórios, setores e serviços | \*Gamificar rotas e percursos dentro da universidade
\*Responder dúvidas sobre a coordenação |   | \*Explicar quais linhas de ônibus chegam à universidade | \*Cadastrar perguntas para acesso por QRcode
  |   | \*Explicar como funcionam as eleições para reitoria e atribuição de cargos como os de reitor ou pró-reitor |  
  |   | \*\*Orientar os acadêmicos quanto a oportunidades de estágio e emprego |  

Legenda: \*\*\*Item essêncial | \*\*Item importante | \*Item desejável

### Visão Geral do Sistema

#### Usuários

   O chatbot poderá ser usado por qualquer usuário do aplicativo Telegram.

#### Premissas

   O aplicativo de troca de mensagens Telegram não terá suas atividades suspensas no país.

#### Restrições

   O chatbot não pode ter integração com serviços da universidade que envolvam o tráfego de informações sensíveis dos estudantes, professores ou técnicos, como e-mails, senhas, notas, números de matrícula, etc.

### Requisitos Funcionais
RF1 - Responder dúvidas cujas respostas sejam encontradas no Regimento Geral da universidade.

RF2 - Responder dúvidas cujas respostas sejam encontradas no blog do curso de computação.

RF3 - Responder dúvidas relacionadas ao regulamento para realização do Trabalho de Conclusão de Curso - TCC.

RF4 - Responder dúvidas relacionadas ao regulamento para Atividades de Estágio.

RF5 - Responder dúvidas sobre o uso do SIGAA.

RF6 - Responder dúvidas quanto a ementa e bibliografia das disciplinas.

RF7 - Orientar os estudantes sobre como buscar informações relacionadas ao andamento da disciplina em fontes como SIGAA e Blog para sanar perguntas sobre adiamento de aulas, horários e datas de avaliação.

RF8 - Responder dúvidas quanto a formatação de artigos e trabalhos acadêmicos.

RF9 - Auxiliar os alunos em estratégias de aprendizagem que podem ter sido usadas pelos veteranos.

RF10 - Responder dúvidas sobre o centro acadêmico.

RF11 - Responder dúvidas sobre a Atlética.

RF12 - Responder dúvidas relacionadas às normas de avaliação da universidade

RF13 - Apresentar ou encaminhar os acadêmicos aos departamentos, setores e serviços da universidade.

RF14 - Auxiliar na localização de blocos de cursos, laboratórios, setores e serviços.

RF15 - Explicar quais linhas de ônibus chegam à universidade.

RF16 - Explicar como funcionam as eleições para reitoria e atribuição de cargos como os de reitor ou pró-reitor.

RF17 - Orientar os acadêmicos quanto a oportunidades de estágio e emprego.

RF18 - Apresentar e responder dúvidas relacionadas ao projeto.

RF19 - Processar mensagens em áudio - Reconhecimento de fala.

RF20 - Registrar interações com usuários

RF21 - Gamificar anotações de aula para revisão dos assuntos.

RF22 - Gamificar rotas e percursos dentro da universidade.

RF23 - Cadastrar perguntas para acesso por QRcode.

RF24 - Responder dúvidas sobre a coordenação

### Requisitos Não Funcionais

#### Usabilidade

RNF1 - O chatbot deve responder a mensagens de texto, utilizando se necessário outros recursos de interface do aplicativo cliente, como botões e menus.

#### Confiabilidade

RNF2 - O chatbot deve ser capaz de alternar entre solicitações de um diálogo identificando corretamente as intenções das mensagens dos usuários que estejam dentro do seu domínio de atuação.

#### Desempenho

RNF3 - O tempo de resposta do chatbot não deve ultrapassar a unidade de segundos.

#### Reusabilidade

RNF4 - O chatbot poderá ser integrado a outras plataformas de mensagens.

#### Segurança

RNF5 - O chatbot não deve automatizar o acesso a sistemas da instituição acadêmica que possam implicar no armazenamento de dados sensíveis de seus usuários.

#### Acessibilidade

RFN6 - O chatbot deve estar acessível a seus usuários pela aplicação cliente Telegram em navegadores e smartphones.