# Welcome

> Your academic assistant.

This is an all-in-one college management app.

### Used tools:

* Code Editor: [Brackets](http://brackets.io) and [Intel XDK](https://software.intel.com/en-us/intel-xdk)
* Front-end Framework: [Materialize](http://materializecss.com)
* Cross-platform Framework: [Phonegap](http://phonegap.com/)
* Build: [Adobe Phonegap Build](https://build.phonegap.com/)
* Server: [NodeJS](https://nodejs.org/)

***

## Ideas

* Canteen booking
* Exam papers
* Chat room
* All features of [Student Diary](https://play.google.com/store/apps/details?id=com.iitms.sdraisoni)
* Notice board
  * Departmental
  * Events
* Class schedule
* Fees payment
* Salary (for staff)
* Send mail??

## Things to ponder

* Should all logic be in one script or they should be split according to function like, canteen.js, login.js? Likewise for css as well.
* Should mail sending facility be added or not?
* Should personal notes and organizer be added for student like a diary or organizer app?

***

# TODO List

### User interface

* [x] **Navigation bar and Panel** - _needs to be updated with links_
* [x] **Dashboard**
* [ ] Canteen page
  * [ ] Item order form
    * [ ] Quantity
	* [ ] Delivery location - if delivery will be given; otherwise not needed
  * [ ] Cart page
  * [ ] Checkout
* [x] **Paper download page**
* [ ] Student Diary pages
  * [x] **Personal details**
  * [x] **Attendance**
  * [x] **Marks**
  * [ ] Course registration
* [ ] Forum
  * [ ] Chat room selection
  * [ ] Chat page
  * [ ] Chat admin panel
* [ ] Class Admin panel
  * [ ] Notice board management
* [x] **Login interface**
  * [x] **Login for Student**
  * [x] ~~**Login for staff/admins**~~ _Login would select apropriate permissions based on username_
  * [x] **Password recovery** _Added as a popout menu in login page_
* [ ] Account management like password change
* [ ] Application admin panel
  * [ ] Users management
* [ ] Canteen Admin Panel
* [x] **404 page**
* [ ] Payments using [UPI](https://en.wikipedia.org/wiki/Unified_Payments_Interface) or [PayTM](http://paytm.com)
* [ ] **IEEE**
  * [ ] IEEE Student Branches
  * [ ] IEEE Sections
  * [ ] IEEE Councils
  * [ ] IEEE Regions
  * [ ] IEEE Groups (like WHatsapp groups)
  * [ ] IEEE Video Chat or Audio Chat (Like Web-X Meetings)
  * [ ] Individual Profile page for every user with Valid IEEE number
  * [ ] Permissions for Chair to Connect with Section SAC Chair and then Section SAC Chair forwarding the Query to Section Chair
  * [ ] Permissions for Chair and SB Counselor and Chapter Advisors (Officially listed on IEEE Rastors)
  

### Backend

* [x] **Create Server Repository**
* [x] **Create Web Server**
* [ ] Database for college info (Student Diary)
* [ ] College info server
* [ ] Chat server
* [ ] Shopping cart manager
* [ ] Papers directory management service

### Bugs

* [ ] The categories view on canteen page is not showing complete cards; only image is visible
