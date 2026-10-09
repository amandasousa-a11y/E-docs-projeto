# 📃E-Docs - Gerenciador de Documentos

Ferramenta via linha de comando em Node.js desenvolvida para a equipe de Qualidade gerenciar o estado e as versões de documentos internos (manuais, relatórios e políticas).

--- 

## 📋 Sobre o Projeto

O **DocKeeper JS** foi criado para resolver a necessidade da equipe de Qualidade de controlar a evolução de documentos (como manuais, relatórios e políticas).
A cada alteração feita no texto de um documento, o sistema atualiza automaticamente a versão (ex: de `1.0` para `1.1`) e mantém um histórico completo das alterações realizadas.

---

## ⚙️ Funcionalidades

- 📌**Cadastrar Documento:** Cria um novo documento com ID, título, conteúdo, data de criação e versão inicial `1.0`.
- 🔄️**Atualizar Conteúdo:** Permite editar o texto de um documento e incrementa a versão automaticamente (`1.0` ➔ `1.1`).
- 📋**Listar Documentos:** Exibe todos os documentos cadastrados com seus respectivos títulos e versões atuais.
- 📜 **Histórico / Status:** Exibe os detalhes de um documento específico e seu histórico de alterações.

---

## 🛠️ Tecnologias Utilizadas

* **JavaScript** (Lógica do sistema)
* **Node.js** (Ambiente de execução)
* **Git & GitHub** (Versionamento e organização profissional)

---
## 🚀 Como Baixar e Executar o Projeto!
---

### Passo 1: Instalar os programas necessários
Antes de começar, você precisa ter 3 programas gratuitos instalados no seu computador:

1. **Node.js** (Necessário para rodar o código): [Baixar Node.js aqui](https://nodejs.org/)
   * *Dica:* Baixe a versão recomendada (LTS) e clique em "Avançar/Next" em todas as telas da instalação.
2. **Git** (Necessário para baixar o projeto): [Baixar Git aqui](https://git-scm.com/)
3. **VS Code** (O leitor de código): [Baixar VS Code aqui](https://code.visualstudio.com/)

---

### Passo 2: Copiar o link do projeto no GitHub
1. No topo desta página do GitHub, procure por um botão verde escrito **`<> Code`**.
2. Clique nele. Uma janelinha vai se abrir.
3. Clique no ícone de **duas folhinhas** (ao lado do link) para copiar o endereço do projeto.

---

### Passo 3: Abrir o VS Code no seu computador
1. Abra o programa **Visual Studio Code** no seu computador.
2. Na barra de menu superior, clique na opção **Terminal** e depois em **Novo Terminal** (New Terminal).
3. Uma janela cinza/preta vai se abrir na parte de baixo da tela. É ali que vamos digitar os comandos.

---

### Passo 4: Clonar/baixar o projeto
1. Clique com o mouse dentro da janela do terminal que se abriu na parte de baixo.
2. Digite o comando `git clone` seguido de um espaço e **cole o link** que você copiou no Passo 2. 
   
   Ele vai ficar assim:
   ```bash
   git clone [https://github.com/SEU_USUARIO/dockeeper-js.git](https://github.com/SEU_USUARIO/dockeeper-js.git)
  
1. Aperte a tecla **ENTER** no seu teclado.

2. Aguarde 3 segundos **O Git vai baixar a pasta do projeto para o seu computador.**

### Passo 5: Entrar na pasta do projeto 

No mesmo terminal, digite o comando abaixo para "abrir" a pasta que acabou de ser baixada e aperte ENTER:

**cd dockeeper-js**

### Passo 6: Rodar o programa!

Agora, digite o comando final para executar o sistema e aperte ENTER:

**node index.js**
rio
Abra o seu VS Code e execute o comando abaixo para baixar uma cópia do código:
