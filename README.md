# VFS Appointment Bot
The VFS Appointment Bot is a Python script that automates the process of checking for available visa appointment slots on the VFS website. 
The script uses Selenium WebDriver to navigate the website and search for available appointments, and can be customized to check for appointments at specific VFS centers.

## Motivation
The VFS Appointment Bot was created to help individuals who were struggling to find available visa appointments on the VFS website. 
I personally experienced this issue and decided to create a solution that would automate the appointment scheduling process 
and improve chances of securing an appointment.

## Features
- Automated appointment searching: The script automatically navigates to the VFS website and searches for available appointments based on the user's preferences.
- Customizable search criteria: Users can specify their preferred VFS center, appointment date range, and other search criteria to optimize their chances of finding available appointments.
- Email notification: When an available appointment is found, the script sends an email to the subscribed mailing list, notifying users of the appointment details and allowing them to quickly reserve the appointment.
- Logging of attempts: The script logs all attempts, including failed login attempts, in order to help identify issues and troubleshoot any problems that may arise.
- Regular operation: The script runs regularly every 5 minutes in order to prevent being blocked from the website.

## Getting Started
To use the VFS Appointment Bot, follow these steps:

- Install Python and Selenium WebDriver on your system.
- Clone the repository to your local machine.
- Run ```pip install selenium```
- Run VFS-Bot.py to start the script.
