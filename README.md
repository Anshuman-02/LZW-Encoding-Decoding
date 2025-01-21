# Lempel-Ziv-Welch (LZW) Encoding and Decoding 📜

This repository contains a Python implementation of the **Lempel-Ziv-Welch (LZW)** algorithm for data compression and decompression. The algorithm dynamically builds a dictionary to encode and decode variable-length input efficiently.

---

## Features

- **Encoding**: Compresses input strings into numeric codes.
- **Decoding**: Reconstructs the original string from the codes.
- **Dynamic Dictionary**: Handles variable-length inputs with a growing dictionary.

---

## How to Run

1. Install Python 3.x from [python.org](https://www.python.org/).
2. Save the script as `lzw_compression.py`.
3. Open a terminal and run:
   ```bash
   python lzw_compression.py
4. Enter a string when prompted to see the encoded and decoded results.

## Example Usage
### Input:
Enter a message to encode: hello world

### Output:
- Encoded: [104, 101, 108, 108, 111, 32, 119, 111, 114, 108, 100] 
- Decoded: hello world

## Applications
- File compression for storage efficiency.
- Data transmission over networks.
- Lossless compression for text processing.
