
# Markdown Previewer

A simple React app that allows users to write and preview markdown content. The app converts markdown input to HTML using the `marked` library and displays it in real time. [TRY NOW!](https://codepen.io/Riki-A/pen/xxvBrXz)

## Features

- Live preview of markdown content.
- Handles different markdown elements like headers, lists, code blocks, images, and links.
- Easy-to-use text area for writing markdown.
- Real-time conversion to HTML using `marked`.

## Technologies Used

- **React**: A JavaScript library for building user interfaces.
- **marked**: A markdown parser used to convert markdown into HTML.
- **CSS**: For styling and layout.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/markdown-previewer.git
   ```
2. Navigate into the project directory:
   ```bash
   cd markdown-previewer
   ```
3. Install the dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm start
   ```

The app will be running on [http://localhost:3000](http://localhost:3000).

## How to Use

1. Write markdown content in the editor on the left side.
2. See the live preview of the markdown on the right side as it is parsed into HTML.
3. The markdown syntax supports headers, links, code blocks, blockquotes, and images.

## Code Structure

- `src/index.js`: The entry point where the React app is rendered.
- `src/App.js`: The main parent component that contains the `Markdown` component.
- `src/Markdown.js`: The component that handles markdown input and preview rendering.
- `src/index.css`: Contains styles for the app's layout, including responsive design for different screen sizes.

## License

This project is licensed under the MIT License.
