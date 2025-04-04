# PadreGino's Delivery

PadreGino's Delivery is a sample project for an online pizza ordering system, developed as part of the course **"The Complete Intro to React v9"** by Brian Holt for Frontend Masters.

### Project Demonstration

![Project Demonstration](/screenshots/Padre%20GIno's.gif)

---

## Prerequisites

Before starting, make sure you have the following versions installed:

- **Node.js**: Minimum version 16.x
- **npm**: Minimum version 8.x

---

## `.env` Configuration

To set up the development environment, create a `.env.development` file in the root of the `pizza-client` directory with the following content:

```env
VITE_API_URL=http://localhost:3000
```

Replace `http://localhost:3000` with the API URL for the development environment, if necessary.

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

## Usage Example

Below are some screenshots and examples of how the project works:

### Home Page

![Home Page](./screenshots/home-page.png)

### Pizza Ordering

![Pizza Ordering](./screenshots/pizza-ordering.png)

### Shopping Cart

![Shopping Cart](./screenshots/shopping-cart.png)

---

Feel free to explore and contribute to the project!
