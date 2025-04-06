# ADVANCED-ENCRYPTION-TOOL
*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: RAYAPATI MANOJ KUMAR

*INTERN ID*: CT04WK146

*DOMAIN*: CYBER SECURITY

*DURATION*: 4 WEEKS

*MENTOR*: NEELA SANTOSH

DESCRIPTION:
The Advanced Encryption Tool is a robust and user-friendly application designed for encrypting and decrypting both text and files using industry-standard AES-256 encryption. Built with Python, the tool combines powerful cryptographic functions with an intuitive graphical user interface (GUI), making it suitable for both beginners and professionals in the field of cybersecurity.

This project was developed to provide a practical solution for data security in daily usage. Whether it’s securing personal notes, confidential files, or sharing encrypted messages, this tool offers a simple yet secure way to handle sensitive information. It uses the Fernet module from Python’s cryptography library, which implements AES encryption in Cipher Block Chaining (CBC) mode with a 128-bit initialization vector and a 256-bit key. This ensures strong encryption that is difficult to break through brute force or other common attacks.

The application’s interface is built using Tkinter, Python’s standard GUI toolkit. This ensures cross-platform compatibility and ease of use without requiring advanced technical knowledge. Upon launching the application, users are greeted with a clean layout that allows them to choose between text mode or file mode, depending on their encryption needs.

In text mode, users can input a plaintext message and a valid 32-byte base64-encoded key. When the “Encrypt” button is clicked, the application encrypts the message and displays the ciphertext in a dialog box. For decryption, users paste the ciphertext and use the same key to retrieve the original message. This functionality is ideal for securely storing or sharing small pieces of sensitive information.

In file mode, the tool allows users to select a file from their device and encrypt it using the provided key. The encrypted output is saved as a new file with the .enc extension, preserving the original data. To decrypt, the user simply selects the encrypted file and provides the correct key. The decrypted file is saved with a new name, ensuring data safety even if the original file is lost or modified.

To use the tool securely, users must generate or obtain a valid 32-byte base64 key. While the tool does not store or manage keys (to enhance security), it expects the user to supply the correct key during each session. This key is critical—without it, encrypted data cannot be decrypted, adding a strong layer of protection.

The Advanced Encryption Tool has practical use in real-world scenarios such as securing client documents, protecting software source code, or safeguarding research and business plans. Since the encryption process complies with modern cryptographic standards, the application can be trusted for moderate to high-level data security needs.

Interns who complete this project gain hands-on experience with encryption techniques, Python programming, GUI development, and user experience design. The final product demonstrates the integration of functionality and usability—a key skill in professional software development. Upon successful implementation, participants are eligible for a Completion Certificate from CodTech, recognizing their achievement and practical understanding of applied cryptography.

This project not only serves as a learning platform but also provides a useful tool that can be applied in both personal and professional environments where data protection is a priority.


OUTPUT:
