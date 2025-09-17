# VaultEdge - Reliable Security - Protecting what matters!

**VaultEdge** is a security company providing high-quality security products, tailor-made packages, exclusive deals, and professional installation services for homes, offices, and commercial properties.

---

## Table of Contents

- [Features](#features)  
- [Technologies Used](#technologies-used)  
- [Installation](#installation)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [License](#license)  
- [Contact](#contact)  

---

## Features

- Product catalogue 
- Tailor-made security packages
- Installation service booking  
- Deals and discounts section
- Order and service tracking
- Secure user authentication and login 
- Responsive Design 
- Forgot / Reset Password  

---

## Technologies Used

- Vue.js
- MySQL 
- Node.js  
- Tailwind
- CSS  
- JavaScript 

---

## Installation

### Prerequisites
- Install **Node.js** (latest LTS recommended)
- Install **MySQL** and ensure it is running
---

1. **Database Setup**  
  Open MySQL and locate the database located in the folder called vaultedge_backend and please run that schema using MYSQL.

2. **Install Dependencies**  
   -  Open the project in **Visual Studio Code** (or your        preferred IDE).
   - Open **two terminals**:
   - **Frontend**:
    ```bash
     cd vaultedge_frontend
     npm install
    ```
   - **Backend**:
    ```bash
     cd vaultedge_backend
     npm install
    ```

3. **Configure Environment**  
   - Inside the `vaultedge_backend` folder, create a `.env` file and update it with your own configuration:
   - ```env
      DB_HOST=localhost
      DB_USER=root
      DB_PASSWORD=yourpassword
      DB_NAME=vault_edge
      JWT_SECRET=your_secret_key
      EMAIL_HOST=smtp.gmail.com
      EMAIL_PORT=587
      EMAIL_USER=youremail@gmail.com
      EMAIL_PASS=your_app_password
    ```
   -  ⚠️ Note: To generate an EMAIL_PASS for Gmail, enable 2-Step Verification on your Google account and create an App Password.

4. **Run the application**  
   - In your terminals please follow the below instructions to run your application successfully 
   - **Backend**:
    ```bash
    cd vaultedge_backend
    nodemon index.js
    The following link will open indicating that your backend server is successfully running :
    http://localhost:3000
    ```
   - **Frontend**:
    ```bash
    cd vaultedge_frontend
    npm run serve
    Open: http://localhost:8081

## Usage

- In order to access the VaultEdge ecommerce website, you first need to register yourself an account in the sign-up page and then login using your email address and password you created whilst registering.

---


## Contributing

Contributions, issues, and feature requests are welcome!  
Feel free to fork the repository and submit pull requests.  

---

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## Contact

For support or enquiries, contact:  
**Zoe Petersen**  
Email: zoetylerhendricks23@gmail.com  
GitHub: [Zoe Petersen] https://github.com/zoe-petersen

---
