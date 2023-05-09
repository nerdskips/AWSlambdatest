# AWSlambdatest
Teste da função serverless AWS usando o Lambda, arquivo em node.js

Neste projeto, provisionei um banco de dados não relacional na AWS utilizando o DynamoDB e o AWS Lambda, para que o meu banco de dados fosse construído de forma
serverless.

Utilizei também os IAM Roles para dar as permissões corretas as minhas funções lambda, que estão dentro da pasta "src".

Neste ambiente é possível fazer upload de dados para seu banco de forma serverless e utilizando códigos no Amazon CLI, tornando muito mais prático a construção
dos bancos de dados.

Também é possível ver todos os logs de alterações realizadas neste ambiente utilizando o CloudWatch, que te da um histórico de tudo que foi feito desde a criação
do seu banco.

Os arquivos foram feitos em Node.js mas podem ser feitos em diversas linguagens também.
