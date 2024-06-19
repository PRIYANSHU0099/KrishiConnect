# KrishiConnect

KrishiConnect is a comprehensive platform designed to bridge the gap between local farmers and consumers, focusing on the sale and purchase of 100% organic, chemical-free products. This README file provides an overview of the functionality, technology stack, and services offered by KrishiConnect, along with instructions for setting up the project.

## Functionality and Services Offered

### Overview
KrishiConnect serves as a one-stop solution for local farmers and buyers of organic products. The platform offers a dual interface catering to both sellers (farmers) and consumers.

### For Farmers
- **Registration**: Farmers can register as sellers by creating a profile.
- **Product Listing**: Sellers can list the organic products they wish to sell.
- **Cultivation Information**: Access valuable information on organic farming practices.
- **On-site Assistance**: Request for on-site assistance from our expert team.
- **Product Categories**: Includes organic fruits and vegetables, oilseeds, herbs, and more.

### For Consumers
- **Product Browsing**: Browse a variety of organic products.
- **Shopping Cart**: Add and remove products from the shopping cart.
- **Multiple Payment Options**: Pay using various available payment methods.
- **User-Friendly Interface**: A seamless shopping experience similar to other online shopping platforms.

## Technology Involved

### Frontend
- **HTML, CSS, Bootstrap**: For aesthetics and design.
- **JavaScript**: For interactive elements and client-side functionality.

### Backend
- **Firebase**: For database management, user authentication (signup and login), and maintaining user data.

### Hosting
- **Google Cloud Platform**: 
  - **VM Instance (T2D Machine Type)**: Used for creating the server and hosting the website. Tau T2D VMs are optimized for cost-effective performance of demanding operations and are based on the AMD Milan CPU platform (Epyc microprocessor).

## Results
We have created a video demonstrating the functioning of our website. You can view it [here](link_to_video).

## Setup Instructions

### Prerequisites
- Node.js and npm installed on your local machine
- Firebase CLI installed
- Google Cloud account with access to VM instances

### Installation

1. **Clone the Repository**
    ```sh
    git clone https://github.com/your-username/KrishiConnect.git
    cd KrishiConnect
    ```

2. **Install Dependencies**
    ```sh
    npm install
    ```

3. **Configure Firebase**
    - Sign in to Firebase
    - Create a new project
    - Add your Firebase configuration to the project
    - Initialize Firebase in your project directory
      ```sh
      firebase init
      ```

4. **Start the Development Server**
    ```sh
    npm start
    ```

5. **Deploying to Google Cloud VM**
    - Create a new VM instance in Google Cloud Platform using the T2D machine type.
    - Deploy your application to the VM instance.
    - Ensure all necessary ports are open and the server is running.

## Contributing

We welcome contributions to KrishiConnect. To contribute:

1. Fork the repository.
2. Create a new branch.
3. Make your changes.
4. Submit a pull request detailing your changes.

## Contact

For any queries or support, please reach out to us at support@krishiconnect.com.

---

Thank you for using KrishiConnect! Together, let's promote organic farming and support local farmers.

