<p align="center">
  <svg width="650" height="80" viewBox="0 0 650 80" xmlns="http://w3.org">
    <defs>
      <!-- 1. The Rainbow Gradient Matrix -->
      <linearGradient id="rainbow" x1="0%" y1="0%" x2="100%" y2="0%">
        <stop offset="0%" stop-color="#FF0000" />
        <stop offset="16.6%" stop-color="#FF7F00" />
        <stop offset="33.3%" stop-color="#FFFF00" />
        <stop offset="50%" stop-color="#00FF00" />
        <stop offset="66.6%" stop-color="#0000FF" />
        <stop offset="83.3%" stop-color="#4B0082" />
        <stop offset="100%" stop-color="#8B00FF" />
      </linearGradient>
      
      <!-- 2. The Typing & Deleting Animation Mask -->
      <mask id="typing-mask">
        <rect x="0" y="0" width="0" height="80" fill="white">
          <animate 
            attributeName="width" 
            values="0; 650; 650; 0; 0" 
            keyTimes="0; 0.4; 0.6; 0.9; 1" 
            dur="5s" 
            repeatCount="indefinite" />
        </rect>
      </mask>
    </defs>

    <!-- 3. The Animated Blinking Cursor Bar -->
    <rect x="0" y="15" width="4" height="42" fill="#00FF00">
      <animate 
        attributeName="x" 
        values="0; 590; 590; 0; 0" 
        keyTimes="0; 0.4; 0.6; 0.9; 1" 
        dur="5s" 
        repeatCount="indefinite" />
      <animate 
        attributeName="opacity" 
        values="1; 1; 0; 0; 1" 
        keyTimes="0; 0.5; 0.55; 0.85; 0.9" 
        dur="1s" 
        repeatCount="indefinite" />
    </rect>

    <!-- 4. The Rendered Rainbow Text Layer -->
    <text 
      x="15" 
      y="50" 
      font-family="'Courier New', Courier, monospace" 
      font-size="38" 
      font-weight="bold" 
      fill="url(#rainbow)" 
      mask="url(#typing-mask)">
      Wordle Daily Inspector
    </text>
  </svg>
</p>


---

## ✨ Features

* **Zero-Setup Execution:** Runs natively directly out of your browser's bookmark bar.
* **Realistic Emulated Typing:** Simulates visual physical button clicks on the virtual Wordle keyboard layout with customized keystroke delays.
* **Dramatic Calculation Pause:** Displays a realistic overlay alert to convince onlookers the machine is computing complex multi-variable elimination paths.

---

## 🚀 How to Install & Use

If you want to use the Dev menu either Ctrl+Shift+J or Cmd+Shift+J the code is here -> https://github.com/Rubik-dev-code/wordle-answer/blob/main/copy%26paste  

If you want to Use bookmarklets then the code is here -> https://github.com/Rubik-dev-code/wordle-answer/blob/main/Bookmarklet 

---

## 📝 License
This project is open-source and intended entirely for educational, testing, and casual demonstration environments.

