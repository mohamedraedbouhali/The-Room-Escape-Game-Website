# The Room Escape Game Website

A modern multi-page style website for an escape game business in Tunis, including a player-facing booking experience and an admin dashboard.

## Overview

This project is a front-end website built with HTML, CSS, and vanilla JavaScript.

The public site includes:

- A cinematic home page with immersive visuals
- Scenario browsing (6 escape room themes)
- Detailed scenario pages with difficulty, player range, and success rate
- Pricing section by team size
- Booking flow with date/time slots and a reservation modal
- Contact and location information with Google Maps integration
- Multilingual interface (French, English, Arabic with RTL support)

The admin side includes:

- Secure login screen
- Reservation management
- Admin account management
- Waiver and KPI/report views
- PDF report export support (jsPDF)

## Tech Stack

- HTML5
- CSS3 (custom responsive styling)
- Vanilla JavaScript
- Browser localStorage for client-side data persistence

## Project Structure

- `index.html`: Main public website (home, scenarios, pricing, booking, contact)
- `admin.html`: Admin dashboard and management interface
- `img/`: Visual assets used by the website

## How to Run Locally

1. Clone or download this repository.
2. Open `index.html` in your browser for the public website.
3. Open `admin.html` in your browser for the admin dashboard.

Because this is a static project, no package installation or build step is required.

## Admin Access (Default)

- Email: admin@gmail.com
- Password: admin

Use these credentials only for local/demo usage and change them for production scenarios.

## Notes

- Reservation and admin data are stored in the browser (localStorage).
- For production deployment, move authentication and booking storage to a secure backend.

## License

This project is currently shared without an explicit license.
<<<<<<< HEAD
Add a license file (for example, MIT) if you plan to make it publicly reusable.
=======
Add a license file (for example, MIT) if you plan to make it publicly reusable.
>>>>>>> 258ae6e ( 2  push)
