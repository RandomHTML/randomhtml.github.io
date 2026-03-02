# Duel of Legends - Local Multiplayer Fighting Game

This is a modern web application built with **React**, **TypeScript**, and **Tailwind CSS**.

## 🚀 How to Run Locally

Because this app uses modern web technologies, you cannot simply open the `index.html` file in your browser. You need to run a small local server.

### Prerequisites
- Install **Node.js** (v18 or higher) from [nodejs.org](https://nodejs.org/).

### Setup Instructions
1. **Download and Extract** the project files to a folder on your computer.
2. **Open a Terminal** (Command Prompt, PowerShell, or Terminal) in that folder.
3. **Install the dependencies**:
   ```bash
   npm install
   ```
4. **Start the game**:
   ```bash
   npm run dev
   ```
5. **Play**: Open your browser and go to the address shown in the terminal (usually `http://localhost:3000`).

## 🛠️ Controls

### Player 1 (Blue)
- **W**: Jump
- **A**: Move Left
- **D**: Move Right
- **S**: Attack

### Player 2 (Red)
- **Up Arrow**: Jump
- **Left Arrow**: Move Left
- **Right Arrow**: Move Right
- **Down Arrow**: Attack

*Note: On mobile or tablet devices, touch controls will appear automatically.*

## 🌐 Deploying to GitHub Pages

I have pre-configured this project for easy deployment to GitHub Pages.

1. **Initialize a Git Repository** (if you haven't):
   ```bash
   git init
   git add .
   git commit -m "Initial commit"
   ```
2. **Create a new repository on GitHub** and link it:
   ```bash
   git remote add origin https://github.com/YOUR_USERNAME/YOUR_REPO_NAME.git
   ```
3. **Deploy with one command**:
   ```bash
   npm run deploy
   ```
   *This will automatically build the project and upload it to a `gh-pages` branch on GitHub.*

4. **Final Step on GitHub**:
   - Go to your repository on GitHub.
   - Click **Settings** > **Pages**.
   - Under "Build and deployment", ensure the source is set to "Deploy from a branch" and the branch is set to `gh-pages`.

## 🏗️ Building for Production
If you want to host this on a website (like GitHub Pages or Vercel):
```bash
npm run build
```
The "ready-to-upload" files will be in the `dist` folder.
