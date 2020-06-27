# UserSessionDetection
Machine Learning Model to Uniquely Identify a User From Browser Sessions

The dataset contains data about user sessions that have been recorded over a period of time.
Each session is represented by a JSON object with the following fields:
- “user_id” is the unique identifier of the user.
- “browser”, “os”, “locale” contain info about the software on the user’s machine.
- “gender”, “location” give analytics data about the user.
- “date” and “time” is the moment when the session started (in GMT).
- “sites” is a list of up to 15 sites visited during the session. For each site, the url and the length of visit in seconds are given.
The goal is to create a method to identify the user with id=0 specifically.
