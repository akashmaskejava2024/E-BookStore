
# E-BookStore

## Overview

E-BookStore is a role-based online bookstore web application developed using Java Servlets, JSP, and MySQL. The platform offers secure login functionality with session management for both users and administrators. Users can browse, search, and purchase ebooks, while admins have dedicated access to manage book inventory, orders, and user accounts. The application ensures seamless navigation via dynamic JSP pages and maintains session states for a personalized shopping experience.

## Features

- Secure login and session management supporting user and admin roles.  
- Role-based access control ensuring appropriate permissions for browsing and managing content.  
- Dynamic JSP-based user interface providing intuitive navigation and real-time content updates.  
- MySQL backend database for storing user information, books, orders, and admin data.  
- Comprehensive admin panel for managing inventory, orders, and user accounts.

## Technologies Used

- Java Servlets  
- JSP  
- MySQL  
- Apache Tomcat (or compatible servlet container)  
- JDBC for database connectivity

## Prerequisites

- Java JDK 8 or above  
- Apache Tomcat 8+  
- MySQL Database Server 

## Installation & Setup

1. **Clone the repository:**  
   ```bash
   https://github.com/akashmaskejava2024/E-BookStore
   cd e-bookstore
   ```

2. **Setup Database:**  
   - Create the required database and tables in MySQL using provided SQL scripts (if any).  
   - Update database connection parameters in your configuration (e.g., `web.xml` or context files).

3. **Build and Deploy:**  
   - Select the project and click Run on server and select the server and run it by auto deploying the war file fo the project to the server eg. Apache Tomcat 8.5

4. **Access Application:**  
   - Open browser at:  
     `http://localhost:8080/`

## Usage

- Users can register, log in, browse ebooks, and place orders.  
- Administrators log in to manage book inventory.  
- Session management ensures a smooth user experience across multiple pages without loss of data.

## Project Structure

```
/src/main/java       - Servlet source code and business logic  
/src/main/webapp     - JSP pages, static resources (CSS, JS)  
/src/main/webapp     - Configuration files and deployment descriptors  
/src/main/webapp/db  - SQL scripts and schema (optional)  
```
