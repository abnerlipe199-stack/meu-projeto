# Guia Definitivo: Ciclo de Vida de um Projeto no GitHub

---

## 🚀 Sessão 1: O Passo a Passo da Criação e Envio

Este guia documenta o caminho completo para inicializar um projeto do zero em ambiente local e publicá-lo de forma segura e versionada no GitHub.

---

### 1. O Início: Criando o Repositório Remoto no GitHub

Para disponibilizar um projeto na nuvem, o primeiro passo é reservar o espaço remoto na plataforma:

1. **Acesso e Criação:**
   - Acesso a minha conta no GitHub.
   - No canto superior direito, clico no ícone `+` e seleciono **New repository**.

2. **Configurações Iniciais Importantes:**
   - **Repository name:** Defino um nome padronizado em minúsculas (ex.: `meu-projeto`).
   - **Description (opcional):** Uma frase curta explicando o objetivo do repositório.
   - **Visibility:** Escolho entre Public ou Private.
   - **Initialize this repository with:** Deixo desmarcadas as opções de README, .gitignore e License para que o repositório remoto nasça completamente vazio, evitando conflitos de histórico com a máquina local.

3. Finalizo clicando em **Create repository**.

---

### 2. A Conexão e Primeiro Envio: Terminal Local para a Nuvem

Com o repositório remoto criado, preparo o ambiente na minha máquina através do terminal e envio os arquivos:

```bash
cd caminho/para/a/pasta

git init

git branch -M main

git remote add origin [https://github.com/abnerlipe199-stack/meu-projeto.git](https://github.com/abnerlipe199-stack/meu-projeto.git)

git remote -v

git add .

git commit -m "docs: trabalho ciclo de vida github"

git push -u origin main
