# Dialogica AI Landing Page

Welcome to the repository for the Dialogica AI landing page! This project contains the source code for a static landing page showcasing Dialogica AI's capabilities, features, and contact information.

## Project Structure

- `public/`: Compiled files ready to be served by a web server. Includes HTML, CSS, JavaScript, and assets such as images.
- `src/`: Source files including components, layouts, styles, and scripts that are processed by the static site generator.
- `src/pages/`: Markdown and template files for the website's content.
- `.git/`: Git version control system directory.
- `package.json`: Node.js project manifest with project dependencies.
- `ssg.config.yml`: Configuration file for the static site generator.

## Getting Started

### Prerequisites

- Node.js (version specified in `package.json`)
- A package manager (npm or yarn)

### Installation

1. Clone the repository to your local machine:
2. Navigate to the project directory:
3. Install dependencies:

### Local Development

To run the website locally for development purposes:

This command will start a local development server and open the website in your default browser. Changes to the source files will automatically rebuild the site and refresh the page.

### Building for Production

To compile the source files into static files ready for production:

The static files will be generated in the `public/` directory.

## Deployment

Deploy the contents of the `public/` directory to your static hosting service of choice (e.g., Netlify, Vercel, GitHub Pages).

