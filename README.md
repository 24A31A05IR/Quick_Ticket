# QuickTicket – Ticket Booking Portal

QuickTicket is a modern, responsive single-page web application (SPA) designed for seamless ticket bookings across multiple services including Buses, Movies, and Trains. It features a high-end dark-themed UI with glassmorphism effects, integrated logic for dynamic pricing, and a simulated authentication system.

Live Demo:https://24a31a05ir.github.io/Quick_Ticket/

## 🚀 Features

### 1. Authentication System
* **Simulated OTP Login**: A realistic login flow where users enter their name and phone number to receive a 6-digit demo OTP.
* **Session Management**: Uses `localStorage` to maintain user sessions and personalized greetings.

### 2. Booking Engines
* **🚌 Bus Booking**:
    * Route selection across major Indian cities.
    * Multiple bus types (Ordinary, AC, Volvo Sleeper, Luxury).
    * Automated 10% discount logic using the promo code **BUSGO**.
* **🎬 Movie Booking**:
    * Dynamic seat selection grid with real-time price updates.
    * Automatic "Free Popcorn" reward logic for bookings of 2 or more seats.
    * Selection of latest blockbusters and popular theatre chains.
* **🚂 Train Booking**:
    * PNR-style booking system with source and destination selection.
    * Automatic 5% "Weekend Saver" discount based on the selected journey date.
    * Support for multiple travel classes (General to 1 Tier AC).

### 3. User Dashboard & History
* **Personalized Insights**: Displays total booking counts and recent activity.
* **Booking History**: A dedicated section to view past confirmed tickets with unique reference IDs.
* **Profile Management**: View account details and membership status.

### 4. UI/UX Design
* **Modern Aesthetics**: Dark-mode interface using 'Syne' and 'DM Sans' typography.
* **Responsive Layout**: Fully optimized for Mobile, Tablet, and Desktop views.
* **Interactive Elements**: Smooth page transitions, toast notifications, and interactive modals.

## 🛠️ Technology Stack
* **HTML5**: Semantic structure for high accessibility.
* **CSS3**: Custom properties (variables), Flexbox, Grid, and advanced animations.
* **JavaScript (ES6+)**: Vanilla JS for DOM manipulation, state management (SPA routing), and logic.

## 📂 Project Structure
The project is contained within a single `code.html` file for ease of portability:
* `<style>`: Contains all design tokens, UI components, and responsive media queries.
* `<body>`: Divided into functional sections (pages) that toggle visibility via the JavaScript router.
* `<script>`: Handles authentication, price calculations, seat mapping, and local storage persistence.

## 📖 How to Run
1. Save the source code as `index.html`.
2. Open the file in any modern web browser (Chrome, Firefox, Safari, Edge).
3. No server-side setup or external database is required as it utilizes browser storage.

---
*Developed as a high-performance frontend prototype for travel and entertainment management.*
