# 📂 CSV to JSON Converter

![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
![TailwindCSS](https://img.shields.io/badge/tailwindcss-%2338B2AC.svg?style=for-the-badge&logo=tailwind-css&logoColor=white)
![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=F7DF1E)
![Netlify](https://img.shields.io/badge/netlify-%2300C7B7.svg?style=for-the-badge&logo=netlify&logoColor=white)

## 🔗 **Live Demo:** [csv-to-jsonconv.netlify.app](https://csv-to-jsonconv.netlify.app/)

A modern, lightweight, and responsive web-based tool designed to convert CSV (Comma Separated Values) data into formatted JSON (JavaScript Object Notation). Built with **Vanilla JavaScript** and **Tailwind CSS**.

## 🚀 Features

* **Multiple Delimiters:** Support for standard delimiters (Comma `,`, Semicolon `;`, Tab `\t`) and user-defined custom delimiters.
* **JSON Formatting:** Choose your output style:
    * 4 Spaces (Standard Pretty Print)
    * 2 Spaces (Compact Pretty Print)
    * Minified (Compact for production)
* **Smart Parsing:** Handles quoted values and cleans up extra whitespace automatically.
* **One-Click Actions:**
    * Convert CSV to JSON
    * Copy output to clipboard
    * Clear all inputs
* **Modern UI:** Fully responsive Dark Mode interface designed with Inter font and Tailwind CSS.
* **User Feedback:** Toast notifications for success, errors, and copy actions.

## 🛠️ Tech Stack

* **Frontend Structure:** HTML5
* **Styling:** Tailwind CSS (via CDN)
* **Logic:** Vanilla JavaScript (No external frameworks required)
* **Font:** Inter (Google Fonts)

## 📖 How to Run Locally

Since this project uses Tailwind via CDN and vanilla JavaScript, no build step or package manager (npm/yarn) is required.

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/your-username/csv-to-json-converter.git](https://github.com/your-username/csv-to-json-converter.git)
    ```
2.  **Navigate to the folder:**
    ```bash
    cd csv-to-json-converter
    ```
3.  **Open the file:**
    Simply open `index.html` in your preferred web browser.

## 📝 Usage Guide

1.  **Input Data:** Paste your CSV data into the "CSV Input" text area. Ensure the first row contains your headers.
2.  **Configure:**
    * Select the delimiter used in your CSV (or type a custom one).
    * Select your desired indentation for the JSON output.
3.  **Convert:** Click the **"Convert to JSON"** button.
4.  **Result:** The JSON will appear in the right-hand panel. You can copy it instantly using the **"Copy JSON"** button.

## 🤝 Contributing

Contributions, issues, and feature requests are welcome!

1.  Fork the Project
2.  Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3.  Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4.  Push to the Branch (`git push origin feature/AmazingFeature`)
5.  Open a Pull Request

## 📄 License

Distributed under the MIT License. See `LICENSE` for more information.
