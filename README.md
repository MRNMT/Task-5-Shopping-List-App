# Shopping List App

A modern, full-stack shopping list management application built with React, TypeScript, Vite, and JSON Server. This app allows users to create, manage, and share shopping lists with a clean, responsive interface.

## 🚀 Features

- **User Authentication**: Secure user registration and login with password encryption
- **Shopping List Management**: Create, edit, and delete shopping lists
- **Item Organization**: Add items with categories, quantities, and completion status
- **List Sharing**: Share shopping lists with other registered users
- **Responsive Design**: Optimized for desktop and mobile devices
- **Real-time Collaboration**: Instant updates for shared lists
- **Data Persistence**: JSON Server backend for data storage
- **Modern UI**: Built with shadcn/ui components and Tailwind CSS

## 🛠️ Tech Stack

### Frontend
- **React 18** - Component-based UI library
- **TypeScript** - Type-safe JavaScript
- **Vite** - Fast build tool and dev server
- **Tailwind CSS** - Utility-first CSS framework
- **shadcn/ui** - Accessible UI component library
- **React Router DOM** - Client-side routing
- **Redux Toolkit** - State management
- **React Hook Form** - Form handling with validation
- **Zod** - Schema validation

### Backend
- **JSON Server** - REST API simulation
- **bcryptjs** - Password hashing

## 📁 Project Structure

```
Task-5-Shopping-List-App/
├── db.json                    # JSON Server database
├── index.html                 # Main HTML file
├── src/
│   ├── components/
│   │   ├── auth/             # Authentication components
│   │   ├── layout/           # Layout components (Header, MainLayout)
│   │   ├── shopping/         # Shopping list components
│   │   └── ui/               # Reusable UI components
│   ├── contexts/             # React contexts (AuthContext)
│   ├── hooks/                # Custom hooks
│   ├── lib/                  # Utility libraries
│   ├── pages/                # Page components (Home, Login, etc.)
│   ├── services/             # API service functions
│   ├── store/                # Redux store configuration
│   │   ├── slices/           # Redux slices (auth, shoppingList)
│   │   └── hooks.ts          # Typed Redux hooks
│   ├── utils/                # Utility functions
│   ├── App.tsx               # Main app component
│   ├── main.tsx              # App entry point
│   └── index.css             # Global styles
├── package.json
├── vite.config.ts
├── tailwind.config.ts
└── README.md
```

## 🚀 Getting Started

### Prerequisites
- Node.js (version 16 or higher)
- npm package manager

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Task-5-Shopping-List-App
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm run dev
   ```
   The app will be available at `http://localhost:8080`

4. **(Optional) Start JSON Server for backend simulation**
   ```bash
   npm run server
   ```
   This starts the JSON Server on `http://localhost:3001`

## 📖 Usage

### Getting Started
1. **Register**: Create a new account with your details
2. **Login**: Sign in with your credentials
3. **Create Lists**: Start by creating your first shopping list
4. **Add Items**: Add items with categories and quantities
5. **Share Lists**: Share your lists with other users via email
6. **Collaborate**: Work together on shared shopping lists

### Key Features
- **List Management**: Create multiple shopping lists for different purposes
- **Item Categories**: Organize items by type (groceries, dairy, household, etc.)
- **Completion Tracking**: Mark items as completed
- **User Collaboration**: Share lists and collaborate in real-time
- **Responsive Interface**: Use on any device with a consistent experience

## 🔧 Available Scripts

- `npm run dev` - Start the Vite development server
- `npm run build` - Build the app for production
- `npm run build:dev` - Build for development
- `npm run preview` - Preview the production build
- `npm run server` - Start JSON Server backend
- `npm run lint` - Run ESLint
- `npm run test` - Run tests with Vitest
- `npm run test:watch` - Run tests in watch mode

## 🔒 Security & Authentication

- **Password Encryption**: User passwords are hashed using bcryptjs
- **Protected Routes**: Authentication required for accessing app features
- **User Isolation**: Users can only access their own and shared lists
- **Input Validation**: Form validation prevents invalid data submission

## 🎨 Design & UX

- **Modern Interface**: Clean design with shadcn/ui components
- **Responsive Layout**: Adapts to different screen sizes
- **Accessibility**: WCAG compliant components
- **Toast Notifications**: User feedback for actions
- **Loading States**: Visual feedback during operations
- **Dark/Light Theme**: Theme support with Tailwind CSS

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/new-feature`)
3. Make your changes
4. Commit your changes (`git commit -m 'Add new feature'`)
5. Push to the branch (`git push origin feature/new-feature`)
6. Open a Pull Request

## 📝 License

This project is licensed under the MIT License.

## 🙏 Acknowledgments

- [shadcn/ui](https://ui.shadcn.com/) - UI component library
- [Tailwind CSS](https://tailwindcss.com/) - CSS framework
- [Vite](https://vitejs.dev/) - Build tool
- [React](https://reactjs.org/) - UI library
- [JSON Server](https://github.com/typicode/json-server) - API simulation
