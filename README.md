# JSON Formatter and Validator

A sleek, browser-based tool for validating, formatting, and manipulating JSON data with real-time syntax highlighting.

## Features

- **JSON Validation** - Instantly validate your JSON and get detailed error messages
- **Intelligent Error Detection** - Identifies the exact line and position of syntax errors
- **Pretty Formatting** - Format JSON with proper indentation for better readability
- **Syntax Highlighting** - Real-time highlighting of JSON syntax elements
- **Line Numbers** - Visual reference with line numbers for easier navigation
- **Error Highlighting** - Visually highlights the line where errors occur
- **Compress JSON** - Minify JSON by removing all whitespace
- **Copy to Clipboard** - One-click copying of the formatted/validated JSON
- **Responsive Design** - Works well on both desktop and mobile devices

## Usage

### Online Version

Visit the online version at [https://t.sys.re/json/](https://t.sys.re/json/)

### Local Installation

1. Clone the repository:
   ```
   git clone https://github.com/nilicule/jsonValidate.git
   ```

2. Open `index.html` in your web browser.

That's it! No build process or dependencies required.

### How to Use

1. **Paste JSON**: Paste your JSON data into the text area.
2. **Validate & Format**: Click the "Validate & Format JSON" button to check for errors and format your JSON with proper indentation.
3. **View Errors**: If there are any errors, they will be displayed with detailed information about the location and nature of the error.
4. **Compress**: Click "Compress" to minify your JSON by removing all whitespace.
5. **Copy**: Click "Copy to Clipboard" to copy the current JSON to your clipboard.
6. **Clear**: Click "Clear" to reset the editor.

## Error Handling

The tool provides detailed error information when your JSON is invalid:

- Highlights the exact line where the error occurs
- Shows a pointer (^) to the exact position in the line
- Provides a descriptive error message
- Intelligently detects when errors are likely caused by issues on previous lines

## Technical Details

This project is built with pure HTML, CSS, and JavaScript - no dependencies required. Key features include:

- Custom syntax highlighting engine
- Error position detection and visualization
- Responsive design with a dark theme inspired by the Dracula color palette
- Line number tracking and synchronization with scroll position
- Error line highlighting

## Browser Compatibility

The JSON Formatter and Validator works with all modern browsers:

- Chrome
- Firefox
- Safari
- Edge

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## Acknowledgments

- Inspired by the need for a simple, dependency-free JSON validation tool
- Color scheme inspired by the Dracula theme