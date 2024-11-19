# Asset Tracking Application

This is a web application built using NestJS for the backend and React with Vite for the frontend. It allows users to track and monitor the prices of different assets.

## Backend (NestJS and PostgreSQL)

The backend of the application is built using the NestJS framework and PostgreSQL as the database.

### Prerequisites

- [Node.js](https://nodejs.org/) (version 14 or higher)
- [PostgreSQL](https://www.postgresql.org/) (version 12 or higher)

### Installation

1. Clone the repository:
```
git clone https://github.com/your-username/asset-tracking-app.git
```

2. Navigate to the `backend` directory:
```
cd asset-tracking-app/backend
```

3. Install the dependencies:
```
npm i 
```

4. Configure the PostgreSQL database connection in the `backend/ormconfig.json` file.

## Running the Application

1. Start the NestJS server:

```
npm run start:dev --prefix backend
``` 

2. Start the Vite development server:
```
npm run dev --prefix frontend
```

The application should now be running, and you can access it in your browser at `http://localhost:3000`.

## Features

- Search for assets by ticker symbol
- Display a table of asset information (ticker, date, entry price, actual price, percentage change)
- Visualize the portfolio breakdown using a pie chart
- (Optional) Implement user authentication and authorization

## Screenshots

![Asset Tracking Application Screenshot](screenshot.png)

## Contributing

If you find any issues or have suggestions for improvements, feel free to open a new issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).
