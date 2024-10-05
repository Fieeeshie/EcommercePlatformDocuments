# ECOMMERCE PLATFORM (TechGear)

## INTRODUCTION

The eCommerce platform is designed to provide a comprehensive and user-friendly online shopping experience. It serves as a 
digital marketplace where businesses can display their products and customers can purchase them with ease. The platform is built 
with scalability, security, and user experience in mind, ensuring that it can handle the demands of a growing user base and a 
diverse range of products.

## Project Features and Characteristics

#### 1.User Account Management
•Secure registration and login with email verification.

•Profile management with options to update personal details, passwords, and preferences.

•Multi-factor authentication (MFA) for enhanced security.

#### 2.Product Catalog

•Dynamic and searchable product catalog with real-time inventory updates.

•Advanced filtering options based on categories, price range, ratings, and more.

•Detailed product pages with high-quality images, descriptions, and customer reviews.

#### 3.Shopping Cart

•Persistent shopping cart that retains items across sessions.

•Ability to modify item quantities, remove items, and save products for later.

•Automatic calculation of total costs including taxes and shipping.

#### 4.Order Management

•Streamlined order placement process with multiple payment options.

•Comprehensive order history, including downloadable invoices and receipts.

•Real-time order tracking integrated with major shipping carriers.

#### 5.Payment Integration

•Support for various payment methods including credit/debit cards, digital wallets (e.g., Paymaya, Gcash), and bank transfers.

•Secure transactions using industry-standard encryption and fraud detection.

•Integration with major payment gateways like Stripe, PayPal, and local payment providers.

#### 6.Admin Panel

•Comprehensive dashboard for monitoring sales, user activity, and inventory levels.

•Tools for product management, including bulk upload, editing, and categorization.

•Customer management features for handling queries, processing refunds, and managing user accounts.

#### 7.Customer Support

•Integrated helpdesk system with ticket management and live chat support.

•Knowledge base and FAQ section for self-service support.

•Automated email notifications for order confirmations, shipping updates, and support tickets.


#### 8.Reviews and Ratings

•Verified purchase reviews to ensure authenticity.

•Star ratings with the option to filter products based on ratings.

•Admin moderation tools for managing and responding to reviews.


#### 9.Inventory Management

•Automated stock level tracking with low-stock alerts.

•Integration with suppliers for real-time stock updates.

•Reporting tools for analyzing inventory turnover and forecasting demand.


## Project Scope

The scope of this eCommerce platform project encompasses the design, development, and deployment of a feature-rich online shopping platform. The platform is intended to serve small to medium-sized businesses, with potential scalability to accommodate larger enterprises. Key deliverables include:

•Frontend Development: Creation of a responsive, intuitive, and aesthetically pleasing user interface that provides a smooth browsing and shopping experience across devices.

•Backend Development: Implementation of robust server-side logic, database management, and API development to handle user interactions, product data, and payment processing.

•Security: Ensuring the platform adheres to best security practices, including data encryption, secure authentication, and regular security audits.

•Testing and Quality Assurance: Rigorous testing to ensure the platform is free of bugs, performs efficiently, and is secure from vulnerabilities.

•Deployment and Hosting: Hosting on a scalable cloud infrastructure, ensuring high availability, performance, and reliability.

### Out of Scope:

•Brick-and-mortar store integration.

•Support for multiple languages and currencies (to be added in future phases).

•Social media commerce features (e.g., direct shopping through social media platforms).

