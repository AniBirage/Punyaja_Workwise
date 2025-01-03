## Project files submitted using my brother's account due to some issues in my Github accout

# Seat Booking

## Video Walkthrough of the project
https://www.loom.com/share/713df6aff3524d91a610402655633500?sid=3055b4a7-5076-46d5-9ac4-2c58bced971f

## Problem Description:
- There are 80 seats in a train with only 7 seats in a row and the last row of only 3
seats. For simplicity, there is only one coach in this train.
- One person can reserve up to 7 seats at a time.
- If a person is reserving seats, the priority will be to book them in one row.
- If seats are not available in one row then the booking should be done in such a way
that the nearby seats are booked.
- Users can book as many tickets as s/he wants until the coach is full.
- User login and signup
- If one user books a seat, no other user can reserve that seat until the booking is
canceled or reset

## Tech Stack
- React js
- Node js
- Express js
- MongoDB

## Screenshot
<img src="![Screenshot (4)](https://github.com/user-attachments/assets/f876817c-d542-4609-83d1-3648d95e4982)
" />

## Backend Installation
- clone repo
- cd backend
- npm install
- node index.js

## Frontend Installation
- clone repo
- cd frontend
- npm install
- npm start

## API Endpoints
- https://seat-booking-tg8y.onrender.com
- GET /api/seats - get all seats
- POST /api/seats - reset all seats booking
- POST /api/seats/book - book n seats
  
