# Restaurant Booking Web Application

## Description
The **Restaurant Booking Web Application** is a simple and efficient platform for managing restaurant reservations. Users can:

- Browse available tables for a specific date and time.
- Make reservations by providing their details.
- View and cancel existing reservations.



## Features
- **Browse Availability**: Check available tables based on date, time, and party size.
- **Reservation Management**: Make, view, and cancel reservations effortlessly.
- **Responsive Design**: Optimized for use on desktops, tablets, and mobile devices.

---

## Technologies Used
- **Python:** The primary programming language.
- **Tkinter:** A standard GUI toolkit for Python, used for creating the graphical user interface.
- **Custom Data Structures:** The project uses custom data structures (NODE, QUEUE) defined in the data_structure.py file.

---

## Setup Instructions

**1.Install Python:**
  Ensure that Python is installed on your system. You can download it from the official website: python.org.
  Verify the installation by running the following command in your terminal:
  python --version
  Set Up a Virtual Environment (Optional but Recommended):

**2.Navigate to the project directory:**
  cd d:/New folder
  Create a virtual environment:
    python -m venv venv
  Activate the virtual environment:
  On Windows:
    venv\Scripts\activate
  On macOS/Linux:
    source venv/bin/activate

**3.Install Required Libraries:**
  Since this project uses Tkinter, which is included with Python, no additional installations are necessary for Tkinter.
  pip install tkinter

**4.Run the Application:**
  Ensure you are in the project directory and run the main.py file:
  python main.py

**5.Using the Application:**
  The application will open a GUI window for restaurant booking. You can enter the name and number of people to make a booking.

---

## Project Structure
```
/project-root
│
├── main.py                # Main entry point for the application
├── gui.py                 # Contains the GUI implementation using Tkinter
├── data_structure.py      # Defines custom data structures (e.g., NODE, QUEUE)
└── README.md              # (Optional) Documentation for the project
```

---

## Screenshots
- **Homepage**: Screenshot showing the homepage with available table options.
- **Reservation Confirmation**: Screenshot showing the confirmation page after a successful reservation.
- **My Reservations**: Screenshot displaying the list of reservations with options to cancel.
![image](https://github.com/user-attachments/assets/78e6178d-4649-4a47-aed6-b7f13d1ee3eb)

---

## Future Enhancements
- **User Accounts**: Enable users to create accounts and save reservation history.
- **Payment Integration**: Add online payment options for deposits or full payments.
- **Advanced Filters**: Allow filtering by cuisine, location, and table preferences.
- **Notifications**: Send email or SMS reminders for upcoming reservations.

---



