# 🟩 Wordle Daily Inspector

An automated client-side inspector script that safely scans active data nodes to reveal the hidden solution code for the daily New York Times Wordle puzzle. 

## 🚀 Live Demo
You can view the project interface and deployment hub here: 
👉 **[Wordle Inspector Deployment Hub](https://rubik-dev-code.github.io/wordle-answer/)**

---

## 🛠️ How to Use the Shortcut

Since browser extensions frequently block standard bookmarklet dragging, follow this direct web console integration structure:

1. Copy the core execution script from the deployment page or copy it directly from your `script.js` file in this repository.
2. Open the official [New York Times Wordle Website](https://nytimes.com).
3. Open your browser's Developer Tools by pressing **F12** (or **Right-Click** anywhere on the page and choose **Inspect**).
4. Click on the **Console** tab at the top of the developer panel.
5. Paste the copied code into the input line at the absolute bottom of the console and hit **Enter**!

---

## 🔍 Deep-Dive: How it Works

The script operates directly within your local browser runtime memory using four failure-proof logic layers:

1. **DOM Tree Target Extraction:** It immediately looks for the `__NEXT_DATA__` script tag or the `[data-testid="wordle-state-provider"]` structural block where the active game state configuration is hydrated.
2. **JSON Hydration Scraping:** It attempts to safely unpack the inner text tree content into a structured object, routing through known application data paths like `pageProps.gameData.solution`.
3. **Runtime Window Inspection:** If data structures are obfuscated, the fallback loop cycles through root global runtime properties inside the `window` memory pool tracking exact string matches for `wordle` or `game`.
4. **Clean Canvas Rendering:** Upon a successful logic match, it surfaces the word block in the console using high-visibility, CSS-styled color blocks mimicking the classic game win blocks.

---

## ⚙️ Repository Layout
* `README.md` - The clear onboarding blueprint you are reading right now.
* `script.js` - The master execution loop handling target structural validation and automated console outputs.

---
*Disclaimer: Developed cleanly for educational exploration, data tree mapping, and front-end JavaScript analytics testing.*
