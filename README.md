# Reminder-Notification-System-using-Python
This Python script allows you to set a reminder for a task after a specific interval. When the time is up, a desktop notification will appear with your task.

Features

Set a task reminder.

Set the interval time in minutes.

Receive a desktop notification when the reminder time is reached.

Requirements

Python 3.x installed on your system.

plyer library to show notifications.

Installation
1. Install Python (if not already installed)

Check if Python is installed:

python --version


If not installed, download and install from Python.org
.

2. Install plyer library

Open the Command Prompt (Windows) or Terminal (macOS) and run:

Windows:

pip install plyer


macOS:

pip3 install plyer


Note: On macOS, you may need to use pip3 depending on your Python installation.

How to Use

Open your Python IDE or text editor and paste the script.

Run the script:

python reminder.py    # Windows
python3 reminder.py   # macOS


Enter the task you want to be reminded of.

Enter the interval time in minutes.

Wait for the notification. A desktop notification will appear when the time is up.
Notes

time.sleep(1) is used to reduce CPU usage.

Make sure notifications are allowed on your system for Pyt
