# POS Mobile App – Flutter

## Overview

This mobile application is part of a larger POS (Point of Sale) system. It is built using **Flutter** and designed to assist store staff or cashiers in:

- Scanning **barcodes and QR codes**
- **Searching products** from the store inventory
- **Generating invoices** for customer purchases

The app communicates with a backend server or POS desktop system to fetch product details and push invoice data.

---

## Features

- 📷 **Barcode and QR Code Scanning**
  - Quickly scan product codes using the mobile device's camera
  - Supports both barcode and QR formats

- 🔍 **Product Lookup**
  - Search for products manually by name or code
  - View item details such as price, description, and availability

- 🧾 **Invoice Generation**
  - Add scanned or searched items to a cart
  - Generate and submit invoices to the POS system or server
  - View invoice totals and details

- 🔄 **Real-time Communication**
  - Fetch data from the POS server for live inventory
  - Submit invoice data back to the central system

---

## Technology Stack

- **Flutter** (Dart)
- **Networking**: HTTP or Dio package for API calls
- **Backend**: Connects to Java server/POS desktop app 

---

## Installation & Setup

### Prerequisites

- Flutter SDK installed ([Install Guide](https://docs.flutter.dev/get-started/install))
- Android Studio or VS Code
- Android/iOS device or emulator

### Steps

1. **Clone the repository**
   ```bash
   git clone https://github.com/shashika-jiat/sad_team_viva.git
   cd mobile
