# Grocery Bud

This is a simple JavaScript project that allows you to manage a grocery list in the browser. It includes features to add, edit, delete, and clear items, with data persistence using the browser's local storage.

## 🛠️ Features

- Add grocery items
- Edit existing items
- Delete individual items
- Clear all items at once
- Data is saved in local storage so the list persists between page reloads

## 📁 Project Structure

```
index.html   - HTML structure and form
styles.css   - Styles for layout and appearance
app.js       - JavaScript logic for handling UI and storage
README.md    - Project documentation (this file)
```

## 🚀 Getting Started

1. **Clone the repository** (or copy files to your local machine):
   ```bash
   git clone https://github.com/your-username/Grocery-Bud.git
   cd Grocery-Bud
   ```

2. **Open the project in your browser**:
   - Double-click `index.html` or right-click and choose "Open with Live Server" (if using VS Code with the Live Server extension).
   - The app will appear, and you can start adding groceries.

3. **Run a simple server (optional)**:
   If you want to serve the files via a local server, you can use Node's `serve` package:
   ```bash
   npx serve .
   ```
   Then open the provided URL in your browser.

## 💾 Using Git and GitHub

1. **Initialize the repository** (if not already):
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```

2. **Push to GitHub**:
   ```bash
   git remote add origin https://github.com/your-username/Grocery-Bud.git
   git branch -M main
   git pull origin main --allow-unrelated-histories
   git push -u origin main
   ```
   - If the remote already has commits, pull first to merge changes before pushing.

## 🧰 Notes

- This project is meant for learning JavaScript DOM manipulation and local storage.
- No build tools or dependencies are required.

## 📄 License

This project is open source and free to use.
