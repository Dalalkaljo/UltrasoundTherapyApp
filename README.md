# UltrasoundTherapyApp
# Pulse Soothe

**Pulse Soothe** is a Python application developed using **PyCharm IDE** and converted into a standalone executable for **Windows** using **PyInstaller**.  

## Dependencies and Libraries
The application relies on Python along with several libraries to extend its functionality:  
- **Kivy & KivyMD**: for designing the user interface, menus, and tables.  
- **SQLite3**: for storing and retrieving patient data.  
- **Matplotlib**: for creating charts and analyzing data.  

## Application Structure and User Experience
The application consists of four main screens with a navigation menu available on each screen. The menu also allows switching between light and dark modes, with scrollable first and third screens for easier viewing.

### Screen 1
Provides brief instructions for using the application:  
1. Enter the patient's personal information and session details.  
2. Set the therapy parameters and start the device.  
3. Apply the gel to the target area and move the probe in circular motions to deliver ultrasound waves.  
4. At the end of the session, an audible alarm and a short red blinking light notify the user to stop the device, followed by cleaning the treated area.  

### Screen 2
Patient identification card for entering basic information: name, age, target area, pain type (acute or chronic), and the number of sessions.  
- The data is saved to a file to support custom databases for physiotherapy pain management, ultrasound therapy, and research purposes.  

### Screen 3
Allows entry of the user name, session date, session number, and therapy parameters (frequency, duty cycle, and duration) to be sent to the device.  
- Includes a timer to notify the end of the session.  
- Progress tracking: Patients rate their pain using the **Numerical Rating Scale (NRS) 0–10** before and after each session to monitor therapy effectiveness.  
- Data is automatically stored in the SQLite database and displayed in Screen 4.  

### Screen 4
Displays a table of patient data with the ability to:  
- Show a chart of pain reduction percentage for a selected patient after each session.  
- Sort by name.  
- Save charts to the device, adjust their dimensions, and use zoom to focus on specific data.

## Notes
The application is designed to support physiotherapy management for acute and chronic pain, enabling accurate tracking and documentation of therapy sessions.

## Notes
The application is designed to support physiotherapy management for acute and chronic pain, enabling accurate tracking and documentation of therapy sessions.
