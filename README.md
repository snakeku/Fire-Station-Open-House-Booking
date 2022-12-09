# FireStation Open-House Booking
#### Conceptualised 2 MVP to handle Fire Station Visit Bookings using either Mobile Application or a Web app

---


## [Table of contents](#table-of-contents)
1. [Project Context](#projectcontext)
2. [Ideas](#ideas)
3. [Project Stack](#projectstack)

---
## [ProjectContext](#projectcontext)

## What's the problem?
In 2020 during the pandemic, people who wished to visit a Fire Station had to book their appointment using a Google Form. There were 2 sessions in each day to a maximum of 5 pax per session for the Visit. Users will have to wait for the admin personnel to approve/reject their applications and the process was rather manual. Additionally, even if the slots were full for that day, there wasn't any logic to prevent users from signing up for that day, leaving the admin having to manually reject their applications.
This creates unnecessary stress and is a needless workload for the admin.

<img src="Images/convertedGIF.gif"  height="500" >

<div align="right">[ <a href="#table-of-contents">↑ to top ↑</a> ]</div>


## [Ideas](#ideas) 

## Proposal 1:
- Utilising Google Form, Cloud Database and a mobile App
> What this solution offer is to ease the menial job of sending rejection emails.
Google Form will collect the information filled by the user and store it into a Cloud Database via AppScript. The admin personnel will then have an overview of all the applications made and it is filterable by stations via the mobile app. The app will also automatically reject when it is >5 pax or when the session is already booked. Once all the sessions are booked, for any following application made, the user will receive a rejection email.

<br />

### Showcase (Mobile App):

<img src="ToBeUploaded/Mobile MVP.png"  height="800" >


## Proposal 2:
- Utilising a WebApp with Cloud Database
> Users can immediately glance through the dates availability at the first glance. Users will also receive an email stating their booking summary right after their booking. This would eliminate the need for a middle man to manually approve requests.

<br />

### Showcase(WebApp):

<img src="ToBeUploaded/WebApp.gif" >

<br />

**Email Template**
<br />
<img src="ToBeUploaded/FrontPage.png"  height="500" > 
<img src="ToBeUploaded/BackPage.png"  height="500" > 
<br />
<img src="ToBeUploaded/Email.png"  height="500" >








<div align="right">[ <a href="#table-of-contents">↑ to top ↑</a> ]</div>

---

## [ProjectStack](#projectstack) 
These are the tech stack that I used to develop this project.

<pre>
Mobile & Web: Flutter
Database: Firestore NoSQL Database
Cloud Messaging: Firebase
Typescript
Google API
Google Appscript
</pre>


App was distributed via Firebase and TestFlight.

<img src="https://user-images.githubusercontent.com/47912781/206226953-a00dd140-a476-4995-b254-86527b792906.png"  height="150" >
<img src="https://user-images.githubusercontent.com/47912781/206661015-51de10a7-fad7-4bf6-a506-da546de688fb.png"  height="150" >




<div align="right">[ <a href="#table-of-contents">↑ to top ↑</a> ]</div>





