# 🌐 Smart Web Launcher using Python

## Overview

Smart Web Launcher is a Python-based automation tool that simplifies daily web browsing activities. The application automatically opens predefined websites during a specified time window and provides a menu-driven interface for launching popular websites and performing Google searches directly from the terminal.

This project demonstrates the use of Python's built-in webbrowser module, automation concepts, user interaction, and time-based task execution.

---

## Features

### Automated Website Launch

* Automatically opens favorite websites during morning hours.
* Configurable website list.
* Time-based execution.

### Quick Access Menu

* Open Google
* Open YouTube
* Open GitHub
* Open Gmail

### Google Search Integration

* Search any topic directly from the application.
* Automatically launches search results in the default browser.

### User-Friendly Interface

* Console-based menu system.
* Continuous operation until user exits.

---

## Technologies Used

* Python 3
* Webbrowser Module
* Datetime Module

---

## Project Workflow

```text
Start Application
        │
        ▼
Check Current Time
        │
        ▼
Morning Time?
   ┌────┴────┐
   │         │
  Yes       No
   │         │
   ▼         ▼
Open Daily   Continue
Websites     Program

        ▼
Display Menu

1. Google
2. YouTube
3. GitHub
4. Gmail
5. Search Google
6. Exit

        ▼
User Selection

        ▼
Open Website / Search
```

---

## Project Demonstration

### Application Startup

The application checks the current time and automatically opens predefined websites if it is within the configured morning schedule.

<p align="center">
  <img src="images/startup_screen.png" width="700">
</p>

---

### Main Menu

The user is presented with a menu-driven interface for quick website access.

<p align="center">
  <img src="Images/main menu.png" width="700">
</p>

---

### Open Google

Launches Google in the default browser.

<p align="center">
  <img src="images/Images/Open Google.png" width="700">
</p>

---

### Open YouTube

Launches YouTube in the default browser.

<p align="center">
  <img src="images/Images/Open Youtube.pngyoutube_open.png" width="700">
</p>

---

### Open GitHub

Launches GitHub in the default browser.

<p align="center">
  <img src="Images/Open Githhub.png" width="700">
</p>

---

### Open Gmail

Launches Gmail in the default browser.

<p align="center">
  <img src="Images/Open Gmail.png" width="700">
</p>

---

### Google Search

Allows users to search any topic directly from the application.

<p align="center">
  <img src="Images/Search on Google.png" width="700">
</p>

---

## Installation

```bash
git clone https://github.com/yourusername/smart-web-launcher.git

cd smart-web-launcher

python web.py
```

---

## Configuration

Modify the DAILY_SITES list to customize websites:

```python
DAILY_SITES = [
    "https://mail.google.com",
    "https://www.youtube.com",
    "https://news.google.com"
]
```

---

## Future Enhancements

* GUI Interface using Tkinter
* Voice Command Support
* Website Categories
* Scheduled Tasks
* Browser Selection Option
* Bookmark Management
* Weather and News Dashboard
* AI-Based Productivity Assistant

---

## Learning Outcomes

* Python Programming
* Browser Automation
* Time-Based Automation
* User Interaction
* Menu-Driven Applications
* Python Standard Libraries

---

## Author

### Raja Ratnam Pilli

Python Developer | Embedded Systems Engineer | Automation Enthusiast
