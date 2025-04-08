# Markdown Editor

This is a simple and functional Markdown editor developed with HTML, CSS, JavaScript, and the **Showdown** library for converting Markdown to HTML. The editor features an intuitive interface to make editing and previewing Markdown documents easy. It has also been developed as a desktop application using **Electron**.

## Features

**Markdown Editing**: Allows users to create and edit Markdown files directly in the browser or in an Electron-based desktop app.

**Live Preview**: The Markdown content preview updates instantly as the user types.

**Text Formatting:**

- **Bold**: Ctrl+B  
- **Italic**: Ctrl+I  
- **Headings**: Insert H1 and H2 headings  
- **Lists**: Create ordered and unordered lists  
- **Blockquotes**: Insert block quotes  
- **Code Blocks**: Insert code blocks  
- **Links and Images**: Easy interface to add links and images using URLs  

**Dark Mode**: Toggle between light and dark themes for a better user experience.

**Save & Load Files**: Save Markdown content locally or load existing `.md` files.

## Installation

To install and run this editor on your machine, follow these steps:

**Prerequisites**

Make sure [Node.js](https://nodejs.org/) (version 14 or higher) is installed on your system.

**Steps**

* Clone the repository:

```bash
git clone https://github.com/andersonmoegel/Editor-de-Markdown.git
cd editor-markdown
```

* Install project dependencies:

```bash
npm install
```

* Run the Electron app:

```bash
npm start
```

This will open the Markdown editor in an Electron app window.

## How to Use

**Text Editing**: Write your content in the editor area.

**Text Formatting**: Select text and use the toolbar buttons to apply formatting.

**Preview Content**: The Markdown preview updates in real-time as you type.

**Save Markdown**: Click the save icon to download the Markdown file.

**Load Markdown**: Click the open icon to load an existing Markdown file.

## Additional Functionality

The editor content is automatically saved to the browser's `localStorage` for session persistence.

Dark mode can be toggled on or off using the button in the top-right corner.

## Technologies Used

**Electron**: Framework for building cross-platform desktop apps with web technologies.

**Showdown.js**: Library to convert Markdown into HTML.

**HTML & CSS**: Used to design the user interface.

**JavaScript**: Manages app logic and event handling.

## License

This project is licensed under the MIT License.
