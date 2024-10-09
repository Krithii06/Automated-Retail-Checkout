# Automated Retail Checkout Using RFID and Web-Based Trolley System

## Overview

This project demonstrates the implementation of an automated retail checkout system using RFID technology, Arduino Uno, ESP8266, and a ReactJS-based web application. The system allows for seamless scanning of products, real-time cart updates, and a contactless checkout experience.

## Features

- **RFID Product Scanning**: Automatically scans and identifies products as they are added to the trolley.
- **Real-Time Cart Updates**: Product details are displayed on an LCD screen and synchronized with a web-based interface for real-time tracking.
- **Seamless Checkout**: Eliminates the need for traditional cashier-based checkout, enabling a smooth and contactless payment experience.

## Hardware Components

- **Arduino Uno**: Controls the RFID scanner and LCD display.
- **ESP8266**: Provides Wi-Fi connectivity for real-time data transmission to the web app.
- **RFID Reader**: Detects and scans product RFID tags.
- **LCD Screen**: Displays the scanned product details in real time.
- **Buzzer**: Alerts in case of system errors or issues.
- **Power Supply**: Powers the Arduino, ESP8266, and other components.

## Software Components

- **ReactJS Web Application**: The front-end application provides users with a real-time view of their cart and facilitates the checkout process.
- **Arduino Code**: Controls the RFID scanner, communicates with the ESP8266, and displays product details on the LCD.
- **Formik for Form Validation**: Used for handling and validating forms in the web app.
- **Material UI for Styling**: Ensures a responsive and modern design.

## Setup Instructions

1. **Hardware Setup**:
   - Connect the RFID reader to the Arduino Uno.
   - Connect the ESP8266 to the Arduino for wireless communication.
   - Set up the LCD and buzzer with appropriate pins.
   
2. **Arduino Code**:
   - Upload the Arduino sketch to handle RFID reading and communication with ESP8266.
   
3. **Web Application**:
   - Clone the ReactJS web application.
   - Install dependencies using `npm install`.
   - Run the app locally with `npm start` or deploy it to a web server.
   
4. **Wi-Fi Configuration**:
   - Configure the ESP8266 module with your Wi-Fi credentials for real-time communication.

## How It Works

- As products are added to the trolley, the RFID reader scans the RFID tags attached to each item.
- The scanned details are displayed on the LCD and sent via the ESP8266 module to the web application.
- The web application updates the cart in real-time, showing the total price and allowing users to proceed to payment.

## Future Enhancements

- Integrate advanced analytics to track customer shopping patterns.
- Implement machine learning models for personalized product recommendations.
- Expand hardware integration to support additional sensors for an enhanced shopping experience.

# https://singular-nasturtium-021c81.netlify.app/

Click here for the Web App
