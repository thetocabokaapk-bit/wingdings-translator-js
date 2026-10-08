# ⚡ Wingdings Translator & Decoder (JavaScript Utility)

A lightweight, zero-dependency JavaScript tool to encode regular English text into Wingdings 1, 2, 3 & Webdings symbols, and decode secret symbol messages back into readable text.

🔗 **Live Web Application & Free Tool:**  
👉 [Wingdings Translator (Instant Copy & Paste)](https://wingding-translator.com/)

---

## 🌟 Key Features

- **Bidirectional Conversion:** English to Wingdings symbols & Wingdings to English decoding.
- **Multiple Font Sets:** Supports Wingdings 1, Wingdings 2, Wingdings 3, and Webdings.
- **Unicode Compatible:** Generated symbols work across Discord, Undertale, Minecraft, and social media.
- **No Dependencies:** Pure vanilla JavaScript implementation.

---

## 🚀 Quick Usage Example

```javascript
// Sample character mapping snippet
const wingdingsMap = {
  'A': '✌', 'B': '👌', 'C': '👍', 'D': '👎', 'E': '☜',
  'F': '☞', 'G': '☝', 'H': '☟', 'I': '✋', 'J': '☺'
};

function encodeToWingdings(text) {
  return text.toUpperCase().split('').map(char => wingdingsMap[char] || char).join('');
}

console.log(encodeToWingdings("HI")); // Output: ✋☺
🌐 Official Web Tools
## 🌐 Official Web Tools

- **Main Tool:** [English to Wingdings Translator](https://wingding-translator.com/)
- **Undertale / Lore:** [W.D. Gaster Font Decoder](https://wingding-translator.com/w-d-gaster-translator-undertale-wingdings-decoder/)
- **Image Scanner:** [Wingdings Translator from Image](https://wingding-translator.com/wingdings-translator-from-image/)
- **Gaming:** [Wingdings Font for Minecraft](https://wingding-translator.com/wingdings-font-for-minecraft/)
📄 License

This project is open-source and free to use under the MIT License.
