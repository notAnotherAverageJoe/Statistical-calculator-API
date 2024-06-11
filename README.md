## 📊 Statistical Calculator API
Welcome to the Statistical Calculator API! This project is a simple yet powerful RESTful API built with Node.js and Express.js. It provides endpoints to calculate the mean, median, and mode of a list of numbers.

## 🚀 Features
Mean Calculation: Calculates the mean of a list of numbers.
Median Calculation: Calculates the median of a list of numbers.
Mode Calculation: Calculates the mode of a list of numbers.
Robust Error Handling: Provides meaningful error messages for invalid inputs.
Interactive Frontend: A user-friendly HTML interface to interact with the API.
## 🛠️ Technologies Used
Node.js
Express.js
JavaScript (ES6+)
Mocha & Chai (for testing)
## 📂 Project Structure
.
├── public
│   └── index.html
├── helpers.js
├── helpers.test.js
├── expressError.js
├── server.js
└── package.json

## 📋 API Endpoints
## Calculate Mean
URL: /mean
Method: GET
Query Parameter: nums (comma-separated list of numbers)
Example: http://localhost:1337/mean?nums=1,2,3,4,5
Response:
json

{
  "operation": "mean",
  "result": 3
}
## Calculate Median
URL: /median
Method: GET
Query Parameter: nums (comma-separated list of numbers)
Example: http://localhost:1337/median?nums=1,2,3,4,5
Response:
json

{
  "operation": "median",
  "result": 3
}
## Calculate Mode
URL: /mode
Method: GET
Query Parameter: nums (comma-separated list of numbers)
Example: http://localhost:1337/mode?nums=1,2,2,3,4,5
Response:
json

{
  "operation": "mode",
  "result": 2
}
🧩 Setup and Installation
Clone the repository:

```bash
Copy code
git clone https://github.com/your-username/statistical-calculator-api.git
Navigate to the project directory:

bash
Copy code
cd statistical-calculator-api
Install the dependencies:

bash
Copy code
npm install
Start the server:

bash
Copy code
npm start
Open your browser and navigate to:
```

arduino
http://localhost:1337
🧪 Running Tests
To run the tests, use the following command:

```bash
npm test
🌟 Usage
Open your browser and go to http://localhost:1337.
```
Enter a list of numbers separated by commas in the input field.
Click on the desired calculation (Mean, Median, or Mode).
View the result displayed on the page.
## 💡 Example Requests
Mean: http://localhost:1337/mean?nums=1,2,3,4,5
Median: http://localhost:1337/median?nums=1,2,3,4,5
Mode: http://localhost:1337/mode?nums=1,2,2,3,4,5
## 👨‍💻 Contributing
Fork the repository
Create a new branch: git checkout -b my-new-feature
Commit your changes: git commit -am 'Add some feature'
Push to the branch: git push origin my-new-feature
Submit a pull request
📄 License
This project is licensed under the MIT License. See the LICENSE file for details.
## 
Special thanks: 
ATGTG