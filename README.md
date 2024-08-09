# Random Activity Generator

This project uses Express.js and Axios to fetch random activities from the Bored API and display them on a web page. Users can also filter activities based on type and number of participants.

## Prerequisites

Before you begin, ensure you have the following installed:
- Node.js
- npm (Node Package Manager)

## Installation

1. Clone the repository:

   ```bash
   git clone <repository-url>
   cd <repository-folder>
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Start the server:

   ```bash
   npm start
   ```

4. Open your web browser and go to `http://localhost:3000` to view the application.

## Usage

- **Home Page**: Visiting the root URL (`/`) displays a random activity fetched from the Bored API.
- **Filtering**: You can filter activities by type and number of participants using the dropdowns provided.
- **Error Handling**: If no activities match the filter criteria, an appropriate message is displayed.

## API Used

This project uses the [Bored API](https://bored-api.appbrewery.com/) to fetch random activities.

## Technologies Used

- Express.js
- Axios
- Body-parser
- EJS (Embedded JavaScript templates)

## Contributing

Feel free to fork the repository and submit pull requests.
