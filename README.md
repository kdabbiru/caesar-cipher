# Caesar Cipher Encoder/Decoder

## Project Overview
This project is a **Caesar Cipher Encoder/Decoder** web application that lets users encode or decode text using the Caesar cipher algorithm. The application is built using HTML, CSS, and JavaScript, providing an interactive interface to apply cipher transformations with customizable parameters.

---

## Features
- **Encode/Decode Modes**: Switch between encoding plaintext and decoding ciphertext.
- **Customizable Parameters**:
  - Shift key for the cipher.
  - Modulo value for wrapping character indices.
  - Custom alphabet set.
  - Options to remove foreign characters.
  - Letter case customization (lowercase/uppercase).
- **Interactive User Interface**: Intuitive input fields and real-time output updates.
- **Validation**: Handles foreign characters and ensures smooth cipher transformation.

---

## File Structure
```plaintext
├── index.html          # Main HTML file for the app layout.
├── style.css           # CSS file for styling the UI.
├── caesar.js           # JavaScript file containing the cipher logic and DOM interactions.
```

---

## Getting Started
1. Clone the repository:
   ```bash
   git clone https://github.com/kdabbiru/caesar-cipher.git
   ```
2. Open the `index.html` file in any modern browser.

---

## How to Use
1. **Select Mode**:
   - Choose between "Encode" or "Decode" using the radio buttons.
2. **Input Text**:
   - Enter the text you want to transform in the input box.
3. **Set Parameters**:
   - Adjust the shift key, modulus, and custom alphabet as needed.
   - Choose whether to remove foreign characters and the letter case output.
4. **View Output**:
   - The result is displayed in the output box.

---

## Customization
### Parameters
- **Shift Key**: Determines how far characters are shifted.
- **Modulo**: Sets the wrap-around value for character indices.
- **Alphabet**: Defines the set of characters to use for the cipher.
- **Foreign Characters**:
  - Enable to remove non-alphanumeric characters.
- **Letter Case**:
  - Preserve, convert to lowercase, or convert to uppercase.

---

# Technical Details
### Caesar Cipher Function
The main cipher logic is implemented in the `caesarCipher` function:
```javascript
function caesarCipher(decode, text, shift, mod, charset, foreignChars) {
    // Logic for encoding/decoding
}
```
Key functionalities include:
- Handling character wrapping with modular arithmetic.
- Removing foreign characters when specified.
- Retaining the case sensitivity of characters.

### Validation
- Input fields are validated to ensure numeric values for the shift and modulo.
- Alphabet and text inputs are sanitized to match the expected format.

---

## Contribution
Contributions are welcome! Feel free to fork this repository and submit pull requests for enhancements or bug fixes.

---


## Acknowledgements
- Built with ❤️ using JavaScript.
- Inspired by classic cryptography techniques.
