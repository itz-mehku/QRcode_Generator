# Mini Project 16 : QR Code Generator
This Python script generates a QR code for a given GitHub profile link using the `pyqrcode` module.

--> What It Does:
1. Takes URL (or any text/link).

2. Creates a QR code from that URL.

3. Saves the QR code as a `.png` image file.

--> How It Works:
1. The script uses the `pyqrcode` library to create the QR code.

2. The link is passed to the generator (`pyqrcode.create()`).

3. The QR code is saved as a PNG file with a defined scale.
