# 💱 CashSwap — Your Campus Exchange

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

A simple, single-page web application designed for students on a campus to facilitate peer-to-peer exchange of **Cash** for **UPI (Unified Payments Interface)** transactions, and vice-versa. It acts as a local bulletin board for instant, small-scale cash/digital currency swaps.

## ✨ Features

CashSwap provides a clean, mobile-friendly interface for posting and viewing exchange requests.

* **➕ Post New Requests:** Easily post a request detailing the amount (in ₹), what you **Have** (Cash or UPI) and what you **Need** (Cash or UPI), along with your contact information and meeting details.
* **📋 Real-Time Request List:** View all active exchange requests, sorted by the most recent.
* **🔍 Search & Filter:** Quickly find specific requests by searching through details or filtering by transaction type (`Cash → UPI` or `UPI → Cash`).
* **🔒 Local Storage Persistence:** All requests are stored locally in the user's browser's **Local Storage**, meaning they persist even after closing and reopening the application.
* **🗑️ Delete Requests:** Users can remove their requests once the transaction is complete.

***

## 🚀 How to Use

The application is a single HTML file with embedded styles and logic.

### Prerequisites

You need a modern web browser (Chrome, Firefox, Safari, Edge).

### Getting Started

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/NSaiHanuman/Swap-Cash.git](https://github.com/NSaiHanuman/Swap-Cash.git)
    cd Swap-Cash
    ```
2.  **Open the file:** Open the `index.html` file directly in your web browser.

### Posting an Exchange Request

1.  Fill in the **Amount** (e.g., `500`).
2.  Select what you **Have** (e.g., `Cash`).
3.  Select what you **Need** (e.g., `UPI`). (*Note: "Have" and "Need" must be different.*)
4.  Enter your **Contact Number**.
5.  Add any **Additional Details** (location, time, notes).
6.  Click **Post Request**.

### Fulfilling a Request

1.  Browse or use the search/filter tools to find a request you can help fulfill.
2.  Click the **Contact** button on the request card.
3.  Reach out to the poster using the provided contact details to arrange the swap.

***

## 🛠️ Technology Stack

This project is a pure client-side application utilizing minimal external dependencies:

* **HTML5**
* **CSS3** (Custom styles + **Bootstrap 5.3** for layout/components)
* **Vanilla JavaScript (ES6+**): Handles all logic, form validation, data management, and DOM rendering.
* **Local Storage:** Used as the persistent data store for all exchange requests.
* **Font Awesome & Bootstrap Icons:** Used for visual cues and iconography.

***

## 💡 Safety & Disclaimer

> **Safety First:** Always meet in public, high-traffic areas on campus and verify payment before completing the exchange. The app is a bulletin board and does not handle transactions.

***

## 📄 License

This project is licensed under the **MIT License**.
