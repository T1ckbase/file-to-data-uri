# File to Data URI Converter

> [!WARNING]
> This is vibe-coded

[Site link](https://t1ckbase.github.io/file-to-data-uri/)

A simple, fast, and secure client-side tool to convert any file into its Data URI or Base64 representation. It runs entirely in your browser, meaning your files are never uploaded to a server, ensuring your data remains private.

## ✨ Features

*   **100% Client-Side:** All processing is done in your browser using JavaScript. Your files never leave your computer.
*   **Drag & Drop:** Easily drop one or multiple files anywhere on the page to start the conversion.
*   **Multi-File Support:** Convert multiple files at once, with each result displayed in its own block.
*   **Rich File Info:** See the original file name, MIME type, size, and the final Data URI size with the percentage increase.
*   **One-Click Copy:** A convenient "Copy" button for each result.
*   **Light & Dark Mode:** Automatically adapts to your system's color scheme.
*   **Zero Dependencies:** Written in plain HTML, CSS, and JavaScript. No frameworks, no build steps.

## 🤔 Why This Tool?

Many online file-to-Base64 converters require you to upload your files to their servers. This can be slow and poses a significant privacy risk, especially with sensitive data.

This tool was built to provide a fast, secure, and user-friendly alternative that respects your privacy by performing all operations locally. It's a single HTML file that you can run online or save and use offline.

## 🚀 How It Works

The application is built with modern, dependency-free web technologies:

*   **FileReader API:** The core of the application, used to read the contents of a user-selected file and encode it as a Data URL (`readAsDataURL`).
*   **Drag and Drop API:** Enables the intuitive drag-and-drop functionality for file input.
*   **Clipboard API:** Powers the secure, one-click "Copy" functionality (`navigator.clipboard.writeText`).
*   **Vanilla JavaScript:** All logic is handled with plain JavaScript for maximum performance and simplicity.
