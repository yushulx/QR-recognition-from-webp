# Reading QR Code from WebP Images
The samples demonstrate how to recognize QR code from WebP images with Dynamsoft Barcode Reader in C/C++ and Python applications.

## Installation
- Dynamsoft Barcode Reader 8.6
    - [C/C++](https://www.dynamsoft.com/barcode-reader/downloads/)
    - Python
    
        ```bash
        pip install dbr opencv-python
        ```
- [libwebp-1.2.1](https://storage.googleapis.com/downloads.webmproject.org/releases/webp/libwebp-1.2.1.tar.gz)

## License Key
Get a valid license key from the [Dynamsoft Customer Portal](https://www.dynamsoft.com/customer/license/trialLicense?product=dbr) and save it to a `license.txt` file.

## Usage

### C/C++

```bash
mkdir build
cd build
cmake ..
cmake --build .
BarcodeReader <webp file> license.txt
```

### Python

```bash
python main.py <webp file> license.txt
```

## Reference
- [https://developers.google.com/speed/webp](https://developers.google.com/speed/webp)

## Blog
[How to Decode QR Code from WebP Images in C++ and Python](https://www.dynamsoft.com/codepool/webp-qr-code-recognition-cpp-python.html)
