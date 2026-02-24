![Deploy Status](https://github.com/SantRhay/devops-aws-docker-project.git/workflows/deploy.yml/badge.svg)

# 🚀 Projeto DevOps na AWS

Projeto prático demonstrando CI/CD automatizado utilizando AWS EC2, Docker e GitHub Actions.

---

## 📌 Arquitetura

- GitHub (repositório)
- GitHub Actions (pipeline CI/CD)
- AWS EC2 (servidor)
- Docker (containerização)
- Nginx (servidor web)
- Linux Ubuntu

---

## ⚙️ Fluxo de Deploy

1. Desenvolvedor realiza git push
2. GitHub Actions é acionado automaticamente
3. Pipeline conecta via SSH na EC2
4. Docker build da aplicação
5. Container é recriado automaticamente
6. Aplicação atualizada em produção

---

## 🔐 Segurança

- Autenticação via chave SSH
- Secrets protegidos no GitHub
- Security Group liberando apenas portas necessárias

---

## 🌐 Aplicação Online

http://54.196.166.20

---

## 🧠 Conceitos aplicados

- CI/CD
- Automação de Deploy
- Containerização
- Infraestrutura em Cloud
- Segurança com SSH
