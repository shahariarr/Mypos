# MY POS

This software is a single use system designed to help business owners manage their businesses efficiently.

## Features Overview

This Point of Sale (POS) system is designed to manage sales, inventory, and transactions efficiently. Below is a detailed list of features and functionalities included in the system.

### 1. Login Page
- **User Authentication**: Secure login for users with unique credentials.

### 2. Home/Dashboard Page
- **Summary Display**: Provides an overview of the system's key metrics and statistics.

### 3. Categories Management
- **Add New Category**: Allows users to create and add new product categories.
- **List All Categories**: Displays a list of all existing categories.
- **Update Category Details**: Enables editing of category information.
- **Delete Category Details**: Allows removal of categories from the system.

### 4. Products Management
- **Add New Product**: Facilitates adding new products to the inventory.
- **List All Products**: Shows a comprehensive list of all products.
- **Update Product Details**: Allows updating of product information.
- **Delete Product Details**: Enables deletion of products from the inventory.

### 5. Point of Sale (POS)
- **Add Product Item to List**: Users can add products to the sales list.
- **Calculate Automatically the Total**: The system auto-calculates the total price of the listed products.
- **Remove Product Item from the List**: Products can be removed from the sales list.
- **Update Item Quantity and Recalculate Total**: Adjusts quantities and recalculates the total price.
- **Auto-Calculate Tax Amount**: Automatically includes tax calculations in the total price.
- **Checkout Form Modal**: Provides a form for completing the checkout process.
- **Auto-Calculate the Customer Change**: Calculates and displays the change due to the customer.
- **Shows the Transaction Receipt**: Displays a receipt for the transaction.

### 6. Sales Management
- **List All Sales Transactions**: Shows a list of all sales transactions.
- **View Transaction Receipt**: Allows viewing of transaction receipts.
- **Print Transaction Receipt**: Provides an option to print receipts.
- **Delete Transaction Details**: Enables deletion of transaction records.

### 7. User Authentication
- **Logout**: Secure logout functionality for users.
## User Instructions

1. **Login:** An admin who will login with his username and password will not have any registration option.
2. **Inventory Management:** Manage your shop's inventory.
3. **Sales Process:** Sell products to customers and generate invoices.
4. **Generate Reports:** Generate sales reports to assist in business management.


## Technologies Used

- **Python**
- **Django**
- **HTML**
- **CSS**
- **JavaScript**
- **jQuery**
- **Ajax**
- **Bootstrap v5**

### Prerequisites
- Ensure you have the following software installed:
  - Python (I used v3.9.1)
  - Django (I used v3.2.3)
  - PIP (for python modules installation)

### Step-by-Step Instructions

1. **Download and Extract the Source Code**

    Download the provided source code zip file from the download button below. Once downloaded, extract the zip file to a desired location on your computer.

2. **Open Terminal/Command Prompt**

    Open your Terminal (macOS/Linux) or Command Prompt (Windows). Make sure you have added `python` and `pip` to your system's environment variables for easy access.

3. **Navigate to the Source Code Directory**

    Change the working directory to the folder where you extracted the source code. For example:

    ```sh
    cd C:\Users\shifat\Desktop\pos
    ```

4. **Install Django**

    Install Django using pip by running the following command:

    ```sh
    pip install Django
    ```

5. **Apply Migrations**

    Apply the necessary database migrations by running:

    ```sh
    python manage.py migrate
    ```

6. **Run the Development Server**

    Start the development server with the following command:

    ```sh
    python manage.py runserver
    ```

7. **Open the Project in a Web Browser**

    Open your web browser and navigate to either of the following URLs to view the project:

    - [http://localhost:8000/](http://localhost:8000/)
    - [http://127.0.0.1:8000/](http://127.0.0.1:8000/)
  
### Access Information
SuperUser
- Username: admin
- Password: admin123 

  

   

