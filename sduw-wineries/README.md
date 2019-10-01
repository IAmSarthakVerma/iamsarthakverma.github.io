# Digital Passport(for Wineries)


# Executive Summary
This documentation is to serve as a 'Statement of Work' or SOW for implementing Digital Infrastructure for SDUW Wineries to enable and enhance the buisness. The advancement in the field of IoT Networks, Computing and Data Science has made possible Integrated systems that can really help business.
Such a system would include a means to capture, catalog and analyze data, along with tools to enforce 'business logic'.

Edvanta Technologies will work with SDUW to:

* Designing the Digital Passport(for Wineries) Operations Architecture
* Identify and integrate Digital Passport(for Wineries) infrastructure
* Develop and Engineer the systems
* Deploy said systems for SDUW
* Provide documentation of the new system
* Knowledge Transfer/Integrate 

Edvanta Technologies proposes to design, develop the proposed system.

The Value Proposition of using Edvanta Technologies for this project are:
* Proven engineering techniques for making Integrated systems.
* Data Architecture and Solution experience
* Using our subject matter experts to complete the project quickly. Rapid project completion minimizes disruptions and allows organizations to realize cost saving quickly.

# Delivery Scope

## Moile Application - User End

This application will be a cross platform(Android & IOS) mobile application that will eventually replace the printed passports in the user's hands with Digital Passports for wine tasting at partner wineries. This application will consist of the following modules(along with their respective functionalities):

### Login/Regestration/Reset Password

* Registration
This will allow the user to get an account registered to use an app

```
Data to Capture:  Email Address (Primary Key)
                  Password
                  Full Name(Oprional)
```

* Login
This will allow the user to login into any registered account. Once logged in, the app will maintain the session until logout or any other actions like reinstalling the app, clearing app data.
Everything that is linked to an account can be accessed just by logging into the account irrespective of the phone, location, etc.

* Password Reset
This will allow the user to reset any account's password by entering the registered email address. A password reset link will be sent to the registered email address to complete the process.

### Home
This is the screen where the user will be landed after loggin in or restarting the app while in a logged in state. This screen will be divided in FOUR PARTS:

```
A GREETING MESSAGE:
This will just contain a personalized greeting message.
```

```
A SEARCH BAR:
This will contain a search bar which can be used by the user to search for different wineries.
```

```
A LIST OF WINERIES (FILTERABLE):
This will contain a horizontal swipable list of wineries with Name, Location and an option to like/wishlist the winery. This list will be filterable and can be filtered by selecting the pills on the top of this list. On clicking any of the list item, the user will be navigated to the details page.
```

```
A LIST OF EVENTS: 
This will contain a horizontal swipable list of wine related events with Name, Date and an option to like/wishlist the event. On clicking any of the list item, the user will be navigated to the details page. 
```

