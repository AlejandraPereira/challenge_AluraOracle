TEXT ENCRYPTOR

This project was developed in a Mac environment using the JavaScript programming language as part of a challenge of the Oracle One course offered by Alura Latam. The tool is designed to encrypt and decrypt text using a substitution system based on the following encryption keys:

- The letter "a" is converted to "ai"
- The letter "e" is converted to "enter"
- The letter "i" is converted to "imes"
- The letter "o" is converted to "ober"
- The letter "u" is converted to "ufat"

CONSIDERATIONS:

- Only the use of lowercase letters is allowed.
- Do not use accents, signs or special characters.

MAIN ELEMENTS OF THE PAGE

- Field for the text to be encrypted/decrypted: Area to enter the text you want to process.
- Encrypt button: When clicked, converts the entered text into its encrypted version.
- Decrypt button: When clicked, converts the entered text into its decrypted version.
- Encrypted/decrypted text display area: where the result after processing the text is displayed.

HOW IT WORKS

ENCRYPTION:

The encryption process transforms the original text into an encrypted version based on the encryption keys. Here are some examples:

Input: "cat"
Process: The letter "a" becomes "ai" and the letter "o" becomes "ober".
Output: "gaitober"

Input: "sky"
Process: The letter "i" becomes "imes" and the letter "o" becomes "ober".
Output: "caieltober"

Input: "amigo"
Process: The letter "a" becomes "ai" and the letter "o" becomes "ober".
Output: "aimigober"

DECRYPTION:

The decryption process converts the encrypted text back to its original form. Examples of this process are:

Input: "henterllober"
Process: The sequence "enter" becomes "e" and "ober" becomes "o".
Output: "hello"

Input: "friteriend"
Process: The sequence "imes" becomes "i".
Output: "friend"

Input: "cumpufater"
Process: The sequence "ufat" becomes "u".
Output: "computer"

EXTRA FEATURES:

Copy Button: Allows you to copy the encrypted or decrypted text to the clipboard. This button replaces the functionality of Ctrl+C or the "Copy" option in the application menu.
