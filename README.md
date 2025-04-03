# PadreGino's Delivery

PadreGino's Delivery é um projeto de exemplo para um sistema de pedidos de pizza online, desenvolvido como parte do curso "The Complete Intro to React v9" por Brian Holt para Frontend Masters.

## Estrutura do Projeto

O projeto está estruturado da seguinte forma:

## Tecnologias Utilizadas

- **React**: Biblioteca para construção de interfaces de usuário.
- **TanStack Router**: Gerenciamento de rotas.
- **TanStack Query**: Gerenciamento de estado assíncrono.
- **Vite**: Ferramenta de build e desenvolvimento.
- **Vitest**: Framework de testes.
- **Playwright**: Testes de navegador.
- **Happy DOM**: Ambiente DOM para testes.
- **ESLint**: Ferramenta de linting.
- **Prettier**: Formatação de código.

## Funcionalidades

- **Página Inicial**: Apresenta a marca e links para as páginas de pedido, pedidos passados e contato.
- **Pedido de Pizza**: Permite selecionar o tipo e tamanho da pizza, adicioná-la ao carrinho e realizar o checkout.
- **Pizza do Dia**: Exibe a pizza do dia com informações detalhadas.
- **Pedidos Passados**: Lista pedidos anteriores com detalhes e permite visualizar informações específicas.
- **Contato**: Formulário para envio de mensagens de contato.
- **Carrinho de Compras**: Exibe os itens adicionados ao carrinho e o total do pedido.

## Scripts Disponíveis

Os scripts disponíveis no arquivo `package.json` incluem:

- `npm run dev`: Inicia o servidor de desenvolvimento.
- `npm run build`: Gera a build de produção.
- `npm run preview`: Visualiza a build de produção.
- `npm run test`: Executa os testes.
- `npm run test:ui`: Abre a interface de usuário do Vitest.
- `npm run coverage`: Gera o relatório de cobertura de testes.
- `npm run lint`: Executa o ESLint.
- `npm run format`: Formata o código com Prettier.

## Configuração do Ambiente

1. Certifique-se de ter o Node.js instalado.
2. Instale as dependências com:

   ```sh
   npm install
   ```

## Dependências Instaladas

O projeto utiliza as seguintes dependências principais:

- **Vite**: Ferramenta de build e desenvolvimento. Instalado com:

  ```sh
  npm install vite
  ```

- **React** e **React DOM**: Biblioteca para construção de interfaces de usuário. Instalado com:

  ```sh
  npm install react react-dom
  ```

- **ESLint**: Ferramenta de linting. Instalado com:

  ```sh
  npm install eslint --save-dev
  ```

- **Prettier**: Formatação de código. Instalado com:

  ```sh
  npm install prettier --save-dev
  ```

- **TanStack Router**: Gerenciamento de rotas. Instalado com:

  ```sh
  npm install @tanstack/react-router @tanstack/router-plugin @tanstack/router-devtools
  ```

- **TanStack Query**: Gerenciamento de estado assíncrono. Instalado com:
  ```sh
  npm install @tanstack/react-query @tanstack/react-query-devtools
  ```

### Dependências para Testes (Opcionais)

Caso queira realizar testes na aplicação, as seguintes dependências foram instaladas:

- **Vitest**: Framework de testes. Instalado com:

  ```sh
  npm install vitest @vitest/ui @vitest/browser @vitest/coverage-istanbul @vitest/coverage-v8 --save-dev
  ```

- **Playwright**: Testes de navegador. Instalado com:

  ```sh
  npm install playwright --save-dev
  ```

- **Happy DOM**: Ambiente DOM para testes. Instalado com:

  ```sh
  npm install happy-dom --save-dev
  ```

- **Testing Library**: Biblioteca para testes de componentes React. Instalado com:

  ```sh
  npm install @testing-library/react --save-dev
  ```

- **Vitest Fetch Mock**: Mock para testes de fetch. Instalado com:
  ```sh
  npm install vitest-fetch-mock --save-dev
  ```

### Plugins e Ferramentas Adicionais

- **ESLint Plugins**: Plugins adicionais para ESLint. Instalado com:

  ```sh
  npm install eslint-config-prettier eslint-plugin-react globals --save-dev
  ```

- **Vite Plugin React**: Plugin para integração do React com Vite. Instalado com:
  ```sh
  npm install @vitejs/plugin-react --save-dev
  ```

Certifique-se de que todas essas dependências estão listadas no arquivo `package.json` para facilitar a instalação em outros ambientes.
