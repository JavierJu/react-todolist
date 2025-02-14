# React Todo List

## Overview
This is a simple yet functional **Todo List** application built using **React (Vite)**. The project was created as part of an Udemy Web Bootcamp course. It allows users to create, manage, and delete multiple to-do lists efficiently.

## Features
- Create multiple to-do lists.
- Add, edit, and delete tasks within each list.
- Persistent state management using React Context API.
- Responsive and user-friendly UI.

## Tech Stack
- **Frontend:** React (Vite), JSX
- **State Management:** React Context API
- **Styling:** CSS
- **Development Tools:** ESLint, Vite

## Folder Structure
```
react-todolist                                           
├─ dist                                                 
│  ├─ assets                                            
│  ├─ index.html                                       
│  └─ vite.svg                                         
├─ public                                               
│  └─ favicon.png                                       
├─ src                                                  
│  ├─ components                                        
│  │  ├─ AllTodoLists.jsx                               
│  │  ├─ App.jsx                                       
│  │  ├─ AppHeader.jsx                                 
│  │  ├─ CurrentTodoList.jsx                           
│  │  └─ NewListDialog.jsx                             
│  ├─ hooks                                            
│  │  ├─ useTodoList.js                                
│  │  └─ useTodoLists.js                               
│  ├─ providers                                        
│  │  └─ AppState.jsx                                  
│  ├─ main.jsx                                         
│  └─ utils.js                                         
├─ eslint.config.js                                     
├─ index.html                                          
├─ package-lock.json                                   
├─ package.json                                        
├─ README.md                                           
└─ vite.config.js                                      
```

## Installation & Usage
### 1. Clone the Repository
```sh
git clone https://github.com/your-username/react-todolist.git
cd react-todolist
```

### 2. Install Dependencies
```sh
npm install
```

### 3. Run the Development Server
```sh
npm run dev
```

### 4. Build for Production
```sh
npm run build
```

## License
This project is licensed under the MIT License.

## Author
Created as part of an Udemy Web Bootcamp project.
