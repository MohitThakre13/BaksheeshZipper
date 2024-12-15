# Zip and Encrypt Software

This software provides functionality to **zip and encrypt** a folder, as well as **decrypt and unzip** it. The encryption process uses the **Baksheesh Cipher** for securing data.

---

## Features
- Compress a folder into a single file.
- Encrypt the compressed file using the **Baksheesh Cipher**.
- Decrypt the encrypted file back to its original state.
- Extract the decrypted content to retrieve the original folder structure.

---

## File Structure
```
software/
│
├── zipEncrypt.py    # Script to zip and encrypt a folder
├── decryptUnzip.py  # Script to decrypt and unzip a folder
└── README.md        # Documentation
```

---
## Usage
### 1. Zipping and Encrypting a Folder
To zip and encrypt a folder:

```bash
python zipEncrypt.py
```
- `folder_path`: Path to the folder you want to compress and encrypt.
- `output_file`: Name of the output encrypted file.



---

### 2. Decrypting and Unzipping a Folder
To decrypt and unzip a file:

```bash
python decryptUnzip.py
```
- `input_file_path`: Path to the encrypted file.
- `output`: Folder's name where the decrypted content will be extracted.



---

## Encryption Algorithm: Baksheesh Cipher
The **Baksheesh Cipher** is a custom encryption technique used in this software. It ensures data security during compression and storage.

---

## License
This software is open source. Feel free to use, modify, and distribute it.

---

## Author
Developed by **Mohit Thakre, Nischay Rajput** and **Harsh Prajapati**.

---

## Notes
- Always ensure you back up your encrypted files.
- For any issues or feature requests, please raise them in the relevant repository or contact the author.


