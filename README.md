# TeamViewerPasswordDecryptor

Password decryptor for TeamViewer

## Usage
If we manage to get, for example `SecurityPasswordAES` properties in a system, it might look like a list of integer numbers. Save that list into a file (for example, `example.txt`), run this script and get the decrypted password


```shell-session
python3 decrypt_password_teamviewer.py -l example.txt
```
