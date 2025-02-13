# UltraTool

UltraTool is a Python program designed to enhance security measures for login and authentication processes on Windows systems. It provides functionalities such as password hashing, password verification, data encryption, and workstation locking to improve security.

## Features

- **Password Hashing**: Securely hashes passwords for storage using SHA-256.
- **Password Verification**: Verifies stored passwords against input using hashing.
- **Data Encryption**: Encrypts sensitive data using Fernet symmetric encryption.
- **Workstation Locking**: Locks the Windows workstation for enhanced physical security.

## Requirements

- Python 3.x
- `cryptography` package

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/yourusername/UltraTool.git
    ```

2. Navigate to the project directory:
    ```bash
    cd UltraTool
    ```

3. Install the required packages:
    ```bash
    pip install cryptography
    ```

## Usage

1. Run the program:
    ```bash
    python ultratool.py
    ```

2. Follow the on-screen instructions to enter your password and simulate a secure login process.

## Security

- Passwords are stored as SHA-256 hashes.
- Sensitive data is encrypted using Fernet encryption for confidentiality.
- The application locks the workstation to prevent unauthorized physical access.

## Note

This tool is a demonstration of enhanced security measures and should be tested and reviewed in a controlled environment before deployment.

## Contributing

Contributions are welcome! Please open an issue or submit a pull request for any improvements or features you would like to add.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.