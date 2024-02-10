# Upcoming-PTO-Email
This Google Apps Script automates the process of retrieving upcoming events from a Google Calendar and sending an email summary to a specified recipient. The script allows customization of the calendar ID, recipient email address, and the timeframe for event retrieval. Additionally, it filters events based on specific users (creators) defined in the script. This tool can be useful for teams or organizations looking to streamline communication about upcoming events within a specified timeframe.

## Setup
Go to https://script.google.com/home

Click ‘New script’

Paste in this script and replace the following variable:  
  var calendarId = 'your_calendar_id_here'; // Replace with your calendar ID
  var recipientEmail = 'recipient_email_here'; // Replace with the recipient's email address
  var subjectPrefix = 'Team PTO: Next '; // Prefix for subject line
  var days = 30; // Number of days for event retrieval and email subject
  var specificUsers = [ ]; // List of specific user email addresses (creators) you want to filter by, comma-separated

Save the project.

Click the ‘Play’ button to execute the script.

A dialog will open to ask for additional permissions. Allow access to your calendar.

In the left side menu, click “My Triggers”, the clock icon.

Click “Add trigger”.

Select your script in the `Choose which function to run` list.

Under `Select event source`, select Time-driven and then adjust your desired frequency below.

Save the trigger. 
