# Point of Sale (POS) System with Mobile Barcode/QR Scanner 

## Overview

This project consists of three main components:

1. **POS Application (Java Swing Desktop App)**  
   A desktop Point of Sale (POS) system developed using Java Swing in NetBeans. It supports product searching, invoice generation, and integrates with a separate Java server application.

2. **Mobile App (Barcode & QR Code Reader)**  
   A mobile application designed for scanning barcodes and QR codes. It communicates with the POS system to streamline product lookup and invoice processing.

3. **Java Server Application**  
   A standalone Java server process that runs separately from the POS app, providing backend services such as managing product data, processing requests from the POS and mobile apps, and handling concurrency.

---

## Features

- **POS Desktop App**  
  - User-friendly interface built with Java Swing  
  - Product search functionality by barcode, QR code, or keywords  
  - Invoice generation and printing  
  - Integration with backend server for real-time data synchronization  

- **Mobile Barcode & QR Scanner**  
  - Scan barcodes and QR codes to fetch product details  
  - Send scanned data to the POS system for quick lookup  
  - Supports Android (or specify platform)  

- **Java Server**  
  - Acts as a middleware for data handling and request management  
  - Maintains product inventory and handles multiple client connections  
  - Runs as a separate process to decouple backend logic from the UI  

---

## Technology Stack

- **Java SE (Swing)** — POS Desktop Application  
- **Java (Server-side)** — Backend server application  
- **Mobile Platform** — Barcode and QR code scanning (e.g., Android with ZXing or similar library)  
- **NetBeans IDE** — Development environment  
- **Ant** — Main build system for all Java components  

---

## Installation & Setup

### Prerequisites

- Java Development Kit (JDK) 8 or above  
- NetBeans IDE  
- Ant build tool (usually included with NetBeans)  
- Mobile device (Android recommended)  

### Steps

1. **Clone the repository**  
   ```bash
   git clone https://github.com/shashika-jiat/sad_team_viva.git
