# ZipCracker ⚡

A lightweight, efficient Bash-based dictionary attack tool for password-protected ZIP files.

## 🚀 Features
- **Memory Efficient**: Processes password lists line-by-line (safe for large files).
- **Fast Testing**: Uses `unzip -t` to test passwords in-memory without extracting files to disk.
- **Silent Mode**: Suppresses all standard error noise for a clean terminal output.
- **Pure Bash**: No heavy dependencies; requires only `unzip`.

## 🛠️ Installation & Usage

1. **Clone the repository:**
   ```bash
   git clone [https://github.com/yourusername/zipcracker.git](https://github.com/yourusername/zipcracker.git)
   cd zipcracker/src

2. **Make the script executable**
    chmod +x zipcracker

3. **Make the script global**
    sudo cp zipcracker /usr/local/bin/zipcracker

4. **Run the cracker**
    zipcracker passwords.txt secure.zip

Note: passwords.txt is the password list required, and secure.zip is the encrypted zip file, you can use the path these parameters in the script(i.e /home/user/Downloads/passwords.txt, /home/user/Downloads/secure.zip)

📋 Requirements
1. Linux

2. unzip utility (installed by default on most distros)

⚠️ Disclaimer
This tool is for educational purposes and authorized security testing only. Using this tool against systems or files you do not have explicit permission to test is illegal. The author is not responsible for any misuse.