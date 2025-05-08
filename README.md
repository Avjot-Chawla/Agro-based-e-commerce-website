# Agro-Based E-Commerce Website

A modern, scalable, and inclusive online marketplace designed to connect farmers, vendors, and consumers directly. This platform eliminates middlemen, ensures fair pricing, and promotes sustainable agricultural practices through innovative features like AI recommendations, real-time logistics, and multilingual accessibility.

## Table of Contents

* [Overview](#overview)
* [Features](#features)
* [Technologies Used](#technologies-used)
* [Installation and Setup](#installation-and-setup)
* [Database Setup](#database-setup)
* [Usage](#usage)
* [Project Structure](#project-structure)
* [Contributing](#contributing)
* [Authors and Acknowledgements](#authors-and-acknowledgements)

## Overview

The **Agro-Based E-Commerce Website** aims to revolutionize the agri-value chain by:

* Providing **farmers** with a direct sales platform to reach a broader market.
* Offering **consumers** fresh, traceable produce at fair prices.
* Empowering **vendors** to participate in a transparent, data-driven ecosystem.

The platform supports seasonal and sustainable eating, reduces food waste, and enhances rural livelihoods. It is aligned with UN Sustainable Development Goals to foster an inclusive, resilient, and eco-friendly food distribution network.

## Features

* **Farmer Module**

  * Farmer registration, product listing, and pricing control.
  * Escrow-based payout system and analytics for performance tracking.

* **Consumer Module**

  * Product browsing, personalized suggestions, and secure checkout.
  * GPS-enabled order tracking and delivery ETA visibility.

* **Vendor/Delivery Partner Module**

  * Delivery assignment dashboard and real-time logistics updates.
  * Payment schedules and ratings system.

* **Admin Module**

  * Dashboard for managing users, products, logistics, and disputes.
  * Analytics tools to monitor market trends, sales, and user behavior.

* **Intelligent Features**

  * AI-based recommendation engine for product suggestions.
  * Multilingual, mobile-first UI with interactive tutorials.
  * Secure multi-gateway payments with escrow handling.

## Technologies Used

* **Frontend:** HTML, CSS, JavaScript, Bootstrap, React (optional)
* **Backend:** Node.js / PHP / Python (depending on implementation)
* **Database:** MySQL / MongoDB
* **APIs:** Google Maps API for GPS tracking, Payment Gateway APIs
* **Cloud & Deployment:** AWS / Firebase / Heroku
* **Architecture:** Microservices with RESTful APIs

## Installation and Setup

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/Avjot-Chawla/Agro-Based-E-Commerce-Website.git
   ```

2. **Place in Web Server Directory:**

   * For PHP: Place in `htdocs` (XAMPP).
   * For Node.js: Use `npm install` to install dependencies.

3. **Configure Environment:**

   * Update `.env` or configuration files with database credentials and API keys.
   * Default DB credentials:

     * **Username:** root
     * **Password:** root
     * **Database Name:** agro\_db

4. **Start the Server:**

   * PHP: Start Apache and MySQL in XAMPP.
   * Node.js: Run `npm start`.

## Database Setup

1. **Create Database:**

   * Use MySQL or MongoDB to create a new database named `agro_db`.

2. **Run Schema Scripts:**

   * Execute the provided DDL and DML scripts from the project documentation to create tables/collections and insert initial data.

## Usage

1. **Launch the App:**

   * Access via browser at `http://localhost/your_project_folder/index.html` or local Node.js port.

2. **Modules:**

   * **Farmers:** Register, add products, view sales, manage orders.
   * **Consumers:** Browse products, get AI suggestions, place orders, track deliveries.
   * **Admins:** Manage listings, users, logistics, resolve disputes, view analytics.

## Project Structure

```
Agro-Based-E-Commerce-Website/
├── frontend/               # HTML/CSS/JS/React components
│   ├── index.html
│   ├── farmer/
│   ├── consumer/
│   ├── admin/
│   └── assets/
├── backend/                # API endpoints, business logic
│   ├── server.js / app.php
│   ├── routes/
│   ├── controllers/
│   └── models/
├── database/               # SQL or MongoDB scripts
│   └── agro_db.sql
├── public/                 # Images and public assets
├── .env                    # Environment variables
└── README.md               # This file
```

## Contributing

We welcome contributions that help improve the platform or introduce new features. Please fork the repository and submit a pull request. Open an issue first for significant changes to discuss implementation strategies.

## Authors and Acknowledgements

* **Rahul Dev Manna** – RA2211003010570
* **Shreyan Dutta** – RA2211003010583
* **Avjot Singh Chawla** – RA2211003010584
* **Project Supervisor:** Dr. T. K. SIVAKUMAR
  *Department of Computing Technologies, SRM Institute of Science and Technology*

---
