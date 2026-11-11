# Bookstore Application

A React single-page application for managing a bookstore workflow. The current implementation includes authentication-aware navigation and screens for book listings, book management, categories, users, profile updates and a shopping cart.

## Technology stack

- **UI:** React 18, Material-UI 4
- **Routing:** React Router 6
- **HTTP:** Axios
- **Forms and validation:** Formik, Yup
- **Notifications:** React Toastify
- **Testing:** React Testing Library

## Application areas

- Authentication: login and registration
- Book listing and book create/edit screens
- Category management
- User management and profile updates
- Shopping cart
- Shared authentication and cart context
- Reusable navigation, header and footer components

## Getting started

### Prerequisites

- Node.js and npm
- Access to any backend/API services configured by the application

### Install and run

```bash
npm install
npm start
```

Open [http://localhost:3000](http://localhost:3000).

### Available scripts

| Command | Description |
|---|---|
| `npm start` | Start the development server |
| `npm test` | Run tests in watch mode |
| `npm run build` | Build the app for production |

## Configuration

Review the existing application constants and API configuration before running against a backend. Do not commit credentials, private API keys or production secrets.

## Project structure

```text
src/
├── assets/
├── components/
├── constant/
├── context/
├── pages/
├── utils/
├── App.js
└── index.js
public/
package.json
```

## Development notes

- Routes are defined through React Router.
- Authentication state is shared through context.
- Form validation uses Formik and Yup.
- API requests use Axios.

## Maintainer

[Shyam Katariya](https://github.com/Shyam-Katariya) · [Portfolio](https://mediumturquoise-fox-633667.hostingersite.com/shyam.html)