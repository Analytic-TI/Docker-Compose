# 🐳 Docker Scripts Collection

Repositório com scripts Docker para subir ambientes prontos de forma rápida e prática.

## 📦 Containers disponíveis

### 📁 FTP Server + File Manager
- **Imagem FTP:** `stilliard/pure-ftpd:hardened`  
- **Interface Web:** `filebrowser/filebrowser`  
- **Descrição:**  
  Servidor FTP seguro com suporte a usuários virtuais, acompanhado de uma interface web para gerenciamento de arquivos.

---

### 🗄️ PostgreSQL Database
- **Imagem:** `postgres:15`  
- **Descrição:**  
  Banco de dados PostgreSQL pronto para uso em desenvolvimento ou testes.

---

### 🛠️ pgAdmin (Gerenciador PostgreSQL)
- **Imagem:** `dpage/pgadmin4:latest`  
- **Descrição:**  
  Interface web para administração do PostgreSQL, permitindo gerenciar bancos, executar queries e monitorar o ambiente.

---

## 🚀 Como usar

```bash
docker compose up -d