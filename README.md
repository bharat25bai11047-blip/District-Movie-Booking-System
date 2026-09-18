<div align="center">
  <h1>🎬 District Movie Booking System</h1>
  <p><strong>A robust, console-based Java application that simulates the experience of booking movie tickets in a modern district cinema.</strong></p>
  
  <p>
    <img src="https://img.shields.io/badge/Java-17+-orange?style=for-the-badge&logo=java" alt="Java 17+" />
    <img src="https://img.shields.io/badge/Architecture-MVC-blue?style=for-the-badge" alt="Architecture MVC" />
    <img src="https://img.shields.io/badge/Interface-CLI-darkgreen?style=for-the-badge" alt="CLI" />
  </p>
</div>

<br />

## 📖 Overview
The **District Movie Booking System** provides two distinct portals: 
* 🧑‍💻 **User Portal**: Browse movies, select seats via a visual seat map, order snacks, and book tickets.
* 👨‍💼 **Admin Portal**: Manage the movie catalogue, schedule shows, and view real-time revenue analytics.

Built without any external dependencies, this system utilizes core Java principles (OOP, Collections, Streams) to deliver a seamless and complete ticket-booking lifecycle entirely in memory.

---

## ✨ Features

### 🍿 User Portal
* 🎥 **Browse Movies & Shows**: View currently playing movies and their scheduled timings across different screens.
* 💺 **Visual Seat Selection**: Interactive tiered seating layout (*VIP, Premium, Executive, Normal*) with real-time availability tracking.
* 🍔 **Snack Bar**: Order add-on snacks (Popcorn, Nachos, Beverages) during the booking process.
* 🎟️ **Promo Codes**: Apply permanent discount codes (e.g., `WELCOME10`) or earn single-use bulk reward codes for booking 5+ seats.
* 🧾 **Detailed Billing**: Automatic calculation of seat totals, snack totals, discounts, 18% GST, and convenience fees.
* 💳 **Ticket Wallet & Cancellation**: View active tickets in your wallet or cancel them for a full refund (automatically freeing up seats and revoking used promo codes).

### ⚙️ Admin Portal
* 📊 **Revenue Analytics**: View per-movie, per-show ticket sales, revenue generation, and grand platform totals.
* 🎬 **Catalogue Management**: Dynamically add new movies or schedule new shows on specific screens.
* 🗑️ **Cascade Deletion**: Removing a movie automatically deletes its scheduled shows and revokes all booked tickets for those shows.

---

## 🛠️ Technologies & Architecture

* **Language**: Java 17 (JDK 17+)
* **Core Concepts**: Object-Oriented Programming (OOP), Collections Framework (List, Set, Map), Enums, Lambda Expressions, Stream API, UUID generation.
* **Architecture**: Layered design with distinct Separation of Concerns (*Presentation, Business Logic, and Data*).
* **Storage**: In-memory collections (`HashMap`, `ArrayList`) ensuring zero-dependency, ultra-fast execution.

---

## 🚀 Quick Start

### Prerequisites
Ensure you have Java (JDK 17 or higher) installed on your system. 
```bash
java -version
