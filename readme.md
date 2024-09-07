# Password Manager

This is a simple Password Manager application built using Python and Tkinter. It allows you to generate strong passwords, save them locally in JSON format, and retrieve them when needed.

## Features:

- Generate random, secure passwords with letters, numbers, and symbols.
- Save website, email, and password information in a local `.json` file.
- Retrieve stored credentials based on the website.
- Easily copy passwords to your clipboard.
- Interactive UI with Tkinter.

## Requirements

Before running the application, make sure you have the following installed:

- Python 3.x
- Tkinter (Usually included with Python)
- `pyperclip` for clipboard support
  - Install via pip: `pip install pyperclip`

## Usage Instructions

1. Clone or download the project files.
2. Save your logo image file as `logo.png` in the same directory as the script.
3. Run the Python script:

   ```bash
   python password_manager.py
   ```

4. Use the following buttons:
   - **Generate Password**: Creates a new password and copies it to your clipboard.
   - **Add**: Saves the website, email, and password to a JSON file based on the email.
   - **Search**: Finds and displays the password for a particular website.

## How it Works

- When a new password is generated, it's automatically copied to your clipboard using `pyperclip`.
- Data is saved in a JSON file named after your email's prefix (e.g., if your email is `example@gmail.com`, the file will be `example.json`).
- If the JSON file doesn't exist, a new one is created.
- You can search for saved passwords by entering the website name.

## Important Notes

- Ensure that `logo.png` is available in your directory, or remove the logo code from the UI setup section if not needed.
- Data is saved locally, so keep the JSON files secure to avoid unauthorized access.

## License

This project is open-source and free to use
