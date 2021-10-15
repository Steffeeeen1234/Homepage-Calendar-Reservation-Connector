# Homepage Calendar Reservation Connector
## Vision
Make reservations for appointments at a doctor and / or a craftsman (such as plumbers) as easy as reserving a table at your famous restaurant.

## Introduction
This project is all about digitalization.

In our common world you are able to make a reservation for a seat in a cinema or to book a table in a fancy restaurant from your smartphone BUT you are not able (in most of the cases in Germany) to make a reservation for a free spot at the doctor (e. g. dentist) or at some technical company (e. g. plumber). 
In those cases you must call them still.
Most of the time you will not reach them because:
- no one is answering the phone, 
- are already out of office, 
- are on vacation, 
- etc.

In a world where we have chat bots, voice bots and everything, it is still so hard to make a reservation for a free spot at the doctors office.

Therefore, the vision of this project is: Make reservations for appointments at a doctor and / or a craftsman (such as plumbers) as easy as reserving a table at your famous restaurant.

## Goals
1. Help to connect these doctors and craftsman (and others) via their homepage to their new clients (e. g. Gen Y and Gen Z). 
1. This project should provide a calendar which can be integrated to your homepage easy. 
1. It should provide a possibility to maintain the time for reservation spots. So that it fits the doctor’s office.
1. It should provide a connector to your favorite calendar (Outlook, Gmail, Notes, or whatsoever).
1. If possible it should be possible for google home, alexa, instagram, facebook, siri, etc. to make a reservation for a free spot via voice.
1. Facebook bots and other bots should be able to use this standard or the connectors as well to make reservations.
1. The source of all of this will be free to use. Even if the company makes money out of this usage. (Todo: find out which license I must set up for this https://github.com/Steffeeeen1234/Homepage-Calendar-Reservation-Connector/projects/1#card-70878849)
1. bring digitalization a step forward to a new area.
1. make it possible to have an easy way to share your company calendar on your company website
1. it also needs to fit in website building tools like wordpress
1. having an all-around service (we should think about it) which includes: optimizing their homepage, setting up and maintaining the bots and calendars, suggesting new dates if the doctor/craftsman has an urgent topic to take care of, sending reminder mails for the customer

## Pros and Cons
from customer/client side <br>
(+) easy booking <br>
(+) no calls needed <br>

from host side <br>
(+) easy handling <br>
(-) to many requests <br>
(+) secretaries can focus on their work

## Contribute
Everyone can contribute to this project. 
I am still in the research phase and haven't started to code anything.
The GitHub repro is also not finally set up. If you have any suggestions just go ahead.

All questions and discussions can start here: https://github.com/Steffeeeen1234/Homepage-Calendar-Reservation-Connector/discussions

You can also reach out to me by E-Mail or by opening an issue to this.

## Research

### Research Questions
Q: Is there no possibility to book a doctor’s appointment online?<br>
A: Sure, there are. There is for example this: <br>
- https://www.medorganizer.de/medorganizer/ but they are a company which lives from providing such a service and many more features. 
I think the calendar feature is the most important one and can bring a lot benefit.
- https://www.jameda.de/ 
- this contains a set of other platforms: https://t3n.de/news/arzttermine-online-buchen-1124001/
- https://www.doctolib.de/

Q: Is there a possibility to make the reservation available over google/maps?<br>
A: I found the following:<br>
Reserve with google: 
- https://www.google.com/maps/reserve/; https://developers.google.com/maps-booking
- A project which has implemented it: https://github.com/tchssk/reserve-with-google-goa <br>

Booking on google
- it is probably the same as reserve with google https://support.google.com/websearch/answer/7015376?co=GENIE.Platform%3DDesktop&hl=en&oco=1 

Appointment URL: https://getreferralmd.com/2017/09/3-new-google-business-features-doctors-increase-appointment-booking/
- can be linked to a booking company or to one landing page where the user can finde the booking details

Q: Why should someone not use the mentioned sites?<br>
A: Because we need more competition.<br>
Because the user experience is much better if it is integrated in the doctors/craftsman homepage. Or if it can be used by Google, Alexa, etc. And I believe there mus be a possibility for those small companies, that they could do it on their own an which is free of charge if they do it on their own.

Q: Are there any free to use calendar?<br>
A: I found this:
- Example on how to connect MS Exchange (https://github.com/DmitryStroganov/TeamCalendar)
- Calendar layout: https://github.com/excid3/simple_calendar
- html calendar: https://github.com/kevinxyc1/Meeting_Scheduler
- https://github.com/peppetort/MeetApp-pureHTML
- reminder mails: https://github.com/v5y8/email_sender

Used search strings on github:
- meeting
- meetings
- schedule meetings html

Q: Is there a calendar standard which can be read by google, bots, other professional meetings sites like jemeda, etc.? Or are there other possibilities for doctors, etc. to get on these sides? <br>
The goal would be that google or the other side crawl the doctors site and get the appointment URL (see above) automatically and inserts it to the business site on google.


Q: Are there examples on github for doctors’ websites?<br>
Q: Why do so many doctors have no website?<br>
Q: Why do so many doctors have no possibility to book a meeting online?<br>
Q: Why are they not using online meetings?<br>

Q: How to connect to Google, Outlook, etc. calendars via the internet?<br>
A: In this it is described how to make timeslotes available for others: https://it.stonybrook.edu/help/kb/creating-bookable-appointment-slots-in-google-calendar

## User groups
### Hosts 
Hosts are the once who will invite you (e.g. a doctor or a craftsman).<br>
Hosts have usually not so much experience with their online appearence, because they think it is not so important for them.<br>

### Clients
Clients are the normal users who reached the hosts webpage and who wants to reserve an appointment.<br>
The clients are usally very into user experience. Easy to use websites, apps, etc. is very important to them.<br>
If they want to contact someone it needs to be NOW. Now can be at any time<br>

## Story Map

The story map shows the happy path of the szenario.

### Get an appointment for a doctor you don't know
1. User has a problem
1. User opens search engine (e.g. google)
1. User enters "need general doctors in berlin"
1. User chooses the one with the best recommendation 
1. User gets directed to the webside of the doctor/ or calls the doctor
1. Call: User reaches the doctors office and gets an appointment
1. Website: User enteres what he wants
2. User gets suggested dates and times
3. User chooses one
4. User gets booking confirmation

### Get an appointment for a doctor you know
1. find the doctors phone number over search engine
1. call the phone number
1. wait
1. Book the appointment

## User Stories

### Client
As client I want to be able to book an appointment after I am done with my work.<br>
As client I want to see when there are spots available.<br>
As client I want to choose why I want a reservation.<br>
As client I want to get a notification if the appointment is confirmed.<br>
As client I want that the notification contains a calendar file so that I can save it to my local calendar.<br>
As client I want to know if it is an online or offline appointment.<br>
As client I want to choose which online appointment method I prefer/want to use. Zoom, Webex, FaceTime, etc.<br>
As client I want to get a reminder e-mail.<br>
As client I want to book a meeting via voice (Siri, Alexa, etc.).<br>
As client I want to know if my appointment gets canceled .<br>
As client I want to provide Information to the doctors e.g. if he has questions up front.<br>
As client I want to have no registration process .<br>
As client I want to be able to put me on a waiting list .<br>
As client I want to be informed if a place is available if I am on the waiting list .<br>
As client I want to know which space I have on the waiting list .<br>
As client I want to ... .<br>

### Hosts
As host I want to maintain the free spots I have for the clients.<br>
As host I want to give a possibility to fast select the common reason why someone wants a meeting.<br>
As host I want to make remote vide calls .<br>
As host I want to ... .<br>

## OutOfScope
Building a Website platform. This is already done by many companies e.g. Wordpress.<br>
Setting up online meetings. But maybe we can provide an interface to the commonly used online platforms?

## Requirements
- create a google business account
- set up some google analytics
- link your business to the business account so that it is available on google
- create a appointment site, where the user can finde all details and where they can book an appointment
