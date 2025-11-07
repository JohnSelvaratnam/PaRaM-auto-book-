# PaRaM-auto-book-
Autobook PaRaM

for copilot:


Export all my past meeting for the current week and upcoming meeting for this week in a .csv file with the following columns:
day | start_time | end_time | title | description | task | team

Use this example as the template:
Monday    09:00    16:00    Team Meeting    Weekly team sync and updates    skye    cab
Tuesday   09:00    16:00    Team Meeting    Discussion with ABC Corp        skye    cab

Ensure:
- Day is the weekday name (e.g., Monday).
- Times are in 24-hour format (HH:MM).
- Title is the meeting subject.
- Description is the meeting body or agenda.
- Task and team can be left blank if not available.
- Subtract **30 minutes from the end_time** of each meeting.
