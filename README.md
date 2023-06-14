# Inventory- Management System with React

This is a  Inventory- Management System  app built with React that allows users to visualize sales data and manage suppliers. The app provides various charts and reports to analyze sales information and includes a feature to add new suppliers.

## Features

- Generate sales charts per type
- Visualize dispatch data using bar charts
- Generate sales reports with detailed information
- View sales per type in a tabular format
- Add new suppliers with their contact details

## Installation

1. Clone the repository: `git clone https://github.com/your-username/dashboard-app.git`
2. Navigate to the project directory: `cd dashboard-app`
3. Install the dependencies: `npm install`

## Usage

1. Run the app: `npm start`
2. Open your web browser and visit `http://localhost:3000` to access the app.

## Technologies Used

- React
- Redux Toolkit
- Chart.js
- Bootstrap

## File Structure

```
├── src
│   ├── components
│   │   ├── Dashboard.js
│   │   └── ...
│   ├── features
│   │   ├── users
│   │   │   └── userSlice.js
│   │   └── ...
│   ├── services
│   │   ├── api.js
│   │   └── axiosBase.js
│   ├── styles
│   │   ├── item.css
│   │   └── ...
│   ├── App.js
│   └── index.js
├── .gitignore
├── package.json
├── README.md
└── ...
```

## API Endpoints

- `GET /users` - Retrieve all users
- `POST /user` - Create a new user
- `POST /user/{id}` - Update a user
- `POST /user/{id}` - Delete a user

## Contributing

Contributions are welcome! If you'd like to add new features, fix bugs, or improve the app, please follow these steps:

1. Fork the repository
2. Create a new branch: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m 'Add feature'`
4. Push to the branch: `git push origin feature-name`
5. Submit a pull request


## Contact

For any questions or inquiries, please email jayaprakashshrestha15@gmail.com

Feel free to customize and modify the content according to your project's needs. Additionally, make sure to include appropriate links, references, and contact information specific to your project.
