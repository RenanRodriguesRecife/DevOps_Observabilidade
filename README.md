# DevOps_Observabilidade

Observabilidade é a forma que você tem para entender o que está acontecendo no seu sistema (Semelhante a uma caixa preta que tem dados entrado e saindo e você quer entender o que tem ali dentro)

- Logs: dados de coisas que aconteceram no passado no seu sistema

- Métricas: Medir o que está acontecendo no seu sistema, quanto tem de CPU, quantas vendas aconteceram, clicks por hora

- Tracing (rastreabilidade): Você sabe por onde entrou uma Request
Ex:

A pessoa entrou no site -> bateu no sistema -> caiu no banco de dados -> mandou uma mensagem foi para RabbitMQ -> Caiu em outro sistema leu o banco de dados -> ...
