# earthgen

An earth-like planet generator

## Description

earthgen is a ClojureScript application that generates and visualizes earth-like planets. It uses various algorithms to create realistic terrain, including continents, oceans, and other geographical features.

## Installation

1. Make sure you have [Node.js](https://nodejs.org/) and [Clojure](https://clojure.org/guides/getting_started) installed on your system.

2. Clone the repository:
   ```
   git clone https://github.com/yourusername/earthgen.git
   cd earthgen
   ```

3. Install the dependencies:
   ```
   npm install
   ```

## Running the Application

To run the application in development mode:
    ```
    npm run release
    ```


This will start a development server. Open your browser and navigate to `http://localhost:8280` to view the application.

## Building for Production

To create a production build:
    ```
    npm run release
    ```


The compiled files will be in the `resources/public/js/compiled` directory.

## Project Structure

- `src/earthgen/`: Contains the main ClojureScript source files
- `resources/public/`: Contains the HTML and other static assets
- `test/`: Contains test files (if any)

## Technologies Used

- ClojureScript
- Reagent (React wrapper for ClojureScript)
- re-frame (Application framework for Reagent)
- shadow-cljs (ClojureScript build tool)
- WebGL (for 3D rendering)

## License

[Add your license information here]