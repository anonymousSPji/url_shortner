# OTP Verification System

This Python script implements an OTP (One-Time Password) verification system using SMTP (Simple Mail Transfer Protocol). The system generates a 6-digit OTP and sends it to the user's email address for verification.

## Introduction

The OTP Verification System provides a secure method for authenticating users by sending a one-time password to their email address. It utilizes Python's `smtplib` library for sending emails and `random` module for generating OTPs.

## Features

- Generates a random 6-digit OTP.
- Sends OTP to the user's email address for verification.
- Validates the OTP entered by the user.
- Supports resending OTP in case of invalid input or request.

## Requirements

- Python 3.x
- An active internet connection
- A Gmail account (for sending emails)

## Setup

1. Clone the repository:

    ```
    git clone https://github.com/anonymousSPji/Otp_Verification.git
    ```

2. Make sure you have Python installed on your system.

3. Install the required libraries using pip:

    ```
    pip install secure-smtplib
    ```

4. Update the following variables in the script with your Gmail credentials:

    - `password`: Your Gmail account password.
    - `server.login("your_email@gmail.com", password)`: Replace `"your_email@gmail.com"` with your Gmail address.

## Usage

1. Run the script `otp_verification.py`.
2. Enter your name and email address when prompted.
3. Check your email for the OTP.
4. Enter the OTP received to verify your identity.

## Contributing

Contributions are welcome! If you find any issues or want to enhance the system, feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
