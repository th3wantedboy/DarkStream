# DarkStream
DarkStream is a web application that allows users to upload files, convert them to Base64-encoded data URLs, and copy the result to the clipboard. It provides a simple, efficient way to handle file encoding locally, without the need for an internet connection.

![DarkStream](https://i.ibb.co/fxMmKP1/Screenshot-2024-07-26-at-16-48-53-Dark-Stream.png)

## Features

- **File Upload**: Allows users to upload files from their local system.
- **Base64 Encoding**: Converts the uploaded file into a Base64 data URI format.
- **Copy to Clipboard**: Provides an easy way to copy the Base64 encoded string to the clipboard.
- **Responsive Design**: Ensures compatibility with various device sizes and screen resolutions.

## Installation

To use DarkStream, you don’t need any special setup. Simply clone this repository and open the `index.html` file in your web browser.

### Cloning the Repository

```
git clone https://github.com/th3wantedboy/DarkStream.git
```
```
cd DarkStream
```

## Open in Browser

Open the `index.html` file using your preferred web browser.

## Usage

1. **Upload a File**: Click the "Choose File" button and select the file you wish to encode.
2. **Convert**: Click the "Upload and Convert" button to generate the Base64 encoded string.
3. **Copy**: Click the "Copy to Clipboard" button to copy the encoded string to your clipboard.

## Code Overview

### HTML (`index.html`)

The HTML file contains the structure of the DarkStream tool. It includes:
- A file input for selecting files.
- Buttons for uploading and copying the encoded string.
- A textarea to display the Base64 encoded string.

### CSS

The CSS styles the tool ensuring it is visually appealing and functional across different devices. Key styles include:
- Background and text colors.
- Layout and positioning using flexbox.
- Responsive adjustments for smaller screens.

### JavaScript

The JavaScript file handles:
- File reading and encoding using the `FileReader` API.
- Copying the encoded string to the clipboard using `document.execCommand`.

## Development

To make modifications or improvements:
- **HTML**: Edit the structure and content in `index.html`.
- **CSS**: Update styles in the `<style>` section of `index.html` or move to an external CSS file.
- **JavaScript**: Modify functionality in the `<script>` section of `index.html`.

## Contributing

Contributions are welcome! If you encounter any issues or have suggestions for enhancements:
- Open an issue on GitHub.
- Submit a pull request with your changes.



## Contact

For any questions or inquiries, reach out to [th3wantedboy](http://t.me/th3wantedboy).

