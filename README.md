# PadreGino's Delivery

PadreGino's Delivery is a sample project for an online pizza ordering system, developed as part of the course **"The Complete Intro to React v9"** by Brian Holt for Frontend Masters.

### Demonstração

![Demonstração do Projeto](/screenshots/Padre%20GIno's.gif)

---

## Pré-requisitos

Antes de começar, certifique-se de ter as seguintes versões instaladas:

- **Node.js**: Versão mínima 16.x
- **npm**: Versão mínima 8.x

---

## Configuração do `.env`

Para configurar o ambiente de desenvolvimento, crie um arquivo `.env.development` na raiz do diretório `pizza-client` com o seguinte conteúdo:

```env
VITE_API_URL=http://localhost:3000
```

Substitua `http://localhost:3000` pela URL da API do ambiente de desenvolvimento, se necessário.

---

## Project Structure

The project is organized as follows:

- **Home Page**: Showcases the brand and provides links to the order, past orders, and contact pages.
- **Pizza Ordering**: Allows users to select the type and size of pizza, add it to the cart, and proceed to checkout.
- **Pizza of the Day**: Displays the daily special with detailed information.
- **Past Orders**: Lists previous orders with details and allows viewing specific information.
- **Contact**: A form for sending contact messages.
- **Shopping Cart**: Displays added items and the total order amount.

---

## Technologies Used

The project leverages the following technologies:

- **React**: Library for building user interfaces. [Documentation](https://react.dev/)
- **TanStack Router**: Routing management. [Documentation](https://tanstack.com/router)
- **TanStack Query**: Asynchronous state management. [Documentation](https://tanstack.com/query)
- **Vite**: Build and development tool. [Documentation](https://vitejs.dev/)
- **Vitest**: Testing framework. [Documentation](https://vitest.dev/)
- **Playwright**: Browser testing. [Documentation](https://playwright.dev/)
- **Happy DOM**: DOM environment for testing. [Documentation](https://github.com/capricorn86/happy-dom)
- **ESLint**: Linting tool. [Documentation](https://eslint.org/)
- **Prettier**: Code formatting. [Documentation](https://prettier.io/)

---

## Accessing and Running the Application

The project consists of two main parts: `pizza-client` and `pizza-server`. Follow the steps below to set up and run the application:

### Setting Up `pizza-client`

1. Navigate to the `pizza-client` directory:

```bash
cd pizza-client
```

2. Install the dependencies:

```bash
npm install
```

3. Start the development server:

```bash
npm run dev
```

### Setting Up `pizza-server`

1. Navigate to the `pizza-server` directory:

```bash
cd pizza-server
```

2. Install the dependencies:

```bash
npm install
```

3. Start the server:

```bash
npm start
```

---

## Available Scripts

The following scripts are available in the `package.json` file for both `pizza-client` and `pizza-server`:

- `npm run dev`: Starts the development server (client only).
- `npm start`: Starts the server (server only).
- `npm run build`: Generates the production build (client only).
- `npm run test`: Runs the tests.
- `npm run lint`: Runs ESLint.
- `npm run format`: Formats the code with Prettier.

---

## Environment Setup

To set up the project locally:

1. Ensure you have **Node.js** installed.
2. Follow the steps in the **Accessing and Running the Application** section to set up both `pizza-client` and `pizza-server`.

---

## Exemplo de Uso

Veja abaixo algumas capturas de tela e exemplos de como o projeto funciona:

### Home Page

![Home Page](./screenshots/home-page.png)

### Pizza Ordering

![Pizza Ordering](./screenshots/pizza-ordering.png)

### Shopping Cart

![Shopping Cart](./screenshots/shopping-cart.png)

---

Feel free to explore and contribute to the project!
