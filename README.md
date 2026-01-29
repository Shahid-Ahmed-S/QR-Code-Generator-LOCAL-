# QR Code Generator – Flask App

This is a simple Flask-based web application that generates a QR code
for any text or URL entered by the user. The generated QR code opens
the correct website even if the protocol (http/https) is not provided.

## Features
- Accepts any input (google.com, www.google.com, plain text, etc.)
- Automatically prepends https:// when required
- Generates QR codes dynamically
- Runs locally using Flask

## Tech Stack
- Python
- Flask
- qrcode
- HTML / CSS

## How to Run Locally

1. Clone the repository
2. Create a virtual environment
3. Install dependencies:
   pip install -r requirements.txt
4. Run the app:
   python app.py
5. Open browser:
   http://127.0.0.1:5000

## Notes
- This repository is for local development.
- Production deployment is maintained separately.

