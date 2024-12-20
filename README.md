# Project-7: Password Manager

## Description
This project is a **Password Manager** built using Python's `tkinter` library. It allows users to securely store, search, and generate passwords for various websites. The application saves passwords in a local JSON file and provides an easy-to-use graphical interface to manage them.

## Prerequisites
Before running this project, ensure the following modules are installed:

- **Tkinter**: Typically included by default in most Python installations.
- **JSON**: A standard Python library, included by default.
- **Random**: A standard Python library, included by default.
- **String**: A standard Python library, included by default.

## How to Run
1. Open a terminal or command prompt in the project directory.
2. Run the Python script:

    ```bash
    python project-7.py
    ```

3. The Password Manager GUI window will open. You can:
   - **Add Passwords**: Enter the website, username, and password, and click "Add Password" to store them.
   - **Search Passwords**: Enter the website name and click "Search Password" to view saved credentials.
   - **Generate Passwords**: Click "Generate Password" to create a random password, which will be automatically inserted into the password field.

## Features
- **Password Generation**: Generates a secure random password containing letters, digits, and symbols.
- **Password Storage**: Saves passwords securely in a local JSON file.
- **Password Search**: Allows searching for saved passwords by website name.
- **User-friendly Interface**: Simple and intuitive interface with clear labels and buttons.

## Limitations
- The password file is stored as a plain JSON file, which can be accessed by anyone with access to the file system.
- The password manager does not support encryption for stored passwords (consider adding encryption for more security).
- No authentication required to access or modify passwords.

## Future Enhancements
- Implement password encryption for added security.
- Add user authentication to protect the password manager with a master password.
- Improve the GUI with better styling and additional features like password strength checking.
- Provide the option to export passwords to a CSV or encrypted file.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute it as you wish.

---

If you encounter any issues or have suggestions for improvement, please open an issue or submit a pull request on the [project repository](https://github.com/YourUsername/Project-7).
