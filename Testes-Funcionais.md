Os testes funcionais representam interações simples e diretas com o chatbot que por questões de praticidade e simplicidade estão documentados em casos de teste por assunto, conforme tabela a seguir.

| Caso de teste | Teste                                 | Resultado |
|---------------|--------------------------------------|-----------|
| CT01          | Saudação com menu de opções          | Sucesso   |
| CT02          | Pergunta sobre TCC                   | Sucesso   |
| CT03          | Pergunta sobre Estágio               | Sucesso   |
| CT04          | Pergunta sobre a Atlética            | Sucesso   |
| CT05          | Pergunta sobre o Centro Acadêmico    | Sucesso   |
| CT06          | Pergunta sobre a coordenação         | Sucesso   |
| CT07          | Pergunta sobre o chatbot             | Sucesso   |
| CT08          | Pergunta fora do escopo do projeto   | Sucesso   |
| CT09          | Pergunta sobre locais dentro da universidade | Sucesso   |
| CT10          | Desambiguação de contexto            | Sucesso   |

Estes testes não cobrem todos os cenários, mas contribuem para verificar o alinhamento entre os requisitos definidos e o software implementado.

### Casos de Teste

#### CT01 - Saudação com menu de opções
Descrição: Testar a resposta do chatbot a uma mensagem de saudação do usuário, apresentando um menu com as opções de diálogos implementados.

Pré-condição: Chatbot ativo e em execução.

Passos:
1. O usuário envia uma mensagem com "oi", "olá" ou "bom dia" para o chatbot.
1. O chatbot deve responder com uma mensagem de saudação e apresentar um menu com as opções de diálogos implementados.

Resultado esperado: O chatbot deve responder corretamente à saudação do usuário.

#### CT02 - Pergunta sobre TCC
Descrição: Testar a resposta do chatbot a uma pergunta relacionada a TCC.

Pré-condição: Chatbot ativo e em execução.

Passos:
1. O usuário envia a mensagem "Como é feito o TCC?" para o chatbot.
1. O chatbot deve responder com uma mensagem explicando as etapas para creditar o TCC.

Resultado esperado: O chatbot deve responder corretamente à pergunta sobre TCC.


#### CT03 - Pergunta sobre Estágio
Descrição: Testar a resposta do chatbot a uma pergunta relacionada a estágio.

Pré-condição: Chatbot ativo e em execução.

Passos:
1. O usuário envia "Como faço para conseguir um estágio?" para o chatbot.
1. O chatbot deve responder com uma mensagem explicando como conseguir um estágio e indicar locais onde houveram registros de estágio de acadêmicos do curso.

Resultado esperado: O chatbot deve responder corretamente à pergunta sobre estágio.

#### CT04 - Pergunta sobre a Atlética
Descrição: Testar a resposta do chatbot a uma pergunta relacionada a Atlética de Computação.

Pré-condição: Chatbot ativo e em execução.

Passos:
1. O usuário envia "O que é a atlética?" para o chatbot.
1. O chatbot deve responder com uma mensagem explicando o que é a atlética.

Resultado esperado: O chatbot deve responder corretamente à pergunta sobre atlética.

#### CT05 - Pergunta sobre o Centro Acadêmico de Computação
Descrição: Testar a resposta do chatbot a uma pergunta relacionada ao Centro Acadêmico de Computação.

Pré-condição: Chatbot ativo e em execução.

Passos:
1. O usuário envia "Qual o contato do centro acadêmico?" para o chatbot.
1. O chatbot deve responder com uma mensagem explicando o contato do centro acadêmico.

Resultado esperado: O chatbot deve responder corretamente à pergunta sobre o centro acadêmico.

#### CT06 - Pergunta sobre a coordenação
Descrição: Testar a resposta do chatbot a uma pergunta relacionada à coordenação.

Pré-condição: Chatbot ativo e em execução.

Passos:
1. O usuário envia "Qual o horário de funcionamento da coordenação?" para o chatbot.
1. O chatbot deve responder com o horário de funcionamento da coordenação.

Resultado esperado: O chatbot deve responder corretamente à pergunta sobre coordenação.

#### CT07 - Pergunta sobre o chatbot
Descrição: Testar a resposta do chatbot a uma pergunta relacionada ao próprio chatbot.

Pré-condição: Chatbot ativo e em execução.

Passos:
1. O usuário envia "Com que tecnologias você foi feito?" para o chatbot.
1. O chatbot deve responder com quais tecnologias foi desenvolvido.

Resultado esperado: O chatbot deve responder corretamente à pergunta sobre o próprio chatbot.

#### CT08 - Pergunta fora do escopo do projeto
Descrição: Testar a resposta do chatbot a uma pergunta que não está dentro do escopo do projeto.

Pré-condição: Chatbot ativo e em execução.

Passos:
1. O usuário envia uma pergunta fora do escopo do projeto para chatbot.
1. O chatbot deve responder com uma mensagem informando que a pergunta está fora do escopo do projeto.

Resultado esperado: O chatbot deve informar que não pode atender a solicitação.

#### CT09 - Pergunta sobre locais dentro da universidade
Descrição: Testar a resposta do chatbot a perguntas sobre locais dentro da universidade.

Pré-condição: Chatbot ativo e em execução.

Passos:
1. O usuário envia uma pergunta sobre onde fica a biblioteca no chatbot.
1. O chatbot verifica se possui a informação solicitada e responde corretamente informando o local da biblioteca.
1. Caso o chatbot não possua a informação solicitada, ele deve responder com uma mensagem informando que ainda não sabe onde fica o local solicitado.

Resultado esperado: O chatbot deve informar corretamente o local solicitado ou informar que ainda não possui a informação solicitada.

#### CT10 - Desambiguação de contexto
Descrição: Testar a situação em que o chatbot lida com uma mensagem que pode se aplicar a mais de um assunto configurado.

Pré-condição: Chatbot ativo e em execução.

Passos:

1. O usuário envia “Como posso participar?”.
1. O chatbot deve responder perguntando ao usuário se ele deseja participar do centro acadêmico, da atlética de computação ou do Projeto Polímata.
1. O usuário deve escolher uma das opções apresentadas pelo chatbot.
1. O chatbot deve responder com as informações correspondentes à opção escolhida.

Resultado esperado: O chatbot deve apresentar as informações corretas ou pedir por mais informações para atender o usuário.

