# EncryptionProject

## Description
EncryptionProject is a Python-based tool for encrypting and decrypting files and images using various encryption techniques, including both traditional and advanced methods.
## Project Structure

- **main.py**: The main script that orchestrates the program.
- **advanced_encryption.py**: Functions for advanced encryption techniques.
- **input_functions.py**: Functions for user input handling.
- **file_functions.py**: Functions for handling file operations such as reading and writing.
- **requirements.txt**: A file that contains a list of all the necessary dependencies for the project.



## Requirements
- Python 3.x

- The required dependencies are listed in **requirements.txt** and include:
- **pycryptodome** - Provides cryptographic functions such as RSA encryption.
- **pillow** - Used for image processing in steganography.
- **pyinputplus** - Handles user input validation.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YehudaWieder/EncryptionProject.git
   ```

2. Navigate to the project directory:
   ```bash
   cd EncryptionProject
   ```
   
3. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. Run the main script:
   ```bash
   python main.py
   ```

2. Follow the on-screen instructions to choose an encryption method:
   ##Encryption Methods:
   **1. Caesar Cipher** - A shift-based encryption where each letter is replaced by another letter.  
   **2. Transposition Cipher** - Rearranges the letters of the plaintext in a predetermined pattern.  
   **3. RSA Encryption** - A public-key cryptosystem where messages are encrypted with a public key and decrypted with a private key.  
   **4. Steganography** - Hides text inside an image file.  
   - Some encryption methods require a **KEY**, which is provided by the user.

