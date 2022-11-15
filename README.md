# Microsserviço de Envio de E-mail
Um microsserviço de envio de email que utiliza as tecnologias Java, SpringBoot, Spring Rest, Spring Email, o servidor SMTP do Gmail e, para mensageria, o RabbitMQ, utilizando o Spring AMQP.

# Como Utilizar
Após fazer o clone por meio do `git clone`, você deverá alterar as configurações no arquivo `resources/application.properties`. Lá, você deverá alterar as variáveis de conexão ao `Banco de Dados`, caso estejam diferentes das suas, bem como alterar as variáveis de `Email` e do `RabbitMQ`.

Para alterar o email, você pode seguir este tutorial do próprio Google: https://support.google.com/accounts/answer/185833

Para alterar o rabbitmq, cria uma conta no seguinte site, e siga as instruções: https://www.cloudamqp.com/
