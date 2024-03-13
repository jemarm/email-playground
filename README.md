---

# Simple Email Sender

This is a simple Python script that demonstrates how to send an email using SMTP (Simple Mail Transfer Protocol) with the `smtplib` library. It also utilizes the `email.message.EmailMessage` class for constructing the email message and the `string.Template` class for templating the HTML content of the email.

## Prerequisites

- Python 3.x installed on your system.
- Access to an SMTP server (e.g., Gmail) and your email credentials.

## Installation

1. Clone this repository to your local machine.
2. Install the required dependencies by running:
    ```
    pip install -r requirements.txt
    ```

## Usage

1. Make sure you have an HTML file named `index.html` in the same directory as the script. This HTML file will be used as the body of the email.
2. Replace `<to email address>`, `<your email address>`, and `<your password>` with the appropriate values.
3. Run the script:
    ```
    python email_sender.py
    ```

## Note

- Ensure that you have allowed less secure apps to access your Gmail account if you are using Gmail as your SMTP server. You can do this by going to your Google Account settings > Security > Less secure app access.
- This script is for demonstration purposes only. It is not recommended to hardcode your email credentials directly into the script for security reasons. Instead, consider using environment variables or a configuration file.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

Feel free to adjust and expand upon this README according to your specific needs and preferences.
