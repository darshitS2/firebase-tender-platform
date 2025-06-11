# Firebase Tender Platform

This is a real-time, multi-user tendering platform built with vanilla HTML, CSS, and JavaScript, powered by Google Firebase for the backend.

## Features

- User authentication (Admin & Bidder roles)
- Admins can create, edit, delete, and close tenders.
- Bidders can view active tenders and submit bids.
- One-bid-per-tender rule for bidders.
- Real-time updates for bids and tender status using Firestore.
- Dynamic countdown timers for tender deadlines.

## Tech Stack

- **Frontend:** HTML5, CSS3, JavaScript (ES6+)
- **Backend:** Google Firebase
  - Firestore Database (for data storage)
  - Firebase Authentication (for user management)

## Setup

1. Clone the repository.
2. Create a Firebase project.
3. Enable Firestore and Authentication (Email/Password).
4. Paste your own Firebase config object into the `<script>` tag in `index.html`.
5. Create an admin user by registering and then manually changing their `userType` to 'admin' in the Firestore `users` collection.
