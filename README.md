# NLW Agents - Web

Este projeto é a interface web para a aplicação **NLW Agents**, desenvolvida durante a edição "Agents" do evento Next Level Week da [Rocketseat](https://rocketseat.com.br).

## 🚀 Tecnologias Utilizadas

A stack principal utilizada no desenvolvimento deste projeto foi:

- **React**: Biblioteca para construção de interfaces de usuário.
- **TypeScript**: Superset do JavaScript que adiciona tipagem estática.
- **Vite**: Ferramenta de build moderna e rápida para desenvolvimento web.
- **React Router DOM**: Para gerenciamento de rotas na aplicação.
- **Tailwind CSS**: Framework CSS utility-first para estilização.
- **shadcn/ui**: Coleção de componentes de UI reusáveis, construídos sobre o Tailwind CSS.
- **Biome**: Ferramenta integrada para formatação e linting de código, garantindo a consistência e qualidade do código.

## ✨ Funcionalidades

Atualmente, a aplicação conta com as seguintes funcionalidades:

- **Listagem de Salas:** Visualize uma lista de salas criadas recentemente na página inicial.
- **Detalhes da Sala:** Cada item da lista exibe o nome da sala, há quanto tempo foi criada e o número de perguntas existentes.
- **Acesso Rápido:** Entre em uma sala diretamente da lista para participar ou visualizar as discussões.
- **Gravação de Áudio:** Dentro de uma sala, é possível gravar áudios que são enviados em tempo real para o servidor, permitindo a transcrição e análise posterior.

## ⚙️ Configuração e Setup

Siga os passos abaixo para configurar e executar o projeto em seu ambiente local.

### Pré-requisitos

Antes de começar, certifique-se de ter instalado:

- [Node.js](https://nodejs.org/) (versão 18 ou superior)

### Instalação

1.  Clone o repositório do projeto:
    ```bash
    git clone git@github.com:luandstv/nlw-agents-frontend.git
    ```
2.  Navegue até o diretório do projeto:
    ```bash
    cd nlw-agents-frontend
    ```
3.  Instale as dependências:
    ```bash
    npm install
    ```

### Executando o Projeto

Para iniciar o servidor de desenvolvimento, execute o seguinte comando:

```bash
npm run dev
```

A aplicação estará disponível em `http://localhost:5173` (ou outra porta, caso a 5173 já esteja em uso).
