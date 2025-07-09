# Green-API - Test case

## Description
This project is a web application for interacting with the WhatsApp instance API. It provides a simple and convenient interface for performing the following actions:

- **Get instance settings.**
- **Check instance status.**
- **Send text messages** to a specified phone number.
- **Send files via URL** to a specified phone number.

---

## Functionality
### Main functions:
1. **Get instance settings**:
You can request settings by specifying the instance ID and token.
2. **Check instance status**:
Allows you to find out the current state of the instance (for example, whether it is active).
3. **Send text message**:
The ability to send a message by specifying the recipient's phone number and the text of the message.
4. **Send file via URL**:
Send a file to a specified phone number via a link.

---

## Usage

### Prerequisites
1. Make sure you have:
- **API URL** of your WhatsApp instance.
- **Instance ID.**
- **API Token.**

2. Connect the necessary libraries:
- [`intl-tel-input`](https://github.com/jackocnr/intl-tel-input) for working with phone numbers.

---

### Instructions
1. Open the `index.html` file in any modern browser.
2. In the left panel, fill in the fields:
- **API URL**: Your API URL.
- **Instance ID**: Instance ID.
- **Instance API Token**: API Token.
3. To send messages:
- Specify the recipient's phone number.
- Enter the message text.
- Click the **"Send message"** button.
4. To send files:
- Specify the recipient's phone number.
- Paste the link to the file.
- Click the **"Send file via link"** button.

---

## Project structure
- **HTML**: Basic page markup.
- **CSS**: Styles for application design.
- **JavaScript**: Event handlers and functions for working with the API.

---

## Pluggable libraries
- **[`intl-tel-input`](https://cdnjs.com/libraries/intl-tel-input/17.0.8)**: Working with phone numbers.
- **[Fetch API](https://developer.mozilla.org/ru/docs/Web/API/Fetch_API)**: Making HTTP requests.

---