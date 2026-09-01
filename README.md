# 🔐 Random Password Generator

A simple and lightweight **Random Password Generator** built using Python.

This program allows users to generate a random password based on their preferred password length. The generated password can contain a combination of:

* 🔤 Lowercase letters
* 🔠 Uppercase letters
* 🔢 Numbers
* 🔣 Special symbols

The program also includes a simple terminal loading animation for a more interactive experience.

---

## ✨ Features

* Generate random passwords instantly
* User can choose the password length
* Includes uppercase and lowercase letters
* Includes numbers
* Includes special characters
* Terminal loading animation
* Simple and beginner-friendly Python project

---

## 📸 Preview

```text
Selamat Datang Ke Random Password Generator By aminzikryy

Nak Berapa Panjang Password nya? 12

Loading:
[■■■■■■■■■■]

Here is your password :

A8@kP!2mQ#xL
```

---

## 🛠️ Requirements

Make sure you have **Python 3** installed on your computer.

This project only uses Python's built-in libraries:

```text
random
string
sys
time
itertools
shutil
threading
```

Therefore, **no additional package installation is required**.

---

## 🚀 Installation

### 1. Clone this repository

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### 2. Open the project folder

```bash
cd YOUR-REPOSITORY
```

### 3. Run the program

```bash
python main.py
```

> Make sure to replace `main.py` with your actual Python filename if it is different.

---

## 💻 Usage

When you run the program, you will be asked:

```text
Nak Berapa Panjang Password nya?
```

Enter the desired password length.

Example:

```text
Nak Berapa Panjang Password nya? 16
```

The program will generate a random password automatically.

---

## 🧠 How It Works

The program combines different types of characters:

```python
lower = "abcdefghijklmnopqrstuvwxyz"
upper = "ABCDEFGHIJKLMNOPQRSTUVWXYZ"
num = "0123456789"
symbols = "!@#$%&?/"
```

All characters are combined:

```python
all = lower + upper + num + symbols
```

Then, Python randomly selects characters based on the password length chosen by the user.

Finally, the characters are combined into a password:

```python
password = "".join(temp)
```

---

## 📂 Project Structure

```text
Random-Password-Generator/
│
├── main.py
└── README.md
```

---

## ⚠️ Note

The password is generated randomly every time the program runs.

Please note that this is a simple educational project and is intended for learning Python programming, especially:

* Variables
* User input
* Python libraries
* Random functions
* String manipulation
* Terminal output
* Basic animations

---

## 👨‍💻 Author

**aminzikryy**

Python Beginner Project 🚀

---

## ⭐ Support

If you like this project, consider giving it a **⭐ Star** on GitHub!

Happy Coding! 💻🔥
