## .ENV FILE STRUCTURE

**EMAIL_API_KEY** = mailjet api_key <br />
**EMAIL_API_SECRET** = mailjet api_secret <br />
**PLANETS_REFRESH_RATE** = number in seconds <br />

## PROJECT DESCRIPTION

Flask based python web app. Provides user with newsletter notifying them when NASA discovers a new planet. <br />
Planet data is fetched from NASA API at https://exoplanetarchive.ipac.caltech.edu/TAP/ <br />
Upade frequency is determined by PLANETS_REFRESH_RATE key in .env file and then compared with data in the database. <br />
<br />
Users can remove themselves from the newsletter list by clicking a link in the email they receive. <br />
