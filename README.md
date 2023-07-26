# Basic-web-server
This is a basic server using Node.js. It only works on a domain  but  not on modern browsers.
# Temperature Converter

This project is a simple temperature converter that can convert between Fahrenheit,Celsius,Kelvin.
Temperature Converter is a simple web application that allows users to convert temperature values between Celsius, Fahrenheit, and Kelvin. This application is built using HTML, CSS, and JavaScript

# How to Use
1.Clone or download the repository to your local machine.

2.Open the index.html file in your web browser.

3.You will see the Temperature Converter interface, which consists of the following elements:

 *Input Value: Enter the temperature value that you want to convert in the "Enter Your Value" input field.
 
 *Select Temperature Unit: Choose the unit of the temperature value you entered (Fahrenheit, Celsius, or Kelvin) from the drop-down menu.
 
 *Calculate Button: Click on the "Calculate" button to perform the conversion.

4.Once you click the "Calculate" button, the converted values will be displayed in the three input fields:

Value In Celsius: The converted temperature value in Celsius.
Value In Fahrenheit: The converted temperature value in Fahrenheit.
Value In Kelvin: The converted temperature value in Kelvin.

5.You can repeat the process by entering a new temperature value or selecting a different unit.

# Technologies Used

*HTML: The structure and layout of the web page.

*CSS: Styling and appearance of the elements.

*JavaScript: Handling the conversion logic and user interactions.

*Bootstrap 5: A popular CSS framework for responsive and mobile-first designs

# Directory Structure
Temperature_converter/

|-- index.html

|-- styles.css

|-- script.js

|--server.js

README.md



# Temperature Converter Server

Temperature Converter Server is a Node.js application that serves the Temperature Converter web application to clients. The server listens on port 3000 and provides the necessary files, such as HTML, CSS, and JavaScript, to render the Temperature Converter in the client's web browser.

Navigate to the root directory of the project where the server code is located.

Install the required dependencies by running the following command:


*npm install
Start the server by running the following command:


*node server.js
The server will start listening on http://localhost:3000.

Open your web browser and enter http://localhost:3000 in the address bar.

You will see the Temperature Converter web application, which allows you to convert temperature values between Celsius, Fahrenheit, and Kelvin.

Follow the instructions provided in the Temperature Converter web application's README to learn how to use the converter.


# How It Works
The server.js file contains the Node.js server code. It uses the http module to create a server and serves the Temperature Converter files stored in the Temperature_converter directory.

When a client makes a request to the server, the server checks the requested URL and maps it to the corresponding file path in the Temperature_converter directory. If the requested file is found, the server reads the file and sends it as a response to the client. If the file is not found, a 404 error response is sent.

The server also sets the appropriate Content-Type header based on the file extension, so the client's browser can interpret the file correctly.

# Contribution
If you would like to contribute to the project, feel free to fork the repository, make changes, and submit a pull request. We welcome any suggestions or improvements to enhance the functionality and usability of the Temperature Converter.


# Acknowledgments
We would like to thank the Bootstrap team and the open-source community for providing the tools and resources that made this project possible

# Author
*Sigireddy Viswesh
*sigireddyviswesh@gmail.com
