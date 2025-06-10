This is a basic shopping cart application using JSP and Servlets.
Deployed on Apache Tomcat and connected to a database for dynamic operations.
Register Page (register.html) collects user data (username, email, password) and sends it to AppController to store in the database.
Login Page (login.html) verifies user credentials by posting data to the servlet.
The Product Catalog (JSP) displays items retrieved from the database using ResultSet and request.setAttribute("products", resultSet).
Each product has an "Add to Cart" button that sends data to AppController to update the user’s cart.
The Cart Page (JSP) shows all selected items using another ResultSet from request.setAttribute("cartItems", resultSet).
An Error Page displays a static message when something goes wrong.
All pages are styled consistently using a shared style.css file.
The Java JDK is required for development; environment variable JAVA_HOME must be set.
Apache Tomcat is installed and configured by setting CATALINA_HOME.
Start Tomcat by running startup.bat from the bin directory.
The app is deployed in C:\Tomcat\webapps\MyCartApp.
.jsp and static files go in the root; .class files go in WEB-INF/classes.
After deployment, visit http://localhost:8080/MyCartApp in the browser.
The backend logic is handled by a servlet named AppController.java.
This controller manages all user actions, database communication, and page navigation.
Data between servlet and JSPs is passed using request.setAttribute().
The project provides a simple and complete flow for a basic e-commerce app.
![image](https://github.com/user-attachments/assets/4546c463-a5d7-4841-9d08-b5b5ea6aa944)
![image](https://github.com/user-attachments/assets/d61718fa-c523-49e7-a62b-7b9e7d5d7b08)
![image](https://github.com/user-attachments/assets/a0dd2732-6449-40e4-9d7d-a8796322124e)
![image](https://github.com/user-attachments/assets/e1e660b0-a2e1-4a0e-8ba9-19d1f8f1d57b)
![image](https://github.com/user-attachments/assets/b8304a9c-6e98-409a-bf4a-b240ded999df)
