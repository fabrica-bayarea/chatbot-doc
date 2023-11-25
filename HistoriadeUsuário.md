# HISTÓRIA DE USUÁRIO

## Notificação para Atendentes

**Como** um atendente do suporte humano, **eu quero** ser notificado quando um usuário aceita o redirecionamento para o suporte humano **para que** eu possa fornecer assistência imediata.

### Critérios de aceitação (BDD)

##### Cenário 1: Notificação para Atendentes.

**Dado** que um usuário aceitou o redirecionamento.

**Quando** o redirecionamento é aceito.

**Então** o sistema deve notificar o atendente do suporte humano.

##### Cenário 2: Forma de Notificação.

**Dado** que um usuário aceitou o redirecionamento.

**Quando** o sistema notifica o atendente.

**Então** a notificação deve ser realizada através de alertas visuais e sonoros.

## Histórico de Conversa

**Como** um atendente do suporte humano, **eu quero** acessar o histórico completo da conversa entre o usuário e o chatbot **para que** eu possa entender o contexto da interação.

### Critérios de aceitação (BDD)

##### Cenário 1: Acesso ao Histórico de Conversa.

**Dado** que fui notificado sobre um novo usuário com problemas com o chatbot.

**Quando** desejo acessar o histórico de conversa.

**Então** o sistema deve permitir que eu acesse o histórico completo.

##### Cenário 2: Apresentação do Histórico.

**Dado** que estou acessando o histórico de conversa.

**Quando** visualizo o histórico.

**Então** o histórico deve ser apresentado de forma clara e organizada, destacando as mensagens do usuário e do chatbot, bem como quaisquer informações relevantes.

## Resposta do Atendente

**Como** um atendente do suporte humano, **eu quero** ser capaz de fornecer uma resposta em substituição ao chatbot **para que** o usuário tenha uma boa experiência usando o chatbot.

### Critérios de aceitação (BDD)

##### Cenário 1: Resposta do Atendente em Substituição ao Chatbot.

**Dado** que estou interagindo com um usuário no suporte humano.

**Quando** desejo fornecer uma resposta em substituição ao chatbot.

**Então** o sistema deve permitir que eu o faça.

##### Cenário 2: Envio da Resposta do Atendente.

**Dado** que fornece uma resposta em substituição ao chatbot.

**Quando** a resposta é enviada.

**Então** o sistema deve identificar a resposta do atendente feita em substituição ao chatbot e enviá-la através do e-mail.

## Finalizar Atendimento

**Como** um atendente do suporte humano, **eu quero** ser capaz de encerrar o atendimento assim que a resposta for enviada **para que** a listagem de atendimentos fique organizada e para evitar confusão quando for responder a um usuário.

### Critérios de aceitação (BDD)

##### Cenário 1: Finalizar Atendimento do usuário.

**Dado** que a resposta correta em substituição ao chatbot foi enviada por e-mail.

**Quando** eu, atendente do suporte, clicar no botão de finalizar.

**Então** o sistema deve identificar que o atendimento foi encerrado e remover o usuário da lista de novos atendimentos.
