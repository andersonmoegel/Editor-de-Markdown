# Editor de Markdown

Este é um editor de Markdown simples e funcional, desenvolvido com HTML, CSS, JavaScript e utilizando a biblioteca Showdown para conversão de Markdown para HTML. O editor conta com uma interface intuitiva para facilitar a edição e visualização de documentos em Markdown. Também foi desenvolvido como um aplicativo de desktop usando Electron.

## Funcionalidades

**Edição de Markdown**: Permite criar e editar arquivos Markdown diretamente no navegador ou em um aplicativo Electron.

**Pré-visualização em tempo real:** A visualização do conteúdo em Markdown é atualizada instantaneamente à medida que o usuário digita.

**Formatação de texto:**
**Negrito:** Ctrl+B

**Itálico:** Ctrl+I

**Título e Subtítulo:** Inserção de títulos (H1 e H2)

**Listas:** Criação de listas numeradas e não numeradas

**Citações:** Inserção de citações

**Código:** Inserção de blocos de código

**Inserção de links e imagens:** Interface simples para adicionar links e imagens ao texto com URLs.

**Modo escuro:** Alterna entre o modo claro e o modo escuro para melhorar a experiência do usuário.

**Salvamento e carregamento de arquivos:** Salve o conteúdo Markdown localmente ou carregue arquivos existentes.

## Instalação
Para instalar e executar este editor em sua máquina, siga as etapas abaixo:

**Pré-requisitos**

[Node.js](https://nodejs.org/) (versão 14 ou superior) deve estar instalado na sua máquina.

**Passos**

* Clone o repositório:

```
git clone https://github.com/andersonmoegel/Editor-de-Markdown.git
cd editor-markdown
```

* Instale as dependências do projeto:

```
npm install

```

* Execute o aplicativo Electron:

```
npm start

```

Isso abrirá o editor de Markdown em uma janela de aplicativo Electron.


## Como Usar


**Edição de texto:** Escreva seu conteúdo no campo de edição.

**Formatar texto:** Selecione o texto e use os botões da barra de ferramentas para aplicar a formatação desejada.

**Visualizar conteúdo:** A visualização do Markdown será atualizada em tempo real à medida que você digita.

**Salvar Markdown:** Clique no ícone de salvar para baixar o arquivo Markdown.

**Carregar Markdown:** Clique no ícone de abrir para carregar um arquivo Markdown existente.

## Funcionalidade Adicional

O conteúdo de texto do editor é salvo automaticamente no localStorage do navegador para persistência entre sessões.

A interface de modo escuro pode ser ativada ou desativada usando o botão no canto superior direito.

## Tecnologias Utilizadas

**Electron:** Framework para construir aplicativos desktop usando tecnologias web.

**Showdown.js:** Biblioteca para converter Markdown em HTML.

**HTML e CSS:** Para construção da interface do usuário.

**JavaScript:** Lógica de interação e manipulação de eventos.


##Licença

Este projeto é licenciado sob a MIT License.
