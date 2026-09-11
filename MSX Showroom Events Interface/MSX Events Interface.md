## Summary

With the completion of the U.S. showroom we have the capacity to host events to boost our profile and develop our business Interests, Want to develop an interface in MSX that will allow us to manage Invites and RSVPs to events.

## Invitee Database (Event Invitees)

**Mockup:**

![alt text](<Event Invitee Database.jpg>)

![alt text](<Add Invitee (Database).jpg>)

This is where we keep track of the contact info for all potential invitees as well as add new invitees. There should be auto-population from various places (Vendors, Customers w/ Accounts, Office Employees) and have the ability to add other potential Invitees.

```
Invitee Object Structure:

Name
Company (Not Mandatory)
Email
Phone (Not Mandatory)
Type
Address (Not Mandatory)
```

## Events Calendar

**Mockup:**

![alt text](<MSX Events Interface Calendar View.jpg>)

As shown in the below mockup; the Calendar View is a meanso of viewing, Month by Month what events are scheduled when. From here there will be a button "New Event" That will open to a creation screen. Additionally there will be 3 categories of events
- *Vendor/Trade Events:* These events will be limited to our existing vendors or people who are in the jewelry business that we may like to grow relations with.
- *Office Events:* These are events that are limited to employees of the Natural Sapphire Company and close guests/family. This could be open to events that select employees have requested the showroom for
- *Customer Events:* These are events that have a wider scope and will be open to customers of NXC and invites can be sent to those customers who've created accounts on the NXC Website and opted in to getting invites 


## Create New Event

**Mockup:**

![alt text](<Create Showroom Event.jpg>)

```
Event Object Structure:

Properties:

Event Name
Event Type
Date and Time
RSVP by Date
[Invitees]
RSVPs
Description
Location *This refers to the section/s of the US Office where the event will be held*
{Invitation} *Should be editable from the Event Description screen and should allow for an upload of a JPG or HTML file that will correspond to an email that will be sent out*
```
From here a new Event will have its properties set, and we can define who the invitees are. (Note: The type will determine who is prioritized on the invite list and who gets auto-added)

## Event Detail View

**Mockup:** 

![alt text](<MSX Events Interface Event Detail View.jpg>)

The detail view of an event will show the properties, allow you to edit the Invitation, monitor the status of RSVPs for the event as well as manage sending and checking if invitatations have been sent out and managing sending out invitations.

There should be checkboxes on the Invitee list that allow for bulk actions on extisting invitees, and there should be an invitee

## Add Invitees

**Mockup:**

![](<Add Invitees (Add to Event).jpg>)

There should be an interface that allows you to add invitees to the invite list on an event. We should maintain a database with different types of invitees. These should feed from the various sources currently existing in MSX (whether that be the Vendor List, the Customer List, or the List of Employees).

Not sure if we should have a means of adding a new invitee directly to the Invitee DB from this section.

