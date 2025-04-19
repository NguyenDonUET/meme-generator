# Meme Generator

The Meme Generator is a fun and interactive web application that allows users to **create custom memes** by adding text to images. This project is built using Vanilla JavaScript and leverages modern web development tools like Vite for a fast and efficient development experience.

## Project Structure

- `index.html`: The main HTML file for the application.
- `main.js`: The primary JavaScript file containing the app logic.
- `vite.config.js`: Configuration file for Vite.
- `assets/`: Contains stylesheets and other static assets.
- `src/`: Contains modular JavaScript files for specific functionalities:
  - `camera.js`: Handles camera-related features.
  - `modal.js`: Manages modal interactions.
  - `text.js`: Handles text input and rendering.
  - `theme.js`: Manages theme switching.

## Getting Started

### Prerequisites

- Node.js and npm installed on your system.

### Installation

1. Clone the repository:

```bash
git clone <repository-url>
```

2. Navigate to the project directory:

```bash
cd meme-generator
```

3. Install dependencies:

```bash
npm install
```

4. Running the Project

- Start the development server:

```bash
npm run dev
```

- Open your browser and navigate to http://localhost:3000 to view the application.

5. Building for Production

- To build the project for production:
- The output will be in the `dist/` directory.
