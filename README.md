# qr-code-generator-python

A simple Python QR Code Generator that converts user-provided URLs into QR code images.

## Features

* Generate QR codes from URLs
* Simple command-line interface
* Automatically saves the generated QR code as a PNG image
* Lightweight and beginner-friendly

## Technologies Used

* Python
* qrcode
* Pillow

## Requirements

* Python 3.x
* `qrcode[pil]`

## Installation

### 1. Clone the repository

```bash
git clone https://github.com/YOUR-USERNAME/qr-code-generator-python.git
```

### 2. Navigate to the project folder

```bash
cd qr-code-generator-python
```

### 3. Install the required package

```bash
pip install -r requirements.txt
```

## How to Run

Run the following command:

```bash
python main.py
```

The program will ask you to enter a URL:

```text
Enter the URL to generate QR code: https://www.google.com
```

The QR code will be generated and saved as:

```text
qrcode.png
```

## Example

### Input

```text
Enter the URL to generate QR code: https://www.google.com
```

### Output

```text
QR code generated and saved to: qrcode.png
```

The generated QR code image will be saved in the project directory.

## Project Structure

```text
qr-code-generator-python/
│
├── QRCodeGen (Main Folder)
├── README.md
└── LICENSE
```

## Future Improvements

* Add a graphical user interface using Tkinter
* Allow users to customize QR code colors
* Allow users to choose the output file name
* Add support for text and other types of data

## License

This project is licensed under the MIT License.

## Author

**Raiyan**

GitHub: https://github.com/TahlilAlRaiyan


