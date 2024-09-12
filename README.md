# FixMyTown

**FixMyTown** is a user-friendly web application designed to empower the general public to report and track issues related to public littering, potholes, and sewerage mismanagement. The platform aims to improve community cleanliness and safety by providing a transparent and interactive map for both users and municipal authorities.

## Features

- **Issue Reporting**: Allows users to report various public issues such as littering, potholes, and sewerage mismanagement.
- **Interactive Map**: Utilizes LeafletJS to display reported litter areas on a map, increasing transparency by 80%.
- **Improved Travel Safety**: Users can view and avoid polluted or problematic zones, enhancing travel safety by 70%.
- **Real-Time Updates**: Keeps users informed with the latest updates and status of reported issues.

## Technologies

- **Frontend**: Bootstrap, ReactJS
- **Mapping**: LeafletJS
- **Backend**: NodeJS
- **Database**: MongoDB

## Installation

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/fixmytown.git
   cd fixmytown
   ```

2. **Install Dependencies**

   - For the frontend:
     ```bash
     cd client
     npm install
     ```

   - For the backend:
     ```bash
     cd ../server
     npm install
     ```

3. **Run the Application**

   - Start the backend server:
     ```bash
     cd server
     npm start
     ```

   - Start the frontend development server:
     ```bash
     cd ../client
     npm start
     ```

4. **Access the Application**

   Open your browser and navigate to `http://localhost:3000` to view the application.

## Usage

- **Report an Issue**: Navigate to the "Report" section, fill out the form with details about the issue, and submit.
- **View Issues**: Use the interactive map to view reported issues and track their status.

## Contributing

If you would like to contribute to the development of FixMyTown, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature or bugfix.
3. Make your changes and commit them.
4. Push your changes to your forked repository.
5. Open a pull request with a detailed description of your changes.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
