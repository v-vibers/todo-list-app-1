# Todo List App

A modern, responsive todo list application built with React, TypeScript, and Vite.

## Features

- ✅ **Add Todos**: Create new tasks with a simple input field
- ✅ **Mark Complete**: Check off completed tasks
- ✅ **Delete Todos**: Remove unwanted tasks
- ✅ **Filter Tasks**: View all, active, or completed todos
- ✅ **Persistent Storage**: Todos are saved in localStorage
- ✅ **Responsive Design**: Works on desktop and mobile devices
- ✅ **Dark Mode Support**: Automatically adapts to system color scheme
- ✅ **Keyboard Support**: Press Enter to add new todos

## Getting Started

### Prerequisites

- Node.js (version 16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
```bash
git clone <repository-url>
cd todo-list-app-1
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Open your browser and visit `http://localhost:5173`

## Available Scripts

- `npm run dev` - Start development server
- `npm run build` - Build for production
- `npm run preview` - Preview production build
- `npm run lint` - Run ESLint

## Technology Stack

- **React 19** - UI library
- **TypeScript** - Type safety
- **Vite** - Build tool and dev server
- **ESLint** - Code linting
- **CSS3** - Styling with modern features

## Project Structure

```
src/
├── App.tsx          # Main application component
├── App.css          # Application styles
├── main.tsx         # Application entry point
└── index.css        # Global styles
```

## Features in Detail

### Todo Management
- Add new todos by typing and pressing Enter or clicking the Add button
- Mark todos as complete/incomplete by checking the checkbox
- Delete individual todos with the × button
- Clear all completed todos at once

### Filtering
- **All**: Shows all todos
- **Active**: Shows only incomplete todos  
- **Completed**: Shows only completed todos

### Data Persistence
All todos are automatically saved to your browser's localStorage, so your data persists between sessions.

## Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Run linting: `npm run lint`
5. Build the project: `npm run build`
6. Submit a pull request
