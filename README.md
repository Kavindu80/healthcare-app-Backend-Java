# Doc-Connect Healthcare Application

## Project Overview

The **Doc-Connect Healthcare Application** is a Java-based project designed to implement core Object-Oriented Programming (OOP) principles for patient management. The application facilitates doctor availability management, appointment scheduling, and patient booking. It operates via a simple text-based interface, enabling easy interaction for both hospital administrators and patients.

## Core Functionality

### 1. Doctor Availability Management
- **Input Availabilities:** Doctors can input their availabilities by specifying a date. The default availability time is set from 5 PM to 10 PM.
- **Variable Availabilities:** The system can handle different availabilities for different dates and times.

### 2. Appointment Slots
- **Types of Appointments:** The application supports two types of appointments: General and Referral.
- **Slot Management:** Appointment slots are fixed at 1-hour intervals. The system dynamically calculates the appointment time based on the number of slots booked for the day.

### 3. Patient Booking
- **Booking Process:** Patients can select a doctor and a desired appointment date. The system will display available slots for the selected doctor.
- **Slot Protection:** The system prevents multiple bookings for the same slot.

### 4. Doctor and Patient Information
- **Doctor List:** The system presents a list of all registered doctors.
- **View Bookings:** Doctors can view a list of their scheduled patients for a specific date.

## Technologies Used
- **Java:** Programming language
- **IDE of Choice:** Compatible with Eclipse, IntelliJ IDEA, etc.

## Project Structure

### 1. Classes and OOP Concepts
- **Interfaces:** To generalize structures like `Person`, `Appointment`.
- **Doctor Class:** Holds attributes like name, specialization, and availability.
- **Patient Class:** Holds attributes like name, contact information, and bookings.
- **Appointment Classes:** `GeneralAppointment` and `ReferralAppointment` to handle different appointment types.
- **Main Class:** Manages the overall system logic.

### 2. Data Structures
- **Doctor Availabilities:** Managed using `HashMap` or `ArrayList`.
- **Appointments:** Stored in an `ArrayList`.

### 3. User Interface
- **Text-Based:** Uses the `Scanner` class for user input.

### 4. System Logic
- **Menu Options:**
  - "Add Doctor"
  - "Add Doctor Availability"
  - "View Doctors"
  - "Book Appointment"
  - "View Doctor's Bookings"
  - "Exit"
- **Handling User Input:** Managed using conditional statements and loops.
- **Appointment Algorithm:** Calculates slot times based on doctor's availability and booked slots.

### 5. Simplifications
- **In-Memory Data Storage:** No data persistence; data is stored in memory.
- **Text-Based UI:** Simplified for this project; can be extended to a GUI in the future.

## Week-by-Week Implementation

### Week 3: Conditional Statements
- Handle user input for selecting options in the main menu.

### Week 4: Loops
- Implement loops to allow recursive user input until the exit is selected.

### Week 5: Methods and Functions
- Modularize the code by creating methods for handling different functionalities.

### Week 6: Classes and OOP
- Implement the `Doctor` and `Patient` classes with necessary methods.

### Week 7: Arrays and ArrayLists
- Implement the functionality for adding new doctors and viewing all doctors.

### Week 8: HashMaps
- Add doctor availability management and implement the appointment booking logic.

### Week 9: Inheritance and Encapsulation
- Create an abstract `Person` class and extend it for `Doctor` and `Patient` classes.

### Week 10 & 11: Abstraction and Polymorphism
- Create `GeneralAppointment` and `ReferralAppointment` classes by extending an abstract `Appointment` class. Modify the booking logic to handle both types of appointments.

## How to Run

1. **Clone the Repository:** 
   ```bash
   git clone https://github.com/username/Doc-Connect.git
