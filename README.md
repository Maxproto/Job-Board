# Job Board Application

This project is a simple React-based web application that allows users to post job listings, edit them, and view all job opportunities in one place. Utilizing a json-server for mock backend functionality, this application simulates full-stack capabilities in a development environment.

## Project Structure

Below is a high-level overview of the project's directory structure:

- `dist/`: The production build of the application after running `npm run build`.
- `node_modules/`: Contains all the npm packages that the project depends on.
- `public/`: Static assets that are used by the application.
- `src/`: Source code of the application.
  - `assets/`: Static files like images or shared data.
  - `components/`: React components used throughout the application.
  - `layouts/`: Components that dictate the overall layout of the application.
  - `pages/`: Components representing individual pages of the application.
- `package.json`: Defines the project dependencies and build scripts.
- `README.md`: Documentation of the project (this file).

## Getting Started

To get the application running locally on your machine, follow these steps:

1. Clone the repository to your local machine.
2. Install the dependencies with `npm install`.
3. Start the json-server with `npm run server`.
4. In a separate terminal, launch the application using `npm run dev` for development mode.
5. To view the production version locally, first create a production build with `npm run build` and then serve it with `npm run preview`.
