# 🚀 Projeto DevOps na AWS

Projeto prático de deploy de aplicação estática utilizando Docker dentro de uma instância EC2 na AWS.

---

## 📌 Sobre o Projeto

Este projeto demonstra na prática conhecimentos em:

- Provisionamento de servidor na AWS
- Containerização com Docker
- Servidor Web Nginx
- Deploy manual em ambiente Linux
- Versionamento com Git e GitHub

---

## 🏗 Arquitetura da Solução

Usuário → Internet → AWS EC2 → Docker → Nginx → Aplicação HTML

---

## 🛠 Tecnologias Utilizadas

- AWS EC2
- Docker
- Nginx
- Linux (Ubuntu)
- Git & GitHub

---

## 📂 Estrutura do Projeto


portfolio-devops/
│
├── Dockerfile
├── index.html
├── css/
│   └── style.css
└── README.md


---

## ⚙️ Como Executar o Projeto

### 1️⃣ Clonar o repositório


git clone git@github.com:SantRhay/devops-aws-docker-project.git
cd devops-aws-docker-project


### 2️⃣ Build da imagem Docker


docker build -t rayane-portfolio .


### 3️⃣ Executar o container


docker run -d -p 80:80 rayane-portfolio


---

## 🌐 Acesso à Aplicação

A aplicação estará disponível via IP público da EC2:


http://SEU-IP-PUBLICO


---

## 🎯 Objetivo

Projeto desenvolvido para consolidar conhecimentos em Cloud e DevOps, demonstrando habilidades práticas em:

- Deploy manual em ambiente Linux
- Containerização de aplicação
- Publicação de projeto no GitHub
- Estruturação profissional de repositório

---

## 📈 Próximos Passos (Evolução do Projeto)

- Implementar CI/CD com GitHub Actions
- Automatizar deploy
- Provisionar infraestrutura com Terraform
- Implementar HTTPS com Certbot

---

## 👩‍💻 Desenvolvido por

Rayane Santana  
Projeto de estudo DevOps & Cloud
