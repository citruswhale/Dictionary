# 📖 Dictionary App

## 🌟 Overview
This project is a **Dictionary Web App** built using **HTML, CSS, and JavaScript**. It allows users to:
- Search for words and get their meanings, examples, and synonyms.
- Hear word pronunciations.
- Display random meaningful words dynamically in animated cards.
- Use a scrolling carousel of word cards with automatic updates.

## 🏗️ Tech Stack
- **HTML**: Structure of the dictionary app.
- **CSS**: Styling and layout, including animations.
- **JavaScript**: Handles API calls, DOM manipulation, and user interactions.
- **APIs Used**:
  - [Dictionary API](https://dictionaryapi.dev/): Fetches word definitions, examples, and pronunciations.
  - [Datamuse API](https://www.datamuse.com/api/): Fetches meaningful random words.

## 📂 File Structure
```
📁 Dictionary-App
│── 📄 index.html      # Main HTML file
│── 📄 styles.css      # CSS styles for UI & animations
│── 📄 script.js       # JavaScript logic
```

## 🖥️ Features & Functionality
### 🔎 1. Search Functionality
- Users can type a word in the search bar.
- The app fetches and displays the word's meaning, example, and synonyms using the **Dictionary API**.
- If the word is not found, an error message is displayed.

### 🔊 2. Word Pronunciation
- Clicking on the speaker icon plays the pronunciation audio using the URL provided by the **Dictionary API**.

### 📜 3. Random Word Cards
- Fetches a list of random meaningful words from the **Datamuse API**.
- Each card displays a unique word.
- Cards scroll automatically in a carousel animation.
- Updates every **10 seconds**.

### 🎨 4. Animated Carousel
- Uses CSS animations for a vertical scrolling effect.
- Hovering over the carousel pauses the animation.

## 🚀 How to Run Locally
1. Clone the repository:
   ```sh
   git clone https://github.com/your-username/dictionary-app.git
   ```
2. Open `index.html` in a browser.

## 🌐 Deployment Options
You can host this project using:
- **GitHub Pages**
- **Vercel**
- **Netlify**

## 🎯 What You’ll Learn
- How to fetch and display data from external APIs.
- How to use the Web Speech API for audio playback.
- How to create a scrolling carousel using CSS animations.
- How to handle asynchronous JavaScript with `fetch()` and `async/await`.

---

This project is a great introduction to **front-end web development** and working with APIs. Happy coding! 🚀

