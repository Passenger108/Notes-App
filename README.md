# 📝 Notes App

A simple **Notes Application** built using **JavaScript, HTML, and CSS**. This app allows users to create, edit, delete, and store notes using **local storage**.

---

## 📸 Screenshots
| Notes App UI | Editing a Note |
|-------------|---------------|
| ![1. ](screenshots/Screenshot%202025-03-08%20at%2011.31.12 PM.png) | ![2. ](screenshots/Screenshot%202025-03-08%20at%2011.32.16 PM.png) | ![3. ](screenshots/Screenshot%202025-03-08%20at%2011.32.35 PM.png) |

*(Replace with actual image paths)*

---

## 🌟 Features
✔ **Create Notes** - Add new notes instantly.  
✔ **Edit Notes** - Update title and content dynamically.  
✔ **Delete Notes** - Remove notes with a double-click confirmation.  
✔ **Persistent Storage** - Notes are saved in **Local Storage**.  
✔ **Intuitive UI** - Sidebar for quick navigation and real-time updates.  
✔ **Separation of Concerns** - Modular JavaScript structure.  

---

## 📐 Design Pattern & Code Structure
This project follows the **Separation of Concerns** principle by dividing logic into three distinct modules:

### **1️⃣ NotesAPI.js** (Data Management) 📂
- Handles **CRUD operations** on notes.
- Uses **Local Storage** for persistent data.
- Provides methods: `getAllNotes()`, `saveNote()`, and `deleteNote()`.

### **2️⃣ NotesView.js** (UI Management) 🎨
- Responsible for **rendering** notes.
- Updates the **sidebar, preview panel, and active note styles**.
- Attaches event listeners for user interactions.

### **3️⃣ App.js** (Controller) 🏗️
- Bridges **NotesAPI** and **NotesView**.
- Manages **user actions** (select, add, edit, delete).
- Ensures **UI updates sync with local storage**.

### **Main Entry Point: main.js**
- Initializes the app using:
  ```js
  import App from "./App.js";
  const root = document.getElementById("app");
  const app = new App(root);
  ```

---

## 🎨 UI & Styling
- **CSS Flexbox** is used for responsive layout.
- **Hover & Click Effects** enhance UX.
- **Minimalist Design** ensures clarity.

---

## 🛠 Technologies Used
- **HTML5** - Structure
- **CSS3** - Styling
- **Vanilla JavaScript (ES6+)** - Logic & Data Handling
- **Local Storage** - Persistent Data

---

## 🚀 How to Run the App
1️⃣ **Clone the repository**:
   ```sh
   git clone https://github.com/Passenger108/Notes-App.git
   ```
2️⃣ **Navigate to the project folder**:
   ```sh
   cd Notes-App
   ```
3️⃣ **Open `index.html` in a browser**:
   ```sh
   start index.html  # Windows
   open index.html    # Mac
   ```

---

## 🔮 Future Enhancements
✨ **Drag & Drop Note Reordering**  
✨ **Cloud Syncing** (Firebase/Backend)  
✨ **Rich Text Formatting** (Bold, Italics, Lists)  

---

## 🤝 Contributing
1. **Fork the repo** 🍴
2. **Create a new branch**: `git checkout -b feature-name`
3. **Commit your changes**: `git commit -m "Added new feature"`
4. **Push and create a Pull Request** 🚀

---

🔥 **Enjoy using the Notes App? Don't forget to ⭐ the repo!** ⭐

https://passenger108.github.io/Notes-App/