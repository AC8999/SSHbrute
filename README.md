**SSH Brute** is a lightweight, command-line brute force tool designed for testing the security of SSH services against known or common credentials. Written entirely in **Python**, this script efficiently attempts to log in to an SSH server by systematically iterating through combinations of usernames and passwords provided via external lists.

It is intended for **ethical security testing, penetration testing, and auditing purposes** on systems you have explicit permission to test. **DO NOT** use this tool for illegal or unauthorized activities.

---

## 🚀 Key Features

* **Python Native:** Developed in Python for cross-platform compatibility and ease of use.
* **Targeted Brute Force:** Systematically combines every username with every password against a specified SSH host.
* **Clear Output:** Provides immediate feedback upon successful login, displaying the **compromised username and password** combination.
* **Simple Interface:** Runs directly from the command line with minimal required arguments.

---

## 🛠️ Installation & Prerequisites


1.  **Install the required dependencies:**
    ```bash
    pip3 install -r requirements.txt
    ```

---

## 📝 Usage

### Basic Syntax

To run the tool, specify the target host, the username list, and the password list:

```bash
python3 SSHBrute.py 10.129.202.135 -p 22 -U <PATH TO USER LIST> -w <PATH TO WORDLIST> 
