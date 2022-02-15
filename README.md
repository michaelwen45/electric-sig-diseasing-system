# Student Housing Electronic Leasing
**Online lease pdf signing solutions, inventory management, analytics, and more!**

This is the core of the internal company web application system consisting of many different modules automating company processes for the business different stages of business and customer lifecycles. 

These are projects for which I led in the development, software architecture, and product management during my time at REM. You can see Database Schema I designed/architected with <b>120 models</b> can be seen here under <b>app/models</b> which gives insight into the depth and complexity of this project. This software has been decommissioned in favor of real estate software solutions by Yardi.

This code was written between 2014-2017 and demonstrates technical experience experience in many different areas including backend and api development, querying and designing DBs, frontend user interface development, product management and more. Laravel is used as the framework for this project for this project.   <b>Laravel/Querying/DBs/etc</b> while giving a sneak peek of the <b>depth and complexity of work</b> I architected at REM.

I started the software development department at REM and built everything from the ground up after getting offered a full time position as the first software developer at the company. I was able to build this software and grow the department with no development mentorship. Only motivation, determination, hard work, and a lot of self education.

My actual development skills, organizational skills, and knowledge have greatly improved since this code. For a more accurate code quality representation, see my more recent React/Angular/Node repos and other newer projects.


# Internal Web App System Description
One large connected system with many different modules. This system automates processes for multiple departments throughout the company, and keeps track of where customers are at in the company pipeline. This is an n tier stack with middleware, server api’s, shared and combined data. All data is saved in the same databases, and information is shared between projects.

# Modules & Software Features

### E-Leasing
* Customers are emailed a link to create an account, and sign their documents online. Leasing agents create the Customer's leasing documents through an interactive form interface with customizations and options that affect the signing process, required documents, document text, and document layout. 
* **Inventory and Occupancy Management and Pricing controls** 
* View building occupancy information by location, building, unit, and time period. When viewing the inventory agents have a high level overview of resident information, and document statuses organized by location. 
* **Inventory Actions** include: moving customers, terminating leases, updating lease information and sending of revisions are available. 
* **Occupancy logic** The system automatically prevents overlapping occupancy by tracking existing leases time frames and locations. 
* **Customers Portal** where they can log in and sign and view documents, see recaps of their residency information, and have options for getting in contact. 
* **Agent Signing Portal** Leasing agents are able to view and sign these leases, and related documents, when they are done being signed by the customer.
* **Customer Profiles** containing all customer related information including, but not limited to, document envelope information, identity information, rent, unit location, event history, and document related actions.
* Ability to mass email customers by building, brand, and location/city.

**Types of Documents**
Pdf documents dynamically created and formatted based on by property/brand, and leasing agent input and options selected at the time of document creation. The effects each document has on a customer, or inventory are automatically handled.
* Lease
* Furniture addendum
* Utility addendum
* Parking addendum
* Internet agreement
* Parent Guarantee
* ACH Form
* Renewal form
* Termination form
* Unit transfer form

### Inventory Pricing Management

### Customer account management

### Inquiries/lead tracking & Appointments
* Keeps track of all leads. Defines and enforces a process for contacting, and following up with customers. Based on the position in the process customers are assigned a status.
* Tracking and management of appointments throughout their life cycle. Keeps track of status, and sets reminders.

### Note taking and labeling
Filterable calendar of all appointments

### Real-Time Reporting & Analytics
* Reports filterable based on time, location/city, building, brand, or individual
* Occupancy Reports
* Monetary reports
* Employee performance reports
* Lead and appointment reports
* Conversion reports tracking how many leads turn into appointments for showings, and how many appointments turn into leases.
* Year over year reports

### Parking App
* **Customer portal** for viewing available parking locations, pricing, and signing the addendum.
* Queue based ticketing system ( like ticketmaster ) allowing customers to sign up for limited parking spots. Customers receive a code that expires after 48 hours. Codes were gradually sent out based on a priority system and the number of remaining spots.
* Electronic Parking Addendum PDF generation, signing, and storage.
* 15 minute spot reservation period
* 
### Admin Dashboard
* Allows for the management of roles, accounts, and permissions.
