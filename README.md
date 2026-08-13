🌐 [English](README.md) | [Русский](README_ru.md) | [中文](README_zh.md)

---

# Google AI Chat Exporter 🚀

A lightweight, zero-resource bookmarklet that allows you to export your entire chat history with Google AI (AI Search/Gemini) in one click. 

Unlike official tools, this script exports the **entire conversation chronologically** (including your prompts and AI responses) and saves it as clean Markdown (`.md`) and/or Text (`.txt`) files.

## Features
- **Zero background resource usage:** It's just a bookmarklet, not an extension.
- **Smart Formatting:** Keeps all HTML structure (bold text, lists, code blocks, links) intact and converts it to pure Markdown.
- **Garbage Cleaning:** Automatically removes UI buttons ("Copy", "Edit", "Share"), system warnings, and extraneous UI elements.
- **Customizable Exports:** Allows you to name your file and choose the desired format (`.md`, `.txt`, or both).
- **Time-stamped:** Automatically appends the current date and time to the filename.

## Installation (1 Minute Setup)
1. Press `Ctrl + D` (`Cmd + D` on Mac) in your browser to create a new bookmark on any page.
2. Click **More...** or **Edit** to edit the bookmark details.
3. In the **Name** field, type something like `📥 Export AI Chat`.
4. In the **URL** field, copy and paste the [entire JavaScript code from here](https://github.com/MakeHorizont/Google-Search-Ai-chat-downloader/blob/main/Google_Ai_Search_Chat_Downloader_Bookmarklet.txt).
5. Save it and place it on your Bookmarks Bar.

## How to use
1. Open your chat with Google AI.
2. Scroll to the top (to make sure the whole chat is loaded in the browser).
3. Click your new `📥 Export AI Chat` bookmark.
4. Enter a name for the file when prompted.
5. Choose your desired format (1 = `.md`, 2 = `.txt`, 3 = both).
6. Done! The files will be downloaded to your PC.

## Privacy & Security
The script runs entirely locally in your browser. It does not send your chat data to any external servers.
