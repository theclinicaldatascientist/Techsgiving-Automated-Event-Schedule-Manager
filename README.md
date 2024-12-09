# Techsgiving-Automated-Event-Schedule-Manager
Automate conference schedule management with Techsgiving's scalable solution!

Case Study

Client: Non-Profit Organization Supporting Tech Education

The non-profit organization Techsgiving required a scalable, automated solution to efficiently manage its event schedule for an annual conference. The challenge was to extract session details from the event’s HTML-based schedule, organize the data for use in a Google Sheet, and automate the process of sending reminders via calendar invites and SMS notifications to registered attendees.

Objective:

Extract and parse session details from the conference schedule webpage.
Structure the data into a Google Sheet for real-time management.
Automate the creation of calendar events and dispatch of SMS/email reminders for attendee engagement.

Impact:

Efficient Data Management: Eliminated manual input and updates for conference sessions.
Enhanced Engagement: Automated notifications boosted attendee awareness and participation.
Improved Accessibility: Seamlessly integrated schedules into personal calendars for attendees.

Solution Overview

Workflow

- HTML Parsing: Extract relevant session information from the event schedule page.
- Data Structuring: Organize the parsed information into a Google Sheet for easy management.
- Automation:
Generate Google Calendar events based on attendee preferences.
Send SMS and email reminders for confirmed sessions.

Implementation Details
1. HTML Parsing and Data Extraction

Key session details extracted included:

Date
Start and End Time
Session Title
Track
Speakers
Description
Location

Tools and Techniques:

Web Scraping: Leveraged Python libraries such as BeautifulSoup for parsing HTML.
Regular Expressions: Used for precise extraction of specific data fields.


2. Data Structuring

Google Sheets Integration: Used the Google Sheets API to store and manage session details in a structured format, enabling collaborative and real-time updates.

3. Automation

Google Calendar Integration: Automated the creation of calendar events using the Google Calendar API.
Notifications:
SMS: Leveraged Twilio’s API to send reminders.
Email: Used Google Apps Script to send email updates and confirmations.

Technical Features
Python and Google Apps Script: Unified solution for data extraction, processing, and notification automation.
API Integration: Seamless communication with Google Workspace and Twilio APIs.
Scalability: System designed to accommodate schedule updates and support additional notification options.

Results

Reduced Manual Effort: Fully automated workflows saved significant administrative time.
Increased Attendance: Timely reminders resulted in higher session attendance rates.
Reusable Framework: Solution adaptable for future events and other non-profit organizations.


Future Enhancements

Improved Error Handling: Enhance resilience to malformed HTML and missing data.
User Customization: Enable attendees to select specific sessions of interest for tailored reminders.
Extended Integration: Add support for communication platforms such as Slack and WhatsApp.
