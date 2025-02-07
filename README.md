# 📌 Estrutura do Projeto

Este projeto foi desenvolvido utilizando **HTML e Tailwind CSS** para o frontend. Abaixo está a organização dos diretórios e arquivos.

## 📂 Estrutura de Diretórios

```
📦 MeuProjeto/
├── 📄 index.html  # Página inicial (Login e opção de Criar Conta)
├── 📂 src/
│   ├── 📂 registro/
│   │   ├── 📂 signup/
│   │   │   ├── 📄 criar-conta.html  # Página para criar uma nova conta
│   ├── 📂 iniciar/
│   │   ├── 📄 iniciar.html  # Página inicial após o login
│   ├── 📂 tabelas/
│   │   ├── 📄 tables.html  # Página para visualizar as ações cadastradas em formato de tabela
├── 📂 img/  # Imagens do projeto
└── 📄 README.md  # Este arquivo explicativo
```

## 📌 Funcionamento do Sistema

1️⃣ **Acesso Inicial (`index.html`)**  
   - O usuário entra no **index.html** para fazer login.  
   - Se já tiver uma conta, insere suas credenciais e acessa o sistema.  
   - Se não tiver conta, clica na opção **"Criar Conta"** para ser redirecionado para a página de registro.

2️⃣ **Registro de Usuário (`src/registro/signup/criar-conta.html`)**  
   - O usuário preenche os dados para criar uma conta.  
   - Após o cadastro, ele será redirecionado para a página de **início**.

3️⃣ **Página Inicial Pós-Login (`src/iniciar/iniciar.html`)**  
   - Exibe:
     - **Imagem de perfil**
     - **Nome do usuário**
     - **Saudação personalizada**
     - **Formulário** para cadastrar ações sustentáveis

4️⃣ **Página de Tabelas (`src/tabelas/tables.html`)**  
   - Lista todas as ações sustentáveis cadastradas pelo usuário.
   - Exibe informações como título, descrição, categoria e pontuação.
   
## 🎨 Estilos e Frameworks Utilizados
- O projeto usa **Tailwind CSS** para estilização rápida e eficiente.

---
✅ **Pronto! O sistema agora está bem estruturado e organizado para facilitar a experiência do usuário.** 🚀

