# TeamSupport-Excel-Tickets
Userscript for TeamSupport website that creates new tickets based on an uploaded Excel spreadsheet


Excel spreadsheets should be formatted so that the following columns exist: title, priority, estimatedDays and id. Any of the fields can be excluded but additional fields need to be coded in if desired.
- title: name of ticket
- priority: severity of the ticket (0,1=High  2=Medium  3=High)
- estimatedDays: estimated development days
- id: will be appended to name of ticket in brackets


Tickets will automatically be created as New Feature tickets.
