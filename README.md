# dio-live-SAM
Repositório para o Live Coding do dia 15/12/2021 sobre infraestrutura como código na AWS utilizando o AWS Serverless Application Model - SAM

## Serviços utilizados

 - AWS CLI
 - AWS SAM CLI
 - AWS SAM Template
 - Git
 
## Recursos AWS utilizados

 - AWS Lambda
 - Amazon API Gateway
 - Amazon DynamoDB
 - AWS IAM
 - AWS CloudFormation

## Instruções para desenvolvimento

### Criar conta na AWS e instalar o AWS SAM CLI

 - [Criar conta na AWS](https://aws.amazon.com/pt/premiumsupport/knowledge-center/create-and-activate-aws-account/)
 - [Download SAM CLI](https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html)

### Configurar credenciais de usuário da AWS

 - ```aws configure``` e inserir as credenciais do usuário criado no AWS IAM

### Desenvolver a aplicação

 - Clonar este repositório: ```git clone https://github.com/cassianobrexbit/dio-live-SAM.git```
 - Acessar a pasta ```src```
 - Iniciar o AWS SAM: ```sam init```
 - Validar o template AWS SAM ```sam validate```
 - Build ```sam build```
 - Deploy da aplicação (assistido) ```sam deploy --guided```
 - Testar com CURL ou Postman
 - Limpar os recursos criados ```sam delete```
