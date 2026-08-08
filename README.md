# 📝 Editor de Markdown

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)
![Electron](https://img.shields.io/badge/Electron-47848F?style=flat&logo=electron&logoColor=white)
![License](https://img.shields.io/badge/license-MIT-green)

Este é um editor de Markdown simples e funcional, desenvolvido com HTML, CSS, JavaScript e a biblioteca Showdown para converter Markdown em HTML. O editor conta com uma interface intuitiva para facilitar a edição e a pré-visualização de documentos Markdown. Também foi desenvolvido como aplicação desktop usando Electron.

## ✨ Funcionalidades

**Edição de Markdown:** permite criar e editar arquivos Markdown diretamente no navegador ou no app desktop baseado em Electron.

**Pré-visualização em tempo real:** a pré-visualização do conteúdo Markdown é atualizada instantaneamente enquanto o usuário digita.

**Formatação de texto:**
- Negrito: `Ctrl+B`
- Itálico: `Ctrl+I`
- Títulos: inserir títulos H1 e H2
- Listas: criar listas ordenadas e não ordenadas
- Citações: inserir blocos de citação
- Blocos de código: inserir blocos de código
- Links e imagens: interface simples para adicionar links e imagens por URL

**Modo escuro:** alterne entre os temas claro e escuro para melhor experiência de uso.

**Salvar e carregar arquivos:** salve o conteúdo Markdown localmente ou carregue arquivos `.md` existentes.

## 📦 Instalação

Para instalar e executar este editor na sua máquina, siga estes passos:

### Pré-requisitos

Certifique-se de ter o Node.js (versão 14 ou superior) instalado no seu sistema.

### Passos

1. Clone o repositório:
```
git clone https://github.com/andersonmoegel/markdown-editor.git
cd markdown-editor
```
2. Instale as dependências do projeto:
```
npm install
```
3. Execute o app Electron:
```
npm start
```

Isso abrirá o editor de Markdown em uma janela do Electron.

## 🚀 Como Usar

**Edição de texto:** escreva seu conteúdo na área do editor.

**Formatação de texto:** selecione o texto e use os botões da barra de ferramentas para aplicar formatação.

**Pré-visualização do conteúdo:** a pré-visualização em Markdown é atualizada em tempo real enquanto você digita.

**Salvar Markdown:** clique no ícone de salvar para baixar o arquivo Markdown.

**Carregar Markdown:** clique no ícone de abrir para carregar um arquivo Markdown existente.

## ⚙️ Funcionalidades Adicionais

O conteúdo do editor é salvo automaticamente no `localStorage` do navegador para persistência da sessão.

O modo escuro pode ser ativado ou desativado pelo botão no canto superior direito.

## 🛠️ Tecnologias Utilizadas

**Electron:** framework para criar aplicações desktop multiplataforma com tecnologias web.

**Showdown.js:** biblioteca para converter Markdown em HTML.

**HTML & CSS:** usados para o design da interface do usuário.

**JavaScript:** gerencia a lógica do app e o tratamento de eventos.

## 📄 Licença

Este projeto está licenciado sob a licença MIT.
