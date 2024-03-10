# Electricity-Billing-System

## Overview:

This C++ project implements an Electricity-Billing-System that allows for the management of residential and commercial customers. The system enables the registration of customers, calculation of their energy consumption bills, and dynamic adjustment of appliance rates for both residential and commercial entities.

## Features:

### 1. Customer Classes:

#### a. **Customer:**
- Base class for both residential and commercial customers.
- Manages customer information such as name, address, contact details, and customer type.

#### b. **ResidentialCustomer:**
- Derived from the Customer class.
- Manages additional information specific to residential customers, such as rates for fan, bulbs, and TV, as well as hours of usage.

#### c. **CommercialCustomer:**
- Derived from the Customer class.
- Manages additional information specific to commercial customers, such as rates for oven, food processor, microwave, printer, and computer, as well as hours of usage for different appliances.

### 2. Admin Class:

- Manages the login credentials for system administrators.

### 3. Functionalities:

#### a. **Rate Management:**
- Allows the administrator to dynamically change the rates of appliances for residential and commercial customers.

#### b. **Display Rates:**
- Enables the administrator to view the current rates of appliances for both customer types.

#### c. **Customer Registration:**
- Facilitates the registration of new customers, gathering relevant information based on customer type (residential or commercial).

### 4. File Handling:

- Utilizes file handling to store and retrieve customer information and appliance rates.

## Implementation:

### 1. Customer Classes:

- Utilizes class inheritance to create a base class (`customer`) and two derived classes (`Residentialcustomer` and `Commercialcustomer`) to manage different types of customers.

### 2. File Handling:

- Employs file handling for storing customer details and appliance rates persistently.

### 3. Object-Oriented Design:

- Utilizes object-oriented principles to encapsulate customer-related functionalities within the respective classes.

### 4. User Interaction:

- Implements a simple console-based user interface for administrator interactions, with options to change rates, display rates, and register new customers.

## How to Use:

1. **Compilation:**
   - Compile the source code using a C++ compiler.

2. **Execution:**
   - Run the compiled executable.

3. **Admin Credentials:**
   - Upon the first run, if no admin credentials are present, the system will prompt for new admin credentials.

4. **Main Menu:**
   - After setting up admin credentials, the main menu will provide options to manage residential and commercial customer rates or register new customers.

5. **Navigation:**
   - Follow on-screen instructions to navigate through different functionalities and perform desired tasks.

## Note:

- This readme assumes that you have a basic understanding of C++ programming and file handling.

## Credits:

This project was developed as part of the Object-Oriented Programming (OOP) course during the second semester.

**Developers:**
- Syeda Hajra
- Zohaib Saqib
- Aqsa Shahbaz
