# 🚀 Automation Exercise API - Postman Test Collection

![Postman Collection](https://img.shields.io/badge/Postman-Collection-orange?logo=postman) ![Newman](https://img.shields.io/badge/Newman-CLI-blue?logo=javascript) ![Node.js](https://img.shields.io/badge/Node.js-v20.12.2-green?logo=node.js)  
This repository contains a collection of Postman API tests for the [Automation Exercise API](https://www.automationexercise.com/api_list). The tests cover various API endpoints, ensuring that all functionalities work as expected.

You can run the tests locally using Newman, the command-line companion for Postman, and integrate it into your development environment using Visual Studio Code (VSCode).

---

## 📋 Prerequisites

Before running the tests, ensure that the following are installed on your system:

- [Node.js](https://nodejs.org/) (v20.12.2 recommended)
- [Postman](https://www.postman.com/downloads/) (for creating and editing API collections)
- [Newman](https://www.npmjs.com/package/newman) (for running Postman collections in the CLI)
- [Visual Studio Code (VSCode)](https://code.visualstudio.com/)

---

## 🚀 Getting Started

### 1. Clone the Repository

\`\`\`bash
git clone https://github.com/TatianaPet121516/project-Postman-api-testing.git
\`\`\`

### 2. Install Dependencies

If there are any Node.js dependencies in the project (such as Newman or supporting scripts), install them using:

\`\`\`bash
npm install
\`\`\`

### 3. Install Newman

Install Newman globally to run Postman tests from the command line:

\`\`\`bash
npm install -g newman
\`\`\`

### 4. Run the Postman Tests with Newman

To execute the Postman collection for the Automation Exercise API, use the following command:

\`\`\`bash
npm run test
\`\`\`

This command will run the collection and display the test results directly in the terminal.

### 5. Run Tests in VSCode Terminal

You can also run Newman directly in the integrated terminal in VSCode. Open the terminal inside VSCode by selecting:

\`\`\`
Terminal > New Terminal
\`\`\`

Then run the same \`newman run\` commands.

---

## 📖 API Documentation

The API documentation for Automation Exercise is available at [Automation Exercise API List](https://www.automationexercise.com/api_list).

---

## 📂 Postman Collection Endpoints

This collection includes tests for the following endpoints:

1. GET All Products List
2. POST To All Products List
3. GET All Brands List
4. PUT To All Brands List
5. POST Search Product
6. POST Search Product (without \`search_product\` parameter)
7. POST Create/Register User Account
8. POST Verify Login (valid details)
9. POST Verify Login (without \`email\` parameter)
10. DELETE Verify Login
11. POST Verify Login (invalid details)
12. GET User Account Detail by Email
13. PUT Update User Account
14. GET Updated User Account Detail by Email
15. DELETE Delete User Account

---

## 📜 License

This project is licensed under the ISC License. See the [LICENSE](LICENSE) file for more information.
