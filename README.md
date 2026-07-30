# 😂 Random Joke Generator Chrome Extension

A clean and lightweight Chrome extension that fetches a random Chuck Norris joke every time you open the popup or click the **New Joke** button.

![Version](https://img.shields.io/badge/version-1.0.0-blue)
![Manifest](https://img.shields.io/badge/Manifest-V3-success)
![License](https://img.shields.io/badge/License-MIT-green)

---

## ✨ Features

- 😂 Get a random Chuck Norris joke instantly
- 🔄 Generate a new joke with one click
- 📋 Copy jokes directly to your clipboard
- ⚡ Fast and lightweight
- 🎨 Modern minimal/neumorphic UI
- 🖥️ Built using Manifest V3

---

## 📸 Preview

> Add a screenshot of your extension here.

```
popup-preview.png
```

---

## 📂 Project Structure

```
Random-Joke-Generator/
│
├── manifest.json
├── popup.html
├── index.js
├── icon.png
├── README.md
```

---

## 🚀 Installation

1. Clone the repository

```bash
git clone https://github.com/yourusername/random-joke-extension.git
```

Or download the ZIP and extract it.

---

### Load the extension

1. Open Chrome.
2. Visit:

```
chrome://extensions
```

3. Enable **Developer Mode**.
4. Click **Load unpacked**.
5. Select the project folder.

The extension is now ready to use.

---

## 🛠️ Technologies Used

- HTML5
- CSS3
- JavaScript (ES6)
- Chrome Extension API (Manifest V3)
- Chuck Norris Joke API

---

## 🌐 API

This project uses the free Chuck Norris Joke API.

```
https://api.chucknorris.io/jokes/random
```

Example Response:

```json
{
  "value": "Chuck Norris counted to infinity. Twice."
}
```

---

## 🎯 How It Works

1. User opens the extension.
2. The extension requests a random joke from the API.
3. The joke is displayed inside the popup.
4. Clicking **New Joke** fetches another joke.
5. Clicking **Copy** copies the joke to the clipboard.

---

## 📦 Permissions

Current permissions:

- Clipboard Write

No personal information is collected or stored.

---

## 💡 Future Improvements

- ⭐ Favorite jokes
- 🌙 Dark mode
- 🔊 Read jokes aloud
- ❤️ Like/Dislike jokes
- 📤 Share to social media
- 📝 Joke history
- 🎭 Category filters
- 🔔 Daily joke notifications

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repository.
2. Create a new feature branch.

```bash
git checkout -b feature-name
```

3. Commit your changes.

```bash
git commit -m "Add new feature"
```

4. Push to your branch.

```bash
git push origin feature-name
```

5. Open a Pull Request.

---

## 📜 License

This project is licensed under the MIT License.

---

## 👨‍💻 Author

**Ritesh Dubey**

GitHub: https://github.com/ritesh-1209

---

### ⭐ If you enjoyed this project, don't forget to star the repository!