![Home Screen](https://user-images.githubusercontent.com/20480867/65960139-69dc6680-e471-11e9-8c51-2aa0c8716eee.png)

### Winery/Event Detail Page

This page will consist of the following elements:

```
AN IMAGE GALLERY:
A gallery of the winery/event pictures.
```

```
WINERY/EVENT DETAILS:
* Name
* Description
* Contact Details
* Winery Open Hours
* A URL Button (?)
* A Navigation Button
* A Sticky Redeem Button
```

![Detail Page](https://user-images.githubusercontent.com/20480867/65960287-c93a7680-e471-11e9-9705-c4b6f90354e3.png)



### Map Page

* This page will consist of a fullpage interactive map that will have pins of the wineries/events.
* If any pin is clicked a chathead type popup appears over the pin to show details like name and address. Also, a button is present which can be used to go to the details page of that particular pin.

### Available Redemtions

* This will contain all the available tasings.

### Redeemed Tastings

* This will contain all the tastings redeemed from the past.

### My Passports

* This page will contain all the details about the passports bought from the account.
* This page will also contain a button to buy new passport.
* While buying the passport, the user will have option to buy the passport for "self" use or for a "friend". While buying the passport for a friend, the registered email address of the friend needs to be entered.

### Navigation Drawer

* This is a navigation drawer that will be common to all pages. This will contain the following navigation options:

    * Home
    * Winery Map
    * Available Tastings
    * Redeemed Tastings
    * My Passports
    * Settings
    * Help/Tutorial 
    
    
 ### MOBILE APP FLOW DIAGRAM
 
 ![Digital Passport(for Wineries) USER APP FLOW](https://user-images.githubusercontent.com/20480867/65958948-4b28a080-e46e-11e9-9a19-b1a2d3c36b04.png)
 
## Web Dashboard

This dashboard will be consists of the following modules(along with their respective functionalities):

### Winery Owner's End

This will be contain winery specific actions/operations. This will allow the winery owners to:

* Accept/Reject the tasting requests by the end-users.
* View Total/Accepted/Rejected tastings in a week/month/year/lifetime and also their respective earning/bill-cost.
* View the winery specific feedbacks given by the users after tasting.
* Generate and download CSV file for all of the above data or a filtered part of it.

### Admin's End

This will be contain system specific actions/operations. This will allow the admins to:

* View all users/wineries/passports/transactions along with their specific details.
* Add/Delete/Blacklist a winery.
* Add/Delete/Blacklist a user.
* Change the expiration of the any passport.
* Cancel/Revoke a passport.
* Generate and download CSV file for all of the above data or a filtered part of it.


## Maintenance
To be maintained for 6 months and then rediscuss based on new requirements and learnings.

## Exclusions
The followings are excluded from the project scope
*


## Customer Responsibilities
* The nature of this engagement dictates that Edvanta Technologies receive a frequent and enthusiastic response from the appropriate personnel.
* A weekly review between the Edvanta Technologies consultant and the Digital Passport(for Wineries) project lead or his designate will ensure that the expectations of this engagement are met.
* Client will assign a key contact who will be responsible for providing Edvanta Technologies with information, access to personnel, and facility access.
* Client will provide a work area space with desk, chair, Internet access for use by Edvanta Technologies to conduct project business while working on-site.

## Investment and Cost
* Man-hour required: 

* Payment Schedule:

Server cost to be paid directly or at the start of each month.
Travel reimbursements as and when declared.

## Acceptance Criteria
At the conclusion of this evaluation, all deliverables for this phase will be presented to SDUW for review.

SDUW or its representative will have five business days from the date of delivery of any document that is a deliverable to review it and request any changes.  If Edvanta Technologies does not receive notification of any required changes within this period, the document will be deemed to have been accepted without modification and will be reissued as a final copy.

If Edvanta Technologies is notified by SDUW, within the above time frame, of any changes required, Edvanta Technologies will within two business days of such notification implement those changes as have been agreed between the parties.  A final copy of the document will then be submitted to SDUW.

## Assumptions
* General
    * All documentation created for this project will be available in hard copy and electronic format.
    * Any modifications to the scope of work will be handled through a change control process and will be agreed to by both parties.

* Commercial
    * Additional costs may be incurred where any delay not under the control of Edvanta Technologies that causes Edvanta Technologies personnel to not fulfill their scheduled tasks.
    * An authorized delegate of SDUW will be available at the time of completion of the build phase so that all documentation can be accepted and signed.
    * Additional costs may be incurred where any work scheduled to be undertaken by Edvanta Technologies is postponed by SDUW after 24 hours of its commencement.
    * All changes to the schedule or technical requirements must be provided to Edvanta Technologies in written format. Email is included as written format. Receipt of all correspondence should be confirmed by phone wherever possible.
    * SDUW has accepted the costs/times estimate as detailed in this document
    * SDUW has accepted the Edvanta Technologies standard terms and conditions linked.

## Intellectual Property
Unless otherwise agreed in writing, SDUW acknowledges that all intellectual property rights attaching to the products or arising out of the provision of services are and will remain the property of Edvanta Technologies (or its suppliers, where such rights are owned by that supplier).

The software will be licensed to SDUW on the terms of the relevant license agreement provided with the product or as otherwise agreed between Edvanta Technologies and SDUW in writing.


## Approved by
Name:   
Date:   
Position:
