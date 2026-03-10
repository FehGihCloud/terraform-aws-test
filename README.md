# Terraform AWS Challenge

Este projeto implementa uma infraestrutura na AWS utilizando Terraform.

## Serviços implementados

1. Frontend estático hospedado no Amazon S3
2. Backend containerizado executando no Amazon ECS
3. Rotina automatizada diária que gera arquivos no S3 utilizando AWS Lambda e EventBridge

## Tecnologias utilizadas

- Terraform
- AWS ECS
- AWS ECR
- AWS Lambda
- AWS S3
- AWS EventBridge
- Docker

## Estrutura do projeto

backend/
    Dockerfile
    aplicação backend

index.html
    aplicação frontend estática

main.tf
    definição da infraestrutura utilizando Terraform

## Como executar

1. Instalar Terraform
2. Configurar credenciais da AWS
3. Executar:

terraform init  
terraform plan  
terraform apply

## Autor

Felipe França
