# Projeto Linux – Infrastructure as Code (IaC)

## 📌 Descrição

Este projeto contém scripts em Shell Script para automatizar a criação de usuários, grupos, diretórios e permissões no Linux, aplicando o conceito de **Infrastructure as Code (IaC)**.

O objetivo é padronizar a configuração de ambientes Linux de forma rápida, reproduzível e automatizada.

## 🛠️ Tecnologias Utilizadas

- Linux
- Shell Script (Bash)
- Git e GitHub

## 📂 Estrutura do Projeto

- `cria_usuarios_convidados.sh`  
  Script responsável pela criação de usuários convidados com troca obrigatória de senha no primeiro login.

- `estrutura_diretorios_usuarios.sh`  
  Script responsável por:
  - Criar diretórios do sistema
  - Criar grupos de usuários
  - Criar usuários e associá-los aos grupos
  - Definir permissões e proprietários dos diretórios

## ▶️ Como Executar

⚠️ **É necessário executar como root ou com sudo**

```bash
chmod +x cria_usuarios_convidados.sh
chmod +x estrutura_diretorios_usuarios.sh

sudo ./estrutura_diretorios_usuarios.sh
sudo ./cria_usuarios_convidados.sh
```
