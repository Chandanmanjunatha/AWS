### AWS Math Web Application

Welcome to the **Math Web Application**! This simple web application leverages five different AWS services to design and build a fully functional, serverless application from scratch. The application includes features such as hosting a web page, performing serverless computations, and interacting with a NoSQL database. Below, you'll find details about each AWS service used and instructions to follow along.

---

## **AWS Services Used**

### 1. **AWS Amplify**
- **Purpose:** Amplify is used to build and host the website.
- **Note:** In this project, a text editor (such as Notepad) is used to create a simple `index.html` page, which is then deployed using AWS Amplify.

### 2. **AWS Lambda**
- **Purpose:** Lambda allows running serverless code upon specific triggers, such as an HTTP request.
- **Code:** The `PowerOfMathFunction` Lambda function handles mathematical computations.

### 3. **Amazon API Gateway**
- **Purpose:** API Gateway is used to build HTTP, REST, and WebSocket APIs. In this application, it acts as the entry point for the `PowerOfMathFunction` Lambda function.

### 4. **Amazon DynamoDB**
- **Purpose:** A serverless NoSQL database to store and retrieve data, if needed.

### 5. **AWS Identity & Access Management (IAM)**
- **Purpose:** IAM is used to set permissions for the Lambda function’s execution role, ensuring it has the necessary access to other AWS services.

---

## **Project Files**

Below are the files provided for this project:

1. **`index-ORIGINAL.html`**: [View or Download](https://drive.google.com/file/d/1D4GFqjos_MmCES7wHbn4ccD6Gq2ZCuul/view)
2. **`PowerOfMathFunction - Lambda-ORIGINAL.txt`**: [View or Download](https://drive.google.com/file/d/1ak_o_OKKBv5UFa7lcp2CMfKsh10tEAhi/view)
3. **`Execution Role Policy JSON.txt`**: [View or Download](https://drive.google.com/file/d/1xdko5AREleKbVfvj9MwRDpNqOzEl1qlj/view)
4. **`PowerOfMathFunction - Lambda-FINAL.txt`**: [View or Download](https://drive.google.com/file/d/1ao_8hKZXEmL4pNeeWEHdaWmUNdLPGAJb/view)
5. **`index.html`**: [View or Download](https://drive.google.com/file/d/1fCFDH1PcT6Gw0rZUIsJnQf8xow4GEdv_/view)

---

## **How to Build the Application**

### **Prerequisites**

1. A **text editor**, such as Notepad, Visual Studio Code, or Notepad++.
2. An **AWS account** with access to the AWS Management Console. Ensure you have administrator permissions. (Need help setting up? [Watch this video](#) for assistance.)
3. Basic knowledge of AWS is helpful, but beginners can follow along as well.

### **Steps to Build the Application**

1. **Create the HTML Page (Frontend):**
   - Use the `index.html` file provided or create your own simple HTML page.
   - Host the file using **AWS Amplify** for a fast and scalable solution.

2. **Set Up Lambda Function:**
   - Use the `PowerOfMathFunction` Lambda function code to perform serverless mathematical operations.
   - Deploy the provided `PowerOfMathFunction - Lambda-FINAL.txt` code in the AWS Lambda console.

3. **Configure API Gateway:**
   - Create a REST API using **Amazon API Gateway**.
   - Link the API Gateway to the Lambda function to trigger computations.

4. **Set Up IAM Roles:**
   - Use the `Execution Role Policy JSON.txt` to define the permissions for your Lambda function.
   - Grant access to resources such as API Gateway and DynamoDB.

5. **Optional: Integrate DynamoDB:**
   - Add functionality to store or retrieve user data or computation history using DynamoDB.

6. **Deploy and Test:**
   - Use the provided `index.html` file or your custom frontend to interact with the backend.
   - Test the application by performing calculations and ensuring all components work together seamlessly.

---

## **Licensing**

This project is provided under the MIT License:

```
MIT License

Copyright (c) 2025 Chandan M

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## **Feedback and Contributions**
Feel free to submit issues or contribute to the project by improving the documentation or code. If you have any questions, reach out to the project maintainer.

Happy coding!


