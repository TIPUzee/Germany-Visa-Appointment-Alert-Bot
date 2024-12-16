# Germany Visa Appointment Alert Bot  
#### For Pakistani Students  

This bot monitors the availability of appointments for German Student Visa applications for Pakistani students. It provides real-time alerts through audio notifications when appointments become available.  

---

## Features  

- **Appointment Monitoring**: Automatically checks the visa application pages for appointment availability.  
- **Real-Time Alerts**: Plays a continuous alert sound when an appointment is available.  
- **Multiple Modes**:  
  - **Web Mode**: Runs the bot with a browser interface for visibility.  
  - **Headless Mode**: Operates in the background without a visible browser (better for performance & slower connections).  
- **Error Notifications**: Audio alerts for connection issues or timeouts.  
- **Automated Browser Recovery**: Reopens the browser if it is accidentally closed while the bot is running.  

---

## Important Notices  

### **Do Not Book Appointments Using the Bot-Controlled Browser**  
- The bot-controlled browser is solely for monitoring and might be refreshed or closed by the bot during its operation.  
- To avoid disruptions, **do not attempt to book appointments within the bot-controlled browser window**.  
- Always use a separate browser window or device to log in and complete the booking process once notified of available appointments.  

---

## Requirements  

1. **Chrome Browser**  
   - Ensure that Google Chrome is installed on your system for the bot to function properly.  

2. **Python (Optional)**  
   - If the bot encounters errors, try installing Python from [Python.org](https://www.python.org/) and ensure it's added to your system PATH.  

3. **Contact Support**  
   - For persistent issues, reach out to the contributors via WhatsApp or email. Visit the [GitHub profile](https://github.com/TIPUzee) for contact details.  

---

## Getting Started  

### Using the Bot  

1. **Web Mode**:  
   - Run the `_run_web.exe` file.  
   - A browser window will open, and the bot will start monitoring the visa appointment website.  
   - When an appointment is available, an alert sound will play continuously until the browser window is closed.  
   - Closing the terminal stops the bot, but the browser might remain open.  

2. **Headless Mode**:  
   - Run the `_run_headless.exe` file to monitor the website in the background.  
   - The bot will check for appointments without a visible browser window.  
   - Alerts will play when an appointment is found, and the bot can be stopped by closing the terminal.  
   - The bot might be running in the background for a few seconds after the terminal is closed.  

---

### Naming Conventions for Executables  

- **Web Mode**: `_run_web.exe`  
- **Headless Mode**: `_run_headless.exe`  
- **File Suffixes**:  
  - `HL`: `HeadLess` Indicates headless mode.  
  - `BP`: `Booking Page` Monitors the Booking Page for appointments. [Link](https://service2.diplo.de/rktermin/extern/appointment_showForm.do?locationCode=isla&realmId=108&categoryId=1600)  
  - `LP`: `List Page` Monitors the List Page for visa appointments. [Link](https://service2.diplo.de/rktermin/extern/choose_categoryList.do?locationCode=isla&realmId=108)  
  - `TC`: `Textual Change` Detects textual changes on the monitored pages.  
  - `TE`: `Text Existence` Checks for specific text (e.g., "stud" for List Page or "summer" for Booking Page).  

---

### Audio Notifications  

- **Appointment Available**: Continuous beep every 5 seconds until stopped.  
- **Connection/Timeout Issues**: Two short beeps of 0.75 seconds each.  
- **Regular Monitoring**: A short beep of 0.1 seconds every time the bot checks the website.  

---

## Contributing  

We welcome contributions! If you’d like to improve or extend the bot’s functionality:  
1. Fork the repository.  
2. Implement your changes.  
3. Submit a pull request for review.  

**Repository Link:** [Placeholder](https://github.com/TIPUzee/germany-visa-appointment-alert-bot)  

---

## License  

This project is licensed under the [APACHE-2.0 License](https://www.apache.org/licenses/LICENSE-2.0).  

---

## Contributors  

- [TIPUzee](https://github.com/TIPUzee)  