## Work breakdown Structure
![Blank diagram (1)](https://github.com/user-attachments/assets/f6ad86a6-c283-472e-85ee-0d7b8f56b039)

## Functional Requirements




### User Requirements

| No. | Users      | System Features                                          | Requirement                                                                                                                                               |
|-----|------------|----------------------------------------------------------|------------------------------------------------------------------------------------------------------------------------------------------------------------|
| 1   | Admin      | A. User Management Module - Register Customers           | 1. The system must allow the Admin to register customers on the platform by entering:                                                                       |
|     |            |                                                          |    a. Email Address                                                                                                                                         |
|     |            |                                                          |    b. Name                                                                                                                                                 |
|     |            |                                                          |    c. Password                                                                                                                                             |
|     |            |                                                          |    d. Address                                                                                                                                              |
|     |            |                                                          |    e. Phone Number                                                                                                                                         |
| 2   | Admin      | B. User Management Module - Customer Details             | 2. The system must allow the Admin to view customer details:                                                                                               |
|     |            |                                                          |    a. Customer ID                                                                                                                                          |
|     |            |                                                          |    b. Purchase History                                                                                                                                     |
|     |            |                                                          |    c. Activity Logs                                                                                                                                        |
| 3   | Admin      | C. Product Management Module - Add Products              | 3. The system must allow the Admin to add new products to the catalog by entering:                                                                         |
|     |            |                                                          |    a. Product Name                                                                                                                                         |
|     |            |                                                          |    b. Brand                                                                                                                                               |
|     |            |                                                          |    c. Description                                                                                                                                          |
|     |            |                                                          |    d. Price                                                                                                                                                |
|     |            |                                                          |    e. Stock Quantity                                                                                                                                       |
|     |            |                                                          |    f. Category                                                                                                                                             |
|     |            |                                                          |    g. SKU (Stock Keeping Unit)                                                                                                                             |
|     |            |                                                          |    h. Product Images                                                                                                                                       |
| 4   | Admin      | D. Order Management Module                               | 4. The system must allow the Admin to manage customer orders, including:                                                                                   |
|     |            |                                                          |    a. Viewing Order Details                                                                                                                                |
|     |            |                                                          |    b. Updating Order Status                                                                                                                                |
|     |            |                                                          |    c. Managing Returns and Refunds                                                                                                                         |
| 5   | Admin      | E. Report Generation                                     | 5. The system must allow the Admin to generate various reports, including:                                                                                 |
|     |            |                                                          |    a. Daily Sales Report                                                                                                                                   |
|     |            |                                                          |    b. Weekly Sales Report                                                                                                                                  |
|     |            |                                                          |    c. Monthly Sales Report                                                                                                                                 |
|     |            |                                                          |    d. Inventory Status Report                                                                                                                              |
| 6   | Customer   | A. User Management Module - Register & Login             | 1. The system must allow customers to register and log in to the platform by entering:                                                                     |
|     |            |                                                          |    a. Email Address                                                                                                                                        |
|     |            |                                                          |    b. Password                                                                                                                                             |
| 7   | Customer   | B. Product Catalog                                       | 2. The system must allow customers to view products, including:                                                                                           |
|     |            |                                                          |    a. Product Name                                                                                                                                         |
|     |            |                                                          |    b. Product Images                                                                                                                                       |
|     |            |                                                          |    c. Price                                                                                                                                               |
|     |            |                                                          |    d. Stock Availability                                                                                                                                   |
|     |            |                                                          |    e. Product Reviews                                                                                                                                      |
|     |            |                                                          |    f. Product Categories                                                                                                                                   |
| 8   | Customer   | C. Search & Filter                                       | 3. The system must allow customers to search and filter products by:                                                                                       |
|     |            |                                                          |    a. Product Name                                                                                                                                         |
|     |            |                                                          |    b. Brand                                                                                                                                               |
|     |            |                                                          |    c. Price Range                                                                                                                                          |
|     |            |                                                          |    d. Product Category                                                                                                                                     |
| 9   | Customer   | D. Shopping Cart Module                                  | 4. The system must allow customers to manage their shopping cart by:                                                                                       |
|     |            |                                                          |    a. Adding Products to Cart                                                                                                                              |
|     |            |                                                          |    b. Updating Product Quantities                                                                                                                          |
|     |            |                                                          |    c. Removing Products from Cart                                                                                                                          |
| 10  | Customer   | E. Checkout & Payment                                    | 5. The system must allow customers to proceed with checkout and payment, including:                                                                        |
|     |            |                                                          |    a. Shipping Information                                                                                                                                |
|     |            |                                                          |    b. Payment Method Selection                                                                                                                             |
|     |            |                                                          |    c. Order Summary Review                                                                                                                                 |
|     |            |                                                          |    d. Order Confirmation                                                                                                                                   |
| 11  | Customer   | F. Order Tracking                                        | 6. The system must allow customers to track their orders by viewing:                                                                                       |
|     |            |                                                          |    a. Order Status                                                                                                                                         |
|     |            |                                                          |    b. Estimated Delivery Date                                                                                                                              |
|     |            |                                                          |    c. Shipping Carrier Details                                                                                                                             |
| 12  | Customer   | G. Wishlist                                              | 7. The system must allow customers to save products to a wishlist for future reference.                                                                    |
| 13  | Customer   | H. Product Reviews                                       | 8. The system must allow customers to leave reviews and ratings for purchased products.                                                                    |


### use case
![image](https://github.com/Fieeeshie/EcommercePlatformDocuments/blob/main/use_case.png?raw=true)

## Database Architecture

### Data Dictionary

##### Table 1: USERS

| FIELD NAME | DESCRIPTION                            | DATA TYPE | LENGTH | SAMPLE          |
|------------|----------------------------------------|-----------|--------|-----------------|
| USER_ID    | Unique User Identification             | String    | 255    | USR123456       |
| EMAIL      | User's Email Address                   | String    | 255    | user@example.com|
| PASSWORD   | User's Encrypted Password              | String    | 255    | ******        |
| NAME       | Full Name of the User                  | String    | 255    | John Doe        |
| ADDRESS    | User's Address                         | String    | 255    | 123 Street Name |
| PHONE      | User's Phone Number                    | String    | 255    | 123-456-7890    |
| ROLE       | User's Role (Customer/Admin)           | String    | 50     | Customer        |
| CREATED_AT | Timestamp of Account Creation          | DateTime  |        | 2024-08-23 12:00|

##### Table 2: PRODUCTS

| FIELD NAME | DESCRIPTION                              | DATA TYPE | LENGTH | SAMPLE        |
|------------|------------------------------------------|-----------|--------|---------------|
| PRODUCT_ID | Unique Product Identification            | String    | 255    | PRD123456     |
| NAME       | Product Name                             | String    | 255    | Wireless Mouse|
| BRAND      | Product Brand                            | String    | 255    | Logitech      |
| DESCRIPTION| Product Description                      | Text      |        | High-quality wireless mouse with ergonomic design|
| PRICE      | Product Price                            | Decimal   |        | 29.99         |
| STOCK      | Quantity Available in Stock              | Integer   |        | 100           |
| CATEGORY   | Product Category                         | String    | 255    | Electronics   |
| SKU        | Stock Keeping Unit                       | String    | 255    | SKU123456     |
| IMAGE_URL  | URL to Product Image                     | String    | 255    | https://example.com/image.jpg |
| CREATED_AT | Timestamp of Product Creation            | DateTime  |        | 2024-08-23 12:00|

##### Table 3: ORDERS

| FIELD NAME  | DESCRIPTION                             | DATA TYPE | LENGTH | SAMPLE         |
|-------------|-----------------------------------------|-----------|--------|----------------|
| ORDER_ID    | Unique Order Identification             | String    | 255    | ORD123456      |
| USER_ID     | User who placed the order               | String    | 255    | USR123456      |
| TOTAL_AMOUNT| Total Order Amount                      | Decimal   |        | 199.99         |
| STATUS      | Order Status (Pending, Shipped, Delivered, Cancelled) | String | 50 | Shipped        |
| CREATED_AT  | Timestamp of Order Creation             | DateTime  |        | 2024-08-23 12:30|

##### Table 4: ORDER_ITEMS

| FIELD NAME   | DESCRIPTION                            | DATA TYPE | LENGTH | SAMPLE         |
|--------------|----------------------------------------|-----------|--------|----------------|
| ORDER_ITEM_ID| Unique Order Item Identification       | String    | 255    | ORDITM123456   |
| ORDER_ID     | Associated Order                       | String    | 255    | ORD123456      |
| PRODUCT_ID   | Product Ordered                        | String    | 255    | PRD123456      |
| QUANTITY     | Quantity of the Product Ordered        | Integer   |        | 2              |
| PRICE        | Price of the Product at the time of Order | Decimal | | 29.99         |

##### Table 5: REVIEWS

| FIELD NAME  | DESCRIPTION                            | DATA TYPE | LENGTH | SAMPLE         |
|-------------|----------------------------------------|-----------|--------|----------------|
| REVIEW_ID   | Unique Review Identification           | String    | 255    | REV123   |




## ERD

For Best View
[https://www.figma.com/file/OXqoeVy3G1U1d3NSjdelYO/UMAK-LIBRARY-ERD?node-
id=0%3A1&t=rUvRxPi6Dcy35dHu](https://lucid.app/lucidchart/cb397712-eaf6-4628-848d-0a3fad767ea2/view)


![image](https://github.com/user-attachments/assets/4f710066-ea28-4e4c-91a8-df0d328a51fe)




## Non Functional Requirements

### Product Requirement (PLEASE SKIP THIS)

### Organizational Requirement (PLEASE SKIP THIS)


### External Requirements  (PLEASE SKIP THIS)


## System Testing and Evaluation   (PLEASE SKIP THIS)

### Functional Testing Procedure   (PLEASE SKIP THIS)

### Functional Testing Summary

### Evaluation Procedure

### Recommendation






### Wireframe (PLEASE SKIP THIS)



### High Fidelity (PLEASE SKIP THIS)



### System Screenshot (PLEASE SKIP THIS)
