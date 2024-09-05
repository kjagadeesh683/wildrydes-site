OVERVIEW OF THE PROJECT:

Fantastic Rides is an AWS serverless application that lets users request rides by specifying their pickup location through an HTML-based interface. It connects to a RESTful backend service for ride dispatch, and users can log in and register before making a request.


APPLICATION ARCHITECTURE:

The application architecture uses AWS Lambda, Amazon API Gateway, Amazon DynamoDB, Amazon Cognito, and AWS Amplify Console. The static web resources, such as HTML, CSS, JavaScript, and image files, are continuously deployed and hosted by Amplify Console and loaded into the user's browser. Data is sent and received from a public backend API created using Lambda and API Gateway by JavaScript running in the browser. To secure the backend API, Amazon Cognito offers user management and authentication features. Last but not least, DynamoDB offers a persistence layer where the Lambda function of the API can store data.

 ![image](https://github.com/user-attachments/assets/e69da070-aa84-48d4-9bbe-e614ee9964c0)


AWS SERVICES USED:
 
1.AWS AMPLIFY - 
AWS Amplify is a set of purpose-built tools and capabilities that enable front-end web and mobile developers to rapidly and simply build full-stack apps on AWS, with the flexibility to utilize the complete range of AWS services as your use cases change. You can simply establish a web or mobile app backend with Amplify, connect your app in minutes, visually construct a web frontend UI, and manage app content outside of the AWS console. With no cloud experience required, you can ship quicker and grow easily.


2.AWS COGNITO - 
Amazon Cognito allows you to quickly and simply add user sign-up, sign-in, and access management to your online and mobile apps. Amazon Cognito enables sign-in with social identity providers such as Apple, Facebook, Google, and Amazon, as well as enterprise identity providers through SAML 2.0 and OpenID Connect, and scalable to millions of users.
 
3.AWS LAMBDA - 
AWS Lambda is a serverless computing solution that automatically maintains the underlying compute resources for you while running your code in response to events. Changes in state or updates, such as a user adding an item to a shopping cart on an ecommerce website, are examples of these events. You may use AWS Lambda to add custom logic to other AWS services or build your own backend services that run on AWS scale, performance, and security. AWS Lambda automatically executes code in response to a variety of events, including HTTP requests via Amazon API Gateway, object modifications in Amazon Simple Storage Service (Amazon S3) buckets, Amazon DynamoDB table updates, and AWS Step Function state transitions.

4.AWS DynamoDB - 
Amazon DynamoDB is a fully managed ("serverless") NoSQL (non relational) database service on Amazon Web Services. Because DynamoDB is extremely scalable, you can start small and scale up without having to re-architect or re-deploy your system. It also features a flexible strategy that employs automated throughput capacity scaling, which saves money and reduces entry costs by scaling compute capacity in response to demand. 

5.AWS API GATEWAY - 
The Amazon API Gateway service is a fully managed service that allows developers to easily construct, publish, maintain, monitor, and protect APIs at any size. APIs allow apps to access data, business logic, or functionality from your backend services through a "front door".
