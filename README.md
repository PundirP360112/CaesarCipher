# Caesar Cipher  🔐

A lightweight, web-based implementation of the classic Caesar Cipher algorithm using **Python** and **Flask**. This tool allows users to encrypt, decrypt, and brute-force crack messages through a clean graphical user interface.

## 🚀 Features

* **Encryption & Decryption:** Shift text by a custom key (supports both letters and numbers).
* **Brute Force Mode:** Instantly generate all 26 possible shifts to "crack" a message without the key.
* **Smart Parsing:** Preserves special characters and handles case sensitivity automatically.
* **Dark Mode UI:** A responsive, dark-themed interface built with embedded HTML/CSS.
* **Auto-Launch:** Automatically opens the web browser when the script runs.

## 🛠️ Tech Stack

* **Backend:** Python 3, Flask
* **Frontend:** HTML5, CSS3 (Embedded)

## 📦 Installation & Usage

1.  **Prerequisites**
    Make sure you have Python installed. You will also need the Flask library.
    ```bash
    pip install flask
    ```

2.  **Run the Application**
    Save the code as `app.py` (or your preferred filename) and run it:
    ```bash
    python app.py
    ```

3.  **Access the Tool**
    The script will automatically attempt to open your default web browser to:
    `http://127.0.0.1:5000`

## 📂 Project Structure

This project utilizes a **single-file architecture**. To keep deployment simple, the HTML template and CSS styles are rendered directly from the Python string, eliminating the need for separate `templates` or `static` folders.

## 📜 License

This project is open-source and available for educational purposes.
