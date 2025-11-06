## 🧑‍💻 User Login System (Python)

A simple and interactive **User Login System** built using Python.
It allows users to **log in** with predefined usernames and passwords — and keeps asking until a correct login is made.

---

### 📜 Features

* 🔐 Secure username and password check
* 🔁 Uses a **while loop** to allow multiple login attempts
* ⚠️ Displays errors for incorrect usernames or passwords
* ✅ Grants access once the correct credentials are entered

---

### 🧩 Code Example

```python
users = {
    "Zain": "22532",
    "Hammad": "22542",
    "Muneeb": "38924",
    "Ahmed": "04734"
}

while True:
    username = input("Enter username: ")
    if username in users:
        password = input("Enter password: ")
        if password == users[username]:
            print("Login Successful!", username)
            break
        else:
            print("Incorrect password! Try again.\n")
    
    else:
        print("Username not found.")
print("🔓 Access Granted!")
```

---

### ⚙️ How to Run

1. Make sure you have **Python 3** installed on your system.
2. Save the code in a file named `login_system.py`.
3. Open your terminal or command prompt and run:

   ```bash
   python login_system.py
   ```
4. Enter your username and password to log in.

https://github.com/zain1522532-svg
zain1522532@gmail.com

### 🧠 Example Output

```
Enter username: Zain
Enter password: 22532
Login Successful! Zain
🔓 Access Granted!
```

---

### 🚀 Future Improvements

* Add a feature for **new user registration**.
* Limit the number of **login attempts**.
* Store user data in a **file or database**.

---

### 📄 License

This project is **open-source** and available under the [MIT License](LICENSE).

---

Would you like me to make it include a **section for unknown users (account creation)** version instead of only predefined users?
