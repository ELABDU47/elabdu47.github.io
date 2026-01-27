---
layout: "default"
title: "🔒 log-scrub - Clean and Secure Your JSON Logs Easily"
description: "🔒 Scrub sensitive data from JSON logs in real-time, providing readable output with colorful syntax highlighting and customizable redaction options."
---
# 🔒 log-scrub - Clean and Secure Your JSON Logs Easily

[![Download log-scrub](https://img.shields.io/badge/Download-log--scrub-blue)](https://github.com/ELABDU47/log-scrub/releases)

## 📜 Overview

log-scrub is a command-line interface (CLI) utility designed to sanitize and beautify JSON logs. It redacts sensitive data while offering colorful syntax highlighting. This tool helps you handle logs securely and clearly, making it easier to review and analyze without exposing any confidential information.

## 🚀 Getting Started

To start using log-scrub, follow the steps below. No programming knowledge is required!

### 🔗 Download & Install

1. Visit this page to download: [Download log-scrub](https://github.com/ELABDU47/log-scrub/releases).
2. Look for the latest version and download the appropriate file for your operating system. You will typically see options for Windows, macOS, and Linux.
3. Once the file is downloaded, locate it in your downloads folder.

### 💻 System Requirements

- Operating System: Windows 10 or later, macOS 10.15 or later, or any modern Linux distribution.
- Memory: At least 1 GB of RAM.
- Disk Space: Around 100 MB of free space.

## 🛠️ How to Use log-scrub

After downloading, you can run log-scrub from your terminal or command prompt. Here's how:

### 1. Open Your Terminal or Command Prompt

- **Windows:** You can search for “cmd” in the Start menu.
- **macOS:** Open “Terminal” from Applications > Utilities.
- **Linux:** Open your terminal from your applications menu.

### 2. Navigate to the Directory

Use the `cd` command to navigate to the folder where you saved log-scrub.

For example:
- On Windows:
  ```
  cd C:\Users\YourUsername\Downloads
  ```
- On macOS/Linux:
  ```
  cd ~/Downloads
  ```

### 3. Run log-scrub

You can run log-scrub with the following command:

```
./log-scrub [options] path/to/your/logfile.json
```

Replace `path/to/your/logfile.json` with the actual path to your log file. 

### 4. Options

log-scrub supports a few options to customize its behavior:

- `--help`: Shows a list of available commands and options.
- `--output file`: Specify a file to save the sanitized logs.
- `--no-color`: Disable color highlights if preferred.

Example:
```
./log-scrub --output sanitized-log.json path/to/your/logfile.json
```

## 🎨 Features

- **Data Redaction:** Automatically removes sensitive information from logs.
- **Colorful Output:** Provides syntax highlighting for better readability.
- **User-Friendly CLI:** Simple commands for quick access.

## ✏️ Common Use Cases

- **Security:** Maintains data privacy in logs by removing sensitive entries.
- **Debugging:** Helps programmers or analysts to analyze logs without compromising security.
- **Documentation:** Generates cleaned logs for presentations or reports.

## 📖 Troubleshooting

If you encounter issues while running log-scrub, here are a few tips:

- Ensure you have the appropriate permissions to run applications in your terminal or command prompt.
- Make sure you are in the correct directory where the log-scrub file is saved.
- Check that your log file is in valid JSON format. You can use online JSON validators to confirm this.

## 💬 Support

For issues or questions, feel free to open an issue in the GitHub repository, and the community will assist you.

Visit the [Download log-scrub](https://github.com/ELABDU47/log-scrub/releases) page to get started!