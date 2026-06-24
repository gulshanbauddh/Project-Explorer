# 🚀 Advanced GitHub Repo Explorer

A beautiful, responsive, and fast web-based file explorer for GitHub repositories. It looks and feels like a real IDE (like VS Code) right in your browser! I created this to easily showcase my repository files directly on a web page.

## ✨ Features

* 📁 **File Explorer:** Browse folders and files easily with a back button and breadcrumb navigation.
* 🔍 **Smart Search:** Instantly search for any file in the whole repository.
* 🎨 **VS Code Style Code Viewer:** Beautiful syntax highlighting for JS, PHP, Python, Java, SQL, HTML, etc., using Prism.js.
* 👁️ **Markdown Preview:** View `.md` files exactly like they look on GitHub.
* ▶️ **Run HTML Code:** Run HTML files directly in a new browser tab.
* 📋 **Copy Code:** One-click button to copy code perfectly.
* ⚡ **Lightning Fast:** Uses `sessionStorage` caching for zero delay when reopening folders.
* 🔒 **Secure:** Uses a PHP backend proxy to hide the GitHub API token safely.
* 🌙 **Dark/Light Mode:** Built-in Bootstrap 5 dark mode toggle.

## 🛠️ Technologies Used

* **Frontend:** HTML5, JavaScript (Fetch API), Bootstrap 5, Bootstrap Icons.
* **Libraries:** Prism.js (Syntax Highlighting) & marked.js (Markdown Rendering).
* **Backend (Security):** PHP (cURL).
* **API:** GitHub REST API & Git Trees API.

## 🚀 How to Setup

1. Clone or download this repository.
2. Create a **GitHub Personal Access Token** (No scopes needed).
3. Open the `github_api.php` file and paste your token inside `$token = 'YOUR_TOKEN_HERE';`.
4. Upload the files to your PHP server (like XAMPP for local testing, or any live hosting).
5. Open `index.html` in your browser and enjoy!

## 👨‍💻 Created By
**Gulshan Bauddh**
