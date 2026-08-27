# AvatarTranslate

A real-time conversational 3D avatar assistant built with vanilla JavaScript, HTML5, CSS3, and Three.js. It features browser-based voice recognition, a procedural 3D avatar with reactive speech animations, and multi-language text-to-speech support.

## Features

* **3D Avatar Rendering:** Renders a responsive 3D character using Three.js with idle animations, blinking eyes, and a jaw mechanism that synchronizes with speech.
* **Speech Recognition:** Integrates the browser's native Web Speech API (`SpeechRecognition`) to convert user voice input into text.
* **Local Conversational Engine:** Includes a built-in rule-based intent handler for instant offline responses, greetings, and help prompts.
* **Text-to-Speech & Multi-Language:** Converts the assistant's replies into spoken audio supporting multiple languages (Spanish, English, Portuguese, Italian, German, French) and custom voice selection.
* **Zero Dependencies / Framework-Free:** Built entirely with vanilla web technologies—no complex build tools or heavy backend servers required.

## Project Structure

```text
AvatarTranslate/
├── index.html       # Complete application (HTML, CSS, and JavaScript)
├── README.md        # Project documentation
└── LICENSE          # MIT License
