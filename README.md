# Desafio TQI com DIO

## Esse repositório tem por finalidade trazer breves explicações e mostrar os diagramas sobre o curso da TQI.

### Diagrama 1 - Amazon EC2 com EBS

![Teste](images/Página-1.png)

### Conceitos Iniciais
O Amazon EC2 (<strong>Amazon Elastic Compute Cloud</strong>) é responsável pela criação de instâncias, que são servidores virtuais nos serviços da AWS.
Em conjunto ao EC2, tem o Amazon EBS (<strong>Amazon Elastic Block Store</strong>), que adiciona blocos de memória à sua instância, como um computador e um pendrive.
Por fim, o Amazon RDS (<strong>Amazon Relational Database Service</strong>) é o mantenedor e facilitador de configurações de banco de dados na web.

### Explicação
O cliente envia algum arquivo para um sistema, e esse arquivo vai para o D - EBS (para a nuvem), que recebe as entradas. O EC2 entra em ação e processa o arquivo do cliente, ele manda os arquivos processados para o E - EBS. E Por fim, depois de validar, manda ao banco de dados no RDS.

### Diagrama 2 - Amazon S3 com Lambda Function

![Teste](images/Página-2.png)
