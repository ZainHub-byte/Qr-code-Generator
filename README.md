QR Code Generator
This project is a simple QR Code Generator web application that allows users to input a URL and generate a corresponding QR code. Users can then download or share the generated QR code image. The project is built with HTML, CSS, and JavaScript, and it uses the GoQR API to generate the QR codes.

Features
Responsive Design: The application is designed to be responsive, making it accessible on various devices, from desktops to mobile phones.
Custom Fonts: Utilizes the 'Outfit' font from Google Fonts for a modern and clean look.
QR Code Generation: Users can input a URL and generate a QR code using the GoQR API.
Download QR Code: Users can download the generated QR code as an image file.
Share QR Code: Users can copy the QR code URL to the clipboard for easy sharing.
Project Structure
lua

/ (Root Directory)
|-- index.html
|-- qrcode.html
|-- styles.css
|-- script.js
|-- script-qrcode.js
|-- bg-illustration.svg
Files Description
index.html: The main landing page where users can input a URL to generate a QR code.
qrcode.html: The page that displays the generated QR code with options to download or share.
styles.css: Contains the styling for the application, making use of modern CSS techniques and responsive design principles.
script.js: Handles the QR code generation process by interacting with the GoQR API and local storage.
script-qrcode.js: Manages the download and sharing functionalities of the generated QR code.
bg-illustration.svg: Background illustration used for aesthetic enhancement of the web pages.
Usage
Clone the repository:

bash

git clone https://github.com/yourusername/qr-code-generator.git
cd qr-code-generator
Open the project:
Open index.html in your preferred web browser to start using the application.

How It Works
Enter URL: On the index.html page, enter the URL you want to generate a QR code for in the input field and click the "QR code" button.
Generate QR Code: The application uses the GoQR API to generate a QR code for the entered URL.
View QR Code: The qrcode.html page displays the generated QR code.
Download or Share: Users can click the "Download" button to download the QR code image or the "Share" button to copy the QR code URL to the clipboard.
Customization
Styling: You can modify styles.css to change the look and feel of the application according to your preference.
Functionality: You can extend the functionalities by adding more features or integrating other APIs by modifying script.js and script-qrcode.js.
Dependencies
Google Fonts: Uses the 'Outfit' font from Google Fonts.
GoQR API: Utilizes the GoQR API for QR code generation
