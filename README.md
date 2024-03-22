<h1 align="center" text="charcoal">
    Guest Camera Notifi App
</h1>

## Project Overview
This Node.js and Express.js project creates a personal guest registration system for your desk. An Application which informs Desk User That a Guest visited thir Desk when they went away. <br> 
 Guests scan a QR code displayed on your desk to access a web form, enter their details, and capture a selfie for your verification. This captured image is sent to your email for review, helping you identify who visited your desk while you were away.

## Features

<ul> 
<li> Generates a unique QR code for guest registration.</li>
<li> Handles guest registration form with name, contact information (optional), and selfie capture. </li>
<li> Stores captured images securely in the database (processing optional).</li>
<li> Sends email notifications to your configured email address with guest details and image. </li>
</ul>

## Technologies Used

<ul> 
<li> Backend: Node.js, Express.js</li>
<li> Database: MongoDB (to be implemented) </li>
<li> QR Code Generation: qrcode (Node.js library) </li>
<li> Image Processing : Node-webcam library </li>
<li> Nodemailer Integration : nodemailer library</li>
</ul>

## Setup

1. Install dependicies
```sh
npm install

```
2. Configure database connection details in config.js
3. Configure Nodemailer in config.js for email notifications to your desired email address.

4. Run the application:
```sh
node app.js

```
