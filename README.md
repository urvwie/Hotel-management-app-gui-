## Hotel Management System

The Hotel Management System is a comprehensive desktop application designed to streamline the operations of a hotel. The system is built using Python's Tkinter library for the graphical user interface and MySQL for the database. The application provides separate login screens for admin and guest users, each with specific functionalities tailored to their roles.

### Features

#### General
- **Login Screen**: Users can log in as either an admin or a guest. The login screen ensures that only authorized users can access specific functionalities.
- **User-Friendly Interface**: The application boasts a colorful and intuitive interface, making it easy for users to navigate and use the system.

#### Admin Features
- **Admin Dashboard**: Upon successful login, admins are greeted with a dashboard displaying various management functions.
- **Manage Staff**:
  - **Add Employee**: Admins can add new employees to the system by providing details like employee ID, name, phone number, Aadhaar number, and date of birth.
  - **Search Employee**: Admins can search for employees by ID, phone number, or Aadhaar number.
  - **Edit Employee**: Admins can edit the details of existing employees.
  - **Delete Employee**: Admins can remove employees from the system.
- **Manage Guests**:
  - **Insert Guest**: Admins can add new guests to the system by providing details like room number, name, date of birth, mobile number, Aadhaar number, nationality, and status.
  - **Search Room**: Admins can search for guests based on their room number.
  - **Search Guest**: Admins can search for guests by name.
  - **Delete Guest**: Admins can delete guest records from the system.

#### Guest Features
- **Guest Dashboard**: Upon logging in, guests are presented with a dashboard that allows them to book rooms and view hotel information.
- **Book Room**: Guests can book rooms by entering the room number. The system checks the availability and updates the status accordingly.
- **View Hotel Info**: Guests can view detailed information about the hotel, including descriptions and images of the property.

### Technology Stack
- **Python**: The core programming language used to build the application.
- **Tkinter**: The library used for creating the graphical user interface.
- **MySQL**: The database used for storing hotel, staff, and guest information.

### How to Run the Application
1. **Install Dependencies**: Ensure you have Python and MySQL installed on your system.
2. **Database Setup**: Create a MySQL database named `hotel` and set up the necessary tables (`staff` and `guest`).
3. **Configure Database Connection**: Update the database connection parameters (host, user, password) in the code.
4. **Run the Application**: Execute the script to launch the application.
    ```sh
    python hotel_management.py
    ```

### Code Structure
- **HotelApp Class**: This class encapsulates the entire application, handling the creation of the GUI, managing user logins, and providing various functionalities for both admin and guest users.
- **Login Screen**: Handles user authentication and directs users to the appropriate dashboard.
- **Admin Dashboard**: Provides functionalities for managing staff and guests, including adding, searching, editing, and deleting records.
- **Guest Dashboard**: Allows guests to book rooms and view hotel information.


#screenshots 
![image](https://github.com/user-attachments/assets/d25377d7-5e5e-43d5-9cf5-b3c5dff6d6a1)
![image](https://github.com/user-attachments/assets/3a165f84-6372-428b-9674-e301e9ab94a0)
![image](https://github.com/user-attachments/assets/b312ee79-adac-41d6-a5f3-74d988633e39)
![image](https://github.com/user-attachments/assets/87700ad5-0142-4ba2-a5f1-71a7904d2cc1)
![image](https://github.com/user-attachments/assets/f1cb60a4-8e5d-4b24-b51c-859e120b5903)
![image](https://github.com/user-attachments/assets/31dc9d41-d77e-485b-b6cd-84b1c2b1b31c)







### Future Enhancements
- **Enhanced Security**: Implement more robust security measures for user authentication and data protection.
- **Additional Features**: Add functionalities like room service requests, billing, and reporting.
- **Improved UI**: Further enhance the user interface to provide a more modern and seamless user experience.

### Conclusion
The Hotel Management System is a powerful tool designed to simplify the management of hotel operations. With its user-friendly interface and comprehensive features, it aims to improve efficiency and enhance the guest experience. Whether you are an admin managing staff and guests or a guest booking a room, this application provides a seamless and intuitive experience.
