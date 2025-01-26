

# 📝React.js Todo App

<img src="https://raw.githubusercontent.com/maciekt07/TodoApp/main/screenshots/baner.png" />

## [https://react-cool-todo-app.netlify.app/](https://react-cool-todo-app.netlify.app/)

[![Netlify Status](https://api.netlify.com/api/v1/badges/e3b07d34-f0da-4280-9076-fd40eea893c6/deploy-status)](https://app.netlify.com/sites/react-cool-todo-app/deploys)
![GitHub code size in bytes](https://img.shields.io/github/languages/code-size/vineela1304/TodoApp?color=%23b624ff)
![GitHub created at](https://img.shields.io/github/created-at/vineela1304/TodoApp?color=%23b624ff)
![GitHub last commit](https://img.shields.io/github/last-commit/vineela1304/TodoApp?color=%23b624ff)



## 💻 Tech Stack

<ul style="display: flex; flex-direction: column; gap:10px;">
  <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=react" alt="react" width="24" style="vertical-align: middle; margin-right: 4px;" /> React
  </li>
    <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=typescript" alt="typescript" width="20" style="vertical-align: middle;margin-right: 4px;" /> Typescript
  </li>
    <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=vite" alt="vite" width="24" style="vertical-align: middle;margin-right: 4px;" /> Vite
  </li>
  <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=vitest" alt="vitest" width="24" style="vertical-align: middle;margin-right: 4px;" /> Vitest
  </li>
  <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=emotion" alt="emotion" width="24" style="vertical-align: middle;margin-right: 4px;" /> Emotion
  </li>
    <li style="vertical-align: middle;">
    <img src="https://go-skill-icons.vercel.app/api/icons?i=mui" alt="mui" width="24" style="vertical-align: middle;margin-right: 4px;" /> Material UI (MUI)
  </li>
</ul>

## ⚡ Features

### 🔗 Share Tasks by Link or QR Code

Easily share your tasks with others using a link or QR code, with the option to download the QR code.

**[Example Link](https://react-cool-todo-app.netlify.app/share?task=N4IgJg9gdgpiBcAzAhgGwM4wDQgA4EspYwEAXAJwFdsQpkBbOeEAdRgCN19SYACAERgA3GKgi5GUUiBxgY6AMbl8uUvmgIQAYXIxkPXsl6pkUMIQDmvXMgt8A7twAWvAEp6FpAHQArdL0QIcl4FVHwYKS9eJ1JSXHR4AHpE+1SvAE8ISlJKdhgvBQh6FP0FJwB+IQBedgBZAGsoRABpAA0ASQAxAEEADgAyUiqAJgBmdH7kdgB9MtNYVCrEXRgtCDktBlwvIIsZEBh6CB98TQBGRAAWADZegFoL0cQFO+GABjewB6v2dn3CsTkTQAYnY12Gl0QiH2YH0TBA7whDzODwA7AAVM6jeCXS7wM7DLwAVlRAE4AFr-OEWILpBAAbVA+BI+NuqIJRMuZ1RN1Gb1GODojE0a3MUD2OEOx1OzAuROQRLuiBgb2hOABQRB1zABKhIAAvlgmSzhoKGPCWEF6vspSdzohRjBhv8IICQRDejA9fqALo4EzoUgAZWQIk0iMuyLRmOxuPxvS8pLeqMp+qAA&userName=Maciej)**

<img src="C:\Users\saivi\OneDrive\Pictures\Screenshots\Screenshot 2025-01-26 151949.png" width="300px" alt="Shared Task" />

### 🤖 AI Emoji Suggestions

This uses `window.ai` which is an experimental feature that works only in dev version of Chrome with some flags enabled. [More info](https://afficone.com/blog/window-ai-new-chrome-feature-api/)

Code: [src/components/EmojiPicker.tsx](https://github.com/vineela1304)

<img src="C:\Users\saivi\OneDrive\Pictures\Screenshots\Screenshot 2025-01-26 151539.png" alt="AI Emoji" width="360px" style="border-radius:12px" />

### 🎨 Color Themes

Users can choose several app color themes and choose between light and dark mode.

<img src="C:\Users\saivi\OneDrive\Pictures\Screenshots\Screenshot 2025-01-26 151847.png" width="200px" alt="Color Themes" />

### 🗣️ Task Reading Aloud

Option to have tasks read aloud using the native `SpeechSynthesis` API, with a selection of voices to choose from.

<img src="C:\Users\saivi\OneDrive\Pictures\Screenshots\Screenshot 2025-01-26 151806.png" width="260px" alt="Task Reading Aloud" />

### 📥 Import/Export Tasks

Users can import and export tasks to/from JSON files. This feature allows users to back up their tasks or transfer them to other devices easily. [Example Import File](https://github.com/vineela1304)

### 📴 Progressive Web App (PWA)

This app is a Progressive Web App (PWA), which means it can be installed on your device, used even when you're offline and behave like a normal application with shortcuts and badges.

<img src="https://raw.githubusercontent.com/maciekt07/TodoApp/main/screenshots/pwaTaskBar.png" alt="taskbar" width="260px" />

### 🔄 Update Prompt

<!-- The app features a custom update prompt that notifies users when a new version is available, allowing for easy refresh to access the latest improvements. -->



<!-- <img src="C:\Users\saivi\OneDrive\Pictures\Screenshots\Screenshot 2025-01-26 152312.png" alt="update prompt" width="260px" /> -->

## 👨‍💻 Installation

To install and run the project locally, follow these steps:

- Clone the repository: `git clone https://github.com/vineela1304`
- Navigate to the project directory: `cd TodoApp`
- Install the dependencies: `npm install`
- Start the development server: `npm run dev`

The app will now be running at [http://localhost:5173/](http://localhost:5173/).

> [!TIP]
> For mobile device testing, use `npm run dev:host` to preview the app on your local network.

## 📷 Screenshots

<img src="C:\Users\saivi\OneDrive\Pictures\Screenshots\Screenshot 2025-01-26 151045.png" width="500px" />

<img src="C:\Users\saivi\OneDrive\Pictures\Screenshots\Screenshot 2025-01-26 150911.png" width="300px" />
<img src="C:\Users\saivi\OneDrive\Pictures\Screenshots\Screenshot 2025-01-26 151431.png" width="300px" />


<img src="C:\Users\saivi\OneDrive\Pictures\Screenshots\Screenshot 2025-01-26 151231.png" width="650px" />

## 🚀 Performance

<img src="C:\Users\saivi\OneDrive\Pictures\Screenshots\Screenshot 2025-01-26 151348.png"width="600px" />

## Credits

Made with ❤️ by [vineela](https://github.com/vineela1304)
