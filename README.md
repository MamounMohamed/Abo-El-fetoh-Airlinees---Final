# Flight Booking Web Application

This project is a simple web application designed for booking flights. Users can search for available flights, select their desired flight, and complete the booking process. The backend API is built with Express.js and PostgreSQL, while the frontend is developed using HTML, CSS, Bootstrap, and vanilla JavaScript.

## Project Structure
```bash
API/
├── migrations/
│ ├── 20220518150508-Person.js
│ ├── 20220518150514-Airline.js
│ ├── 20220518150528-Trips.js
│ ├── 20220518150536-Airplane.js
│ ├── 20220518150541-Flight.js
│ └── sqls/
│ ├── up/
│ │ └── {build scripts for every table}
│ └── down/
│ └── {drop scripts for every table}
└── src/
├── handlers/
│ ├── airLineHandler.js
│ ├── tripsHandler.js
│ └── userHandler.js
├── middleware/
│ └── verifyToken.js
├── models/
│ ├── airline.js
│ ├── trip.js
│ ├── users.js
├── app.js
└── database.js

Frontend/
├── images/
├── scripts/
│ ├── auth.js
│ ├── booking.js
│ └── signup.js
├── styles/
└── *.html files
```
## Technologies Used

- **Backend:**
  - Express.js
  - PostgreSQL
- **Frontend:**
  - HTML
  - CSS
  - Bootstrap
  - Vanilla JavaScript

## Credits 
    -[Mamoun Mohamed](https://github.com/MamounMohamed)
    -[Arsany Milad] (https://github.com/aroo530)



