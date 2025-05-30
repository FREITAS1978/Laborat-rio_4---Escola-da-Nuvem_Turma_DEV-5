# Laboratório_Escola da Nuvem_Turma DEV-5 (************ Em edição ******************)

# 🎯 Jogo de Adivinhação Serverless com AWS Lambda, API Gateway e S3

![AWS Lambda](https://img.shields.io/badge/AWS-Lambda-orange?logo=amazon-aws)
![API Gateway](https://img.shields.io/badge/AWS-API--Gateway-blue?logo=amazon-aws)
![Amazon S3](https://img.shields.io/badge/AWS-S3-red?logo=amazon-aws)
![Status](https://img.shields.io/badge/Status-Concluído-brightgreen)
![Licença: MIT](https://img.shields.io/badge/Licença-MIT-yellow.svg)

Este projeto é um jogo simples de adivinhação de números, desenvolvido como parte do laboratório da **Escola da Nuvem💙**. Ele utiliza **AWS Lambda**, **API Gateway** e **S3** para criar uma aplicação web totalmente serverless.

---

## 🧠 Funcionalidades

- Backend serverless com AWS Lambda (Python)
- Rota GET via API Gateway
- Site estático hospedado no Amazon S3
- Comunicação entre domínios via CORS
- Acesso público configurado por política de bucket

---

## 🛠️ Tecnologias Utilizadas

- [x] AWS Lambda
- [x] API Gateway
- [x] Amazon S3
- [x] HTML / JavaScript no frontend
- [x] Comunicação via JSON e HTTP
- [x] IAM e políticas de bucket

---

## 🌐 Demonstração ao Vivo

> 🔗 https://s3-website-fabiofreitas.s3.us-east-1.amazonaws.com/index.html

---

## 🚀 Como Funciona

1. O usuário digita um número de 1 a 10.
2. O site envia a tentativa por meio da API Gateway.
3. A API aciona uma função Lambda que processa o número.
4. O resultado é retornado e exibido na tela.

---

## 🧪 Prints do Projeto (***************   Em Edição *************)

| Etapa | Imagem |
|------|--------|
| Função Lambda | ![](prints/lambda.png) |
| API Gateway | ![](prints/api_gateway.png) |
| Bucket S3 | ![](prints/s3_bucket.png) |
| Site Funcionando | ![](prints/site_funcionando.png) |
| Publicação LinkedIn | ![](prints/linkedin_post.png) |

---
