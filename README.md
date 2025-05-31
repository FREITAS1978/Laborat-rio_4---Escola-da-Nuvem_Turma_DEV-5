# Laboratório_Escola da Nuvem_Turma DEV-5

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

- [x] AWS Lambda – Backend com lógica em Python.
- [x] API Gateway - Rota GET com integração ao Lambda.
- [x] Amazon S3 – Frontend com "index.html" estático hospedado.
- [x] CORS – Permissão para comunicação entre domínios.
- [x] Comunicação via JSON e HTTP.
- [x] IAM e políticas de bucket.
- [x] GitHub – Código versionado com boas práticas.

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
| Função Lambda | ![ 1 Função_Lambda_Criada](https://github.com/user-attachments/assets/731b967f-335c-4184-bbfa-e6007f2548e6) |
| API Gateway | ![ 2 API_Criada](https://github.com/user-attachments/assets/fa20f5ce-ea65-4f75-9fbf-0a8f5ca1b60a)  |
| Bucket S3 | ![ 3 Bucket_Criado](https://github.com/user-attachments/assets/7ca849bc-3dac-4744-8925-b91ffc9d4491)  |
| Site Funcionando | ![ 4 Site_Funcionando](https://github.com/user-attachments/assets/22b716ca-6cde-4e89-a8a0-ccfcef6482c0)  |

---
