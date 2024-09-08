# SimpleCalculation: AWS-Based Serverless Calculator Application
SimpleCalculation is a highly scalable and serverless calculator application built using AWS Amplify, AWS Lambda, Amazon API Gateway, and Amazon DynamoDB. This project performs basic arithmetic operations such as addition, subtraction, multiplication, division, modulo, and exponentiation. It demonstrates the use of serverless architecture to build efficient, scalable, and cost-effective applications.

### Features
Serverless Backend: Powered by AWS Lambda, ensuring high scalability and cost efficiency by executing code only when needed.
API Integration: Amazon API Gateway serves as a front door, securely managing requests to the Lambda function.
Persistent Storage: Amazon DynamoDB is used to store calculation results and inputs for future reference.
AWS Amplify for Frontend: Provides a robust and scalable platform for hosting the calculator's user interface with continuous deployment.

### Tech Stack
AWS Lambda: Executes the server-side arithmetic operations.
Amazon API Gateway: Manages and secures API requests between the client and server.
Amazon DynamoDB: Stores the calculation history.
AWS Amplify: Hosts the front-end application for user interaction.

### Requirements
AWS CLI installed and configured
AWS Lambda function setup
Amazon API Gateway configured
Amazon DynamoDB table setup for persistent storage
AWS Amplify project for hosting the frontend

### Installation and Setup
Clone the repository: git clone https://github.com/yourusername/SimpleCalculation.git
cd SimpleCalculation
Deploy the front-end using AWS Amplify:

amplify init
amplify add hosting
amplify publish

Configure the backend with AWS Lambda, API Gateway, and DynamoDB:

Create a new Lambda function to perform the calculations.
Set up an API Gateway to trigger the Lambda function via RESTful API requests.
Create a DynamoDB table to store calculation inputs and results.
Update API endpoints and DynamoDB configurations in the front-end code.

### Usage
Navigate to the hosted front-end.
Input the desired arithmetic operation and numbers.
The application sends a request to API Gateway, which triggers the Lambda function.
The result is returned and displayed, with the operation being stored in DynamoDB for future reference.

### Contributing
Contributions are welcome! Feel free to open issues, submit pull requests, or suggest enhancements.

### License
This project is licensed under the MIT License.

