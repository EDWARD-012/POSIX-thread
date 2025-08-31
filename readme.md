readme.md
# Interactive Report on POSIX Threads (pthreads)

This project is an **interactive single-page application (SPA)** that explains POSIX Threads (pthreads) using a sidebar navigation system, interactive diagrams, simulations, and code examples.  
It is built with **HTML, TailwindCSS, JavaScript, and Chart.js**.

## 🌐 Live Demo
- [Live](https://edward-012.github.io/POSIX-thread/)  
 

## 📂 Project Structure
.
├── index.html # Main interactive report

├── README.md # Documentation

├── LICENSE # License for usage

└── .gitignore # Ignored files for Git


markdown
Copy code

## 🚀 Features
- Sidebar-driven navigation (Introduction, Lifecycle, Synchronization, Performance, Examples).
- Thread lifecycle diagram with interactive highlighting.
- Shared counter simulation demonstrating race conditions vs. mutex protection.
- Performance bar chart using Chart.js.
- Copy-to-clipboard C code examples.

## 🛠️ Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/pthreads-report.git
cd pthreads-report
2. Open in browser
Just open index.html in your favorite browser.

3. (Optional) Run a local server
If you want live reload:

bash
Copy code
# Python 3
python -m http.server 8080

Visit http://localhost:8080

