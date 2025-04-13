# UPI QR Code Generator

This simple Python script generates UPI payment QR codes for **PhonePe**, **Paytm**, and **Google Pay** using a user-input UPI ID.

## 📽️ Reference Video

This project is based on the tutorial: [Generate UPI QR Code using Python](https://youtu.be/XR0qVaNNaAo?si=qf6N7UUyXaLXTEA4)

## 💡 Features

- Accepts UPI ID from user input
- Generates QR codes for three popular UPI apps
- Saves each QR as a PNG image
- Automatically opens the generated QR codes for viewing

## 🛠️ Requirements

- Python 3.x
- `qrcode` library
- `Pillow` library (usually installed with `qrcode`)

Install requirements using pip:

```bash
pip install qrcode[pil]
