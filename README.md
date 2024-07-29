# La Sorgente Hotel - Website

Welcome to the repository of "La Sorgente" hotel website! This site is designed to provide information about the hotel, its services, rooms, and to allow users to make online reservations.

## Contents

- [Description](#description)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Installation and Setup](#installation-and-setup)
- [Usage](#usage)
- [Contact](#contact)

## Description

La Sorgente is a luxury hotel located in Iguazú, Argentina. This website provides detailed information about the hotel, including its rooms, services, and location. Additionally, visitors can make online reservations through a secure system.

## Features

- Detailed information about the hotel and its services.
- Online reservation system.
- Image gallery.
- Contact section with a form for inquiries.
- Responsive design for both mobile and desktop devices.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript, React.js
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Others**: Bootstrap

## Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/marina-nh/la-sorgente-hotel.git
   ```

2. **Navigate to the project directory**:
   ```bash
   cd la-sorgente-hotel
   ```

3. **Install frontend dependencies**:
   ```bash
   cd frontend
   npm install
   ```

4. **Install backend dependencies**:
   ```bash
   cd ../backend
   npm install
   ```

5. **Set up environment variables**:
   Create a `.env` file in the root of the project with the following variables:
   ```
   DATABASE_URL=mongodb+srv://username:password@cluster.mongodb.net/la-sorgente
   PORT=3000
   ```

6. **Start the development server**:
   - Frontend:
     ```bash
     cd frontend
     npm start
     ```
   - Backend:
     ```bash
     cd ../backend
     npm start
     ```

## Usage

Once the application is running, you can access the website at `http://localhost:3000`. From there, you can navigate through the different sections of the site, view information about the hotel, rooms, and make reservations.

## Contributions

Contributions are welcome! If you want to contribute to this project, please follow these steps:

1. Fork the repository.
2. Create a branch for your feature or bug fix (`git checkout -b branch-name`).
3. Make your changes and commit them (`git commit -am 'Description of changes'`).
4. Push to the branch (`git push origin branch-name`).
5. Open a Pull Request.

## Contact

If you have any questions or need more information, feel free to contact us via [email](mailto:contact@marinanunez.tech).
