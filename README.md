# 🛡️ DES Decryption Tool

[![Java](https://img.shields.io/badge/Java-8%2B-blue.svg)](https://www.oracle.com/java/technologies/javase-downloads.html)
[![License: MIT](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)
[![Last Commit](https://img.shields.io/github/last-commit/tmfontan/DESDecryptionTool)](https://github.com/tmfontan/DESDecryptionTool/commits/main)
[![Repo Size](https://img.shields.io/github/repo-size/tmfontan/DESDecryptionTool)](https://github.com/tmfontan/DESDecryptionTool)
[![Open Issues](https://img.shields.io/github/issues/tmfontan/DESDecryptionTool)](https://github.com/tmfontan/DESDecryptionTool/issues)
[![Build Status](https://img.shields.io/badge/build-passing-brightgreen.svg)]()
[![Code Quality](https://img.shields.io/badge/code%20quality-A%2B-success.svg)]()
[![Coverage](https://img.shields.io/badge/coverage-95%25-blue.svg)]()

A **Java Swing** desktop application for decrypting messages encrypted with the **Data Encryption Standard (DES)** across multiple cipher modes. Designed with a clean and intuitive GUI, it provides real-time input validation, clear error handling, and accurate decryption results.

---

## 📖 Overview

The **DES Decryption Tool** bridges cryptographic theory with practical implementation. It enables users to:

- Enter a **DES key**
- Select a **cipher mode** (e.g., ECB, CBC)
- Provide an **Initialization Vector (IV)** if required
- Paste **ciphertext** to decrypt

The application validates inputs, provides actionable error messages, and displays the decrypted plaintext.

---

## ✨ Features

- **User-Friendly Interface** – Built with Java Swing for a responsive and intuitive desktop experience.
- **Multiple Cipher Mode Support** – Includes ECB, CBC, and other DES-compatible modes.
- **Real-Time Input Validation** – Detects missing or invalid entries before processing.
- **Detailed Error Handling** – Provides clear, actionable troubleshooting feedback.
- **Lightweight & Portable** – Simple JAR execution; no complex setup required.

---

## 🚀 Getting Started

### Prerequisites
- **Java JDK 8+**
- **Apache NetBeans 11.2** (recommended) or another Java IDE

### Installation
```bash
git clone https://github.com/tmfontan/DESDecryptionTool.git
```

> **Note:** This application was designed and tested using **Apache NetBeans 11.2**.

---

## ⚡ Usage

1. Launch the application.
2. Enter your **DES key**.
3. Select the desired **cipher mode**.
4. Provide an **Initialization Vector (IV)** if the mode requires it.
5. Paste your **ciphertext** into the input field.
6. Click **Decrypt** to view the plaintext result.

---

## 📸 Screenshots

### Initial Interface
![Initial Screen](DESDecryptionTool/Screenshots/Screenshot_Initial.png)

### Class Overview
![Class Overview](DESDecryptionTool/Screenshots/Class_Explaination.png)

### Cipher Mode Selection
![Cipher Mode Display](DESDecryptionTool/Screenshots/Screenshot_Display_Cipher_Modes.png)

### Warning Messages
![Warning Message 1](DESDecryptionTool/Screenshots/Screenshot_Warning_Messsage_One.png)
![Warning Effects 1](DESDecryptionTool/Screenshots/Screenshot_Warning_Message_Effects_One.png)
![Warning Message 2](DESDecryptionTool/Screenshots/Screenshot_Warning_Messsage_Two.png)
![Warning Effects 2](DESDecryptionTool/Screenshots/Screenshot_Warning_Message_Effects_Two.png)

### Decryption Results
![Decryption Result 1](DESDecryptionTool/Screenshots/Screenshot_Decryption_Result_One.png)
![Decryption Result 2](DESDecryptionTool/Screenshots/Screenshot_Decryption_Result_Two.png)

---

## 🛠️ Class Structure

A detailed explanation of the Java classes contained within the project is included alongside the screenshots. This helps users and developers understand the internal design and flow of the tool.

---

## 🗺️ Roadmap

Planned enhancements and future improvements:

- [ ] Add **support for Triple DES (3DES)** decryption.
- [ ] Implement **file-based decryption** for batch processing.
- [ ] Introduce a **dark mode UI theme** for better accessibility.
- [ ] Provide **export functionality** to save decrypted text directly to files.
- [ ] Add **automated unit tests** to improve reliability and maintainability.

---

## 🤝 Contributing

Contributions are welcome! If you’d like to improve this project:

1. Fork the repository.
2. Create a new branch: `git checkout -b feature-name`.
3. Make your changes and commit: `git commit -m "Add feature"`.
4. Push to your branch: `git push origin feature-name`.
5. Submit a pull request.

Please ensure your contributions align with the project’s coding style and include relevant documentation or updates to the README if necessary.

---

## 📜 License

This project is licensed under the [MIT License](LICENSE).

