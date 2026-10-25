# Crypsy — Secure File Vault

Crypsy is a Python-based desktop application designed to protect sensitive files through encryption and security monitoring. It provides a graphical user interface built with Tkinter and supports protecting text, image, audio, and video files using AES-based encryption.

The application also includes authentication, automatic locking, and intrusion monitoring features to help prevent unauthorized access.

##Features

- AES Encryption: Encrypt sensitive files to protect their contents.
- Multi-Format Support: Designed to handle text, image, audio, and video files.
- User Authentication: Restrict access to authorized users.
- Automatic Locking: Lock the application to help prevent unauthorized access.
- Intrusion Detection: Monitor suspicious access attempts.
- Webcam Monitoring: Capture images during configured security events.
- Telegram Alerts: Send security notifications through Telegram when configured.
- Graphical User Interface: Simple desktop interface developed using Python and Tkinter.
- Local File Management: Manage encrypted files on your local system.

## Tech Stack

- **Programming Language:** Python
- **GUI Framework:** Tkinter
- **Encryption:** AES-based encryption
- **Computer Vision:** OpenCV (if used in the implementation)
- **Notifications:** Telegram Bot API
- **Storage:** Local filesystem

## How It Works

1. Launch the Crypsy application.
2. Authenticate to access the application.
3. Select a file that you want to protect.
4. Encrypt the selected file using the application's encryption functionality.
5. Store the encrypted file securely on your local system.
6. Use the authorized decryption functionality when you need to access the original file.
7. Use automatic locking and monitoring features to improve access security.

## Installation and Setup

### Prerequisites

- Python 3.10 or newer recommended.
- pip package manager.
- A webcam if webcam monitoring is enabled.
- Telegram bot credentials if Telegram alerts are enabled.

### Step 1: Clone the Repository

```bash
git clone https://github.com/VivekBrijwasi/Crypsy.git
```

```bash
cd Crypsy
```

Replace the repository URL and directory name if your actual GitHub repository uses a different name.

### Step 2: Create a Virtual Environment

For Windows:

```bash
python -m venv venv
venv\Scripts\activate
```

For macOS/Linux:

```bash
python3 -m venv venv
source venv/bin/activate
```

### Step 3: Install Dependencies

If your repository contains a `requirements.txt` file, run:

```bash
pip install -r requirements.txt
```

If the file does not exist, install the dependencies required by your source code.

### Step 4: Run the Application

Run the main Python file:

```bash
python main.py
```

Replace `main.py` with your actual entry-point filename if it is different.

##Security Considerations

- Use strong authentication credentials.
- Keep encryption keys and passwords secure.
- Back up important files before testing encryption and decryption.
- Never upload passwords, encryption keys, Telegram bot tokens, or private files to GitHub.
- Store sensitive configuration in environment variables or a local configuration file excluded through `.gitignore`.
- Encryption security depends on the implementation, including key management, encryption mode, initialization vectors or nonces, and integrity verification.
- Use webcam monitoring and notifications responsibly and with appropriate consent.

Note: Crypsy is a personal/educational project and has not been represented as an independently audited security product.

## Future Improvements

- Improve encryption key management.
- Add automated tests for encryption and decryption.
- Strengthen authentication and access control.
- Improve error handling and recovery mechanisms.
- Add detailed security event logs.
- Package the application for easier installation.
- Improve the graphical user interface.

##Contributing

Contributions and suggestions are welcome.

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Test your changes.
5. Submit a pull request describing your improvements.

