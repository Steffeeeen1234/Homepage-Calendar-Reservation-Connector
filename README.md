# Homepage Calendar Reservation Connector
# Vision
Make reservations at doctors and craftsman (such as plumbers) as easy as reserving a table at your famous restaurant.

# Introduction
This project is all about digitalization.

In our common world you are able to make a reservation for a seat in a cinema or a table in a fancy restaurant from your smartphone BUT you are not able (in most of the cases in Germany) to make a reservation for a free spot at the doctor (e. g. dentist) or at some technical company (e. g. plumber). 
In those cases. you still must call them. 
Most of the time you will not reach them because:
- no one is answering the phone, 
- are already out of office, 
- are on vacation, 
- etc.

In a world where we have chat bots, voice bots and everything, it is still so hard to make a reservation for a free spot at the doctors office.

Therefore, the vision of this project is: Make reservations at doctors and plumbers as easy as reserving a table at your famous restaurant

# Goals
1. Help to connect these doctors and craftsman (and others) via their homepage to their new clients (e. g. Gen Y and Gen Z). 
1. This project should provide a calendar which can be integrated to your homepage easy. 
1. It should provide a possibility to maintain the time for reservation spots. So that it fits the doctor’s office.
1. It should provide a connector to your favorite calendar (Outlook, Gmail, Notes, or whatsoever).
1. If possible it should be possible for google home, alexa, instagram, facebook, siri, etc. to make a reservation for a free spot via voice.
1. Facebook bots and other bots should be able to use this standard or the connectors as well to make reservations.
1. The source of all of this will be free to use. Even if the company makes money out of this usage. (Todo: find out which license I must set up for this)
1. bring digitalization a step forward to a new area.
1. make it possible to have an easy way to share your company calendar on your company website
1. it also needs to fit in website building tools like wordpress
1. having an all-around service (we should think about it) which includes: optimizing their homepage, setting up and maintaining the bots and calendars, suggesting new dates if the doctor/craftsman has a urgent topic to take care of, sending reminder mails for the customer


# Contribute
Everyone can contribute to this project. 
I am still in the research phase and haven't started to code anything.
The GitHub repro is also not finally set up. If you have any suggestions just go ahead.

All questions and discussions can start here: https://github.com/Steffeeeen1234/Homepage-Calendar-Reservation-Connector/discussions

You can also reach out to me by E-Mail or by opening an issue to this.

# Research

## Research Questions
Q: Is there no possibility to book a doctor’s appointment online?<br>
A: Sure, there are. There is for example this: <br>
- https://www.medorganizer.de/medorganizer/ but they are a company which lives from providing such a service and many more features. 
I think the calendar feature is the most important one and can bring a lot benefit.
- https://www.jameda.de/ 
- this contains a set of other platforms: https://t3n.de/news/arzttermine-online-buchen-1124001/

Q: Why should someone not use the mentioned sites?
A: Because we need more competition.<br>
because the user experience is much better if it is integrated inside the doctors/craftsman homepage. Or if it can be used by Google, Alexa, etc.

Q: Are there any free to use calendar?
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
A: I found the following:<br>
Reserve with google: 
- https://www.google.com/maps/reserve/; https://developers.google.com/maps-booking
- A project which has implemented it: https://github.com/tchssk/reserve-with-google-goa

Q: Are there examples on github for doctors’ websites?


Q: Why do so many doctors have no website?<br>
Q: Why do so many doctors have no possibility to book a meeting online?<br>
Q: Why are they not using online meetings?<br>

Q: how to connect to Google, Outlook, etc. calendars via the internet?

# User groups
## Hosts 
Hosts are the once who will invite you (e.g. a doctor or a craftsman)

## Clients
Clients are the normal users who reached the hosts webpage and who wants to reserve an appointment.

# Story Map

## Get an appointment for a doctor you don't know
1. User has a problem
1. User opens search engine (e.g. google)
1. User enters "need general doctors in berlin"
1. User chooses the one with the best recommendation 
1. 

## Get an appointment for a doctor you know
1. find the doctors phone number over search engine
1. call the phone number
1. wait

# User Stories
## Hosts
As host I want to maintain the free spots I have for the clients.<br>
As host I want to give a possibility to fast select the common reason why someone wants a meeting.<br>
As host I want ... .<br>

## Client
As client I want to see when there are spots available.<br>
As client I want to choose why I want a reservation.<br>
As client I want to get a notification if the appointment is confirmed.<br>
As client I want that the notification contains a calendar file so that I can save it to my local calendar.<br>
As client I want to know if it is an online or offline appointment.<br>
As client I want to choose which online appointment method I prefer/want to use. Zoom, Webex, FaceTime, etc.<br>
As client I want to get a reminder e-mail.<br>
As client I want to book a meeting via voice.<br>
As client I want to ... .<br>


# OutOfScope
Building a Website platform. This is already done by many companies e.g. Wordpress.<br>
Setting up online meetings. But maybe we can provide an interface to the commonly used online platforms?


