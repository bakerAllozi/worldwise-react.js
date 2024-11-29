### Worldwise-React.js

**Project Description:**  
A React application that utilizes **React Router**, **useReducer**, and **Context API** to create a centralized state management system with dynamic page navigation.

---

### **Features:**
- **Dynamic Navigation:** Powered by React Router to manage routes and pages.
- **Advanced State Management:** Handled by useReducer for organizing complex state logic.
- **Seamless Data Sharing:** Using Context API to propagate state across components.

---

### **Technologies Used:**
1. **React.js:** Library for building user interfaces.
2. **React Router:** For navigation between pages.
3. **useReducer:** To manage complex state logic.
4. **Context API:** For sharing state between components.

---

### **Installation and Usage:**
1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-repo/worldwise-react.js.git
   ```
2. **Navigate to the project directory:**
   ```bash
   cd worldwise-react.js
   ```
3. **Install dependencies:**
   ```bash
   npm install
   ```
4. **Run the application:**
   ```bash
   npm start
   ```

---

### **Project Structure:**
```
src/
│
├── components/   // UI components
├── context/      // Context API files
├── reducers/     // useReducer files
├── pages/        // Application pages
├── App.js        // Main application entry point
└── index.js      // Root file
```

---

### **How It Works:**
1. **React Router:**  
   - Routes are configured in `App.js` using `BrowserRouter` and `Route`.
2. **useReducer:**  
   - Centralized state (e.g., user data) is stored in `reducer.js`.
   - Actions contain logic for updating the state.
3. **Context API:**  
   - `createContext` is used to share the state managed by `useReducer`.

---

### **Contribution:**
- Open pull requests with a clear description.
- Test all features thoroughly before submitting.

---

### **License:**  
This project is licensed under the **MIT License**.  
