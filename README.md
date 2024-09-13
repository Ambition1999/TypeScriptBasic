# Todo App

A simple **Todo App** built with **TypeScript**, using **Vite** as the build tool and **Node.js** for the backend. This app helps users manage their daily tasks, allowing them to add, delete, and mark tasks as completed.

## Features

- **Add tasks**: Users can add new tasks to their todo list.
- **Delete tasks**: Tasks can be removed from the list.
- **Mark tasks as complete**: Users can mark tasks as completed, which will update their status.
- **Interactive UI**: A clean and simple user interface for managing tasks.

## Tech Stack

- **TypeScript**: Ensures type safety and cleaner code.
- **Vite**: A fast and modern build tool for the frontend, making development faster.
- **Node.js**: Used for handling the backend logic.
  
## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/todo-app.git
    cd todo-app
    ```

2. Install dependencies:
    ```bash
    npm install
    ```

3. Start the development server:
    ```bash
    npm run dev
    ```

4. Open the app in your browser at `http://localhost:3000`

## Usage

- After starting the app, you can:
  - Add new todos in the input field.
  - Mark todos as complete by clicking the checkbox.
  - Remove todos by clicking the delete button.
  
## Scripts

- `npm run dev`: Start the development server.
- `npm run build`: Build the project for production.
- `npm run preview`: Preview the production build.

## Folder Structure

```bash
.
├── src
│   ├── css
│   │   └── style.css             # Styles for the app
│   ├── model
│   │   ├── FullList.ts           # Model for the full list of todos
│   │   └── ListItem.ts           # Model for individual todo items
│   ├── templates
│   │   ├── ListTemplate.ts       # Template logic for rendering lists
│   │   └── counter.ts            # Simple counter logic (if used)
│   ├── main.ts                   # Entry point for the app
│   └── vite-env.d.ts             # Vite environment configuration
├── .gitignore                    # Files to ignore in version control
├── index.html                    # HTML template for the app
├── package-lock.json             # Lockfile for npm dependencies
├── package.json                  # Project metadata and scripts
├── tsconfig.json                 # TypeScript configuration
├── typescript.svg                # TypeScript logo/image file
└── README.md                     # Project documentation
```

## Contributing

Feel free to open issues or submit pull requests for improvements and suggestions.

## License

This project is licensed under the MIT License.