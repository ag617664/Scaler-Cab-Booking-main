
# Cab System Web Application

The Cab System is a web application designed to streamline cab booking processes, offering users optimal routes and estimated costs for their trips. This README offers a comprehensive outline of the project, its functionalities, and instructions for setup and usage.

## 1. Description

The Cab System is a web-based platform allowing users to reserve cabs while computing the shortest possible duration and estimated expenses for their journeys.

## 2. Features

### Cab Booking

- Users have the option to reserve cabs by furnishing their email addresses, along with specifying both the pickup and drop-off locations.

### Shortest Route Calculation

- The system computes the most efficient travel time from the pickup point to the destination, taking into account various available routes.

### Cab Management

- The system oversees a fleet of five cabs, each with distinct pricing structures, ensuring that there are no overlaps in the start and end times of two cabs.

### Estimated Cost

- Users are provided with an estimated cost for their cab rides, determined by the selected cab and the duration taken to reach the drop-off location.

### Cab Confirmation Email

-  Users are promptly notified via email at the time of booking, receiving comprehensive details regarding their reservation.

### Edit Bookings

-Users have the ability to modify their bookings by adjusting the pickup and drop-off locations, as well as selecting a different cab if needed.

### Cancel Booking

-Users can cancel their bookings, which transitions their booking status to archived.

### Booking Tracking

- Users can view and track their cab bookings within the system.

### Responsive Design

- The application is designed to be responsive, adapting to different screen sizes and devices.

### Admin Access

- The application assumes that only administrators will access it.



## 3. Assumptions

- The application is designed for use by administrators; no user login/signup pages are required.

## 4. Project Setup

To set up and run the Cab System web application, follow these steps:

1. Clone the project from the repository:
   ```
   git clone https://github.com/ag617664/Scaler-Cab-Booking-main
   ```

2. Navigate to the project directory:
   ```
   cd SCALER CAB BOOKING
   ```

## Server

1. Navigate to the server directory:
   ```
   cd server
   ```

2. Install the required dependencies:
   ```
   npm install
   ```

3. Start the application:
   ```
   npm run dev
   ```
4. The server should now be running on your local server `http://localhost:9095`.

## Client

1. Navigate to the client directory:
   ```
   cd client
   ```

2. Install the required dependencies:
   ```
   npm install
   ```

3. Start the application:
   ```
   npm start
   ```

4. The client should now be running on your local server. 
Open your web browser and access it at `http://localhost:3000`.

## 5. Technologies Used

The Cab System web application is built using the following technologies:

- Frontend:
  - React: A JavaScript library for building user interfaces.
  - Axios: A promise-based HTTP client for making requests to the backend API.
  - Tailwind CSS: A CSS framework

- Backend:
  - Node.js: A JavaScript runtime for the server.
  - Express: A web application framework for Node.js.
  - MongoDB: A NoSQL database for data storage.
 



<img width="1440" alt="Screenshot 2024-04-03 at 6 15 35 PM" src="https://github.com/ag617664/Scaler-Cab-Booking-main/assets/95614809/492ac50d-3de1-4f8a-b0b7-d34390fb3a07">

<img width="1440" alt="Screenshot 2024-04-03 at 6 19 27 PM" src="https://github.com/ag617664/Scaler-Cab-Booking-main/assets/95614809/b8b0ec28-4d39-401b-a2ab-049654993a22">

<img width="1440" alt="Screenshot 2024-04-03 at 6 19 34 PM" src="https://github.com/ag617664/Scaler-Cab-Booking-main/assets/95614809/41ebdee2-7694-42fd-91cd-056121dd2c53">
<img width="1440" alt="Screenshot 2024-04-03 at 6 19 40 PM" src="https://github.com/ag617664/Scaler-Cab-Booking-main/assets/95614809/b9cc9a80-77a4-4a55-bf51-76938b329c0e">
<img width="1440" alt="Screenshot 2024-04-03 at 6 19 55 PM" src="https://github.com/ag617664/Scaler-Cab-Booking-main/assets/95614809/f4c2e458-7824-4419-8a45-35214082b4ef">
