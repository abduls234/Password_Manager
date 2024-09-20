# Simple Password Manager

This is a simple password manager program built in Python that allows users to securely store and manage their passwords. It uses the `cryptography` library for encryption, ensuring that sensitive information is protected.

## Features

- **Add Passwords**: Easily save account names and passwords.
- **View Passwords**: Retrieve and view stored passwords securely.
- **Encryption**: Utilizes Fernet symmetric encryption to protect passwords.

## Requirements

- Python 3.x
- `cryptography` library

To install the required library, run:

```bash
pip install cryptography
```
## How It Works
The program stores passwords in a text file and encrypts them using a generated key. Users can add new passwords or view existing ones through a command-line interface. The passwords are stored in the format ```account_name|encrypted_password```, making them easy to retrieve while keeping them secure.

**Example Usage**
- Add a New Password: Choose the "add" option and input the account name and password.
- View Existing Passwords: Choose the "view" option to display stored passwords.

*Important Note*
**Ensure that the key.key file is kept secure, as it is essential for decrypting the stored passwords.**

## License
This project is licensed under the MIT License. Feel free to modify and use it as needed!
