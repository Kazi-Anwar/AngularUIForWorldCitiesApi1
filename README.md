
# Angular UI for World Cities API

This repository contains an Angular application designed to interact with a World Cities API. The app provides a user-friendly interface for searching, displaying, and managing information about cities around the world.

## Features

- **City Search**: Search for cities by name.
- **City Details**: View detailed information about selected cities.
- **Responsive Design**: User-friendly and responsive interface built with Angular.
- **API Integration**: Fetches city data from an external World Cities API.

## Technologies Used

- **Angular**: Framework for building dynamic and single-page applications.
- **Bootstrap**: For responsive and modern UI design.
- **HttpClient**: Angular service for making HTTP requests.
- **RxJS**: For handling asynchronous operations and reactive programming.

## Getting Started

### Prerequisites

- **Node.js**: Ensure you have Node.js installed. You can download it from [nodejs.org](https://nodejs.org/).
- **npm**: Node Package Manager, included with Node.js.

### Installation

1. **Clone the Repository**

   ```sh
   git clone https://github.com/Kazi-Anwar/AngularUIForWorldCitiesApi1.git
   ```

2. **Navigate to the Project Directory**

   ```sh
   cd AngularUIForWorldCitiesApi1
   ```

3. **Install Dependencies**

   Install the necessary packages using npm:

   ```sh
   npm install
   ```

4. **Run the Application**

   Start the Angular development server:

   ```sh
   npm start
   ```

   The application will be available at `http://localhost:4200` in your web browser.

## Usage

- **Search for Cities**: Use the search bar to find cities by name.
- **View Details**: Click on a city to view detailed information.
- **Navigate**: Use the navigation components to explore different views and features of the application.

## Project Structure

- **`src/`**: Contains the source code for the Angular application.
  - **`app/`**: Main application code.
    - **`components/`**: Angular components used throughout the application.
    - **`services/`**: Angular services for API interaction and data management.
    - **`app.module.ts`**: Main Angular module.
    - **`app.component.ts`**: Root component of the application.
  - **`assets/`**: Contains static assets such as images and styles.
  - **`environments/`**: Configuration files for different environments.
- **`angular.json`**: Angular CLI configuration file.
- **`package.json`**: Lists project dependencies and scripts.
- **`tsconfig.json`**: TypeScript configuration file.

## API Integration

The application interacts with an external World Cities API. Ensure the API endpoint is correctly configured in the service files for fetching city data.

## Contributing

Contributions to this project are welcome. Please follow these steps to contribute:

1. **Fork the Repository**
2. **Create a New Branch**
3. **Make Your Changes**
4. **Commit Your Changes**
5. **Push to Your Fork**
6. **Open a Pull Request**

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.

## Contact

For any questions or issues, please [contact me on GitHub](https://github.com/Kazi-Anwar).

