# CATMO

App

I have been assigned to a Project Named CATMO, which has mobile app and admin web app. They have provided me KT for the Project Overview not the Code KT only about the modules and user and admin flow of the project. Here I provide you the complete KT details from top to bottom in depth so that I can prepare for my Reverse KT.

General

This US Project focuses on Situational Awareness, Mustering, and Emergency related use cases. The project integrates with SARA (emergency alert system) to notify users of the triggered alarm and the emergency which follows up with users requiring to safely muster to nearby Mustering safe location, and check in via mobile app to confirm their safety so focus can be put on those in need and not checked in which can be lifesaving. It can be used in schools, universities, government organisation for ensuring safety of people and give them a trust that they will be safe. It can also be used in hospital and elderly living homes, in which during emergency one can trigger an alarm too send notification to notify doctors/nurses/caretakers for immediate action. Alarms can be configured for any type of alerts for any emergency like Earthquake, Fire, Medical attention, or general purpose.

WEB ADMIN

Account & Facility Management

/home/system/account & /home/system/facility

This is a Single Server Application, which can be customised for different Vendors based on their requirements and needs. Vendors can get an Catie Mobile admin account from the Catie Mobile Super Admin. Account is created by the super admin for the Catie Mobile admin for an organisation. The Super admin has Dashboard and System modules.

Dashboard contains - Total Accounts

System contains

Account – Add and Manage Accounts

Facility – Add and Manage Facility

Integrations

The account creation requires the following fields

Account Name

Address

City

Zip Code

Country

Contact Number

Primary User Details - First Name, Last Name, Email & Contact Number

Add Account Page

The Facility creation requires the following fields

Account Name \[Dropdown – Show list of created accounts\]

Facility Names

Address

City

Zip Code

Country

Time Zone \[Dropdown\]

Contact Number

Total Accounts

Web Logo \[File Pick\]

Mobile Logo \[File Pick\]

Add Facility Page

Multiple facilities can be created under a Mobile admin account for handling multiple branches of a vendor. That primary admin can manage everything in all the facilities listed under the account. When logged in as CATIE Mobile admin he/she can switch the facilities using the Gear icon near the current facility name.

Sign In & Sign Out

/user/login

Account Email is essential for mobile admin creation which sends a login link to reset password as mail which can then be used to login to the account. The Email id given during account creation process is used for Sign In purposes. Sign Out can be performed from profile options in top right corner in the web admin page.

CATIE Mobile Admin Login Page

Web Page

The CATIE Mobile admin page has all the modules and features. After login user is directed to main home page which display current user logged in and current facility in top left corner, profile tab and action to view profile and logout in top right corner and a side bar containing

Search Bar – Search feature

Dashboard – shortcut to basic actions

Users & groups – Manage Users, Groups, Roles, Devices & Classes

System – Server config & Facility Details

Application – Alarms, Mustering, Events, Docs & images

Reports – History

Support – Device Logs

Dashboard

/home/dashboard

Permissions:

View Dashboard- Show the dashboard section

This Page displays three quick access buttons to add user (users), add group (groups) and manage system (server config). The three quick access options are displayed based on the user permissions provided

Add User Option – if Add User Permission is granted

Add Group Option – if Add Group Permission is granted

Manage System Option – if View Server Configuration permission is granted

Dashboard

Roles & Permissions (Web)

/home/roles

Permissions:

View Roles- Show the roles section to display list of roles

Add Roles – Create a new role with permission for web and mobile

Edit Roles - Manage Column Edit Option to edit role

Delete Roles - Manage Column Delete Option to Delete a role

Role Table Columns: Role Name, Manage.

Roles define the permission for the users created, Role is a mandatory field in User creation. There are different set of permissions for web application and mobile application. Role creation requires Role Name, CATIE web permission, CATIE mobile permissions and a check box whether to show the users associated with the roles in advisor's dropdown in user creation.

Roles page

Roles can be edited for permissions and name but deleted only when no users are associated with the role. Changes are saved when “Save role and Permissions” button is clicked. View permission had dependency with other permissions. Including add/edit/delete/ anything which has view will need its View permission. Removing will throw error saying dependent permission are included cannot remove the permission.

Role Creation & Permissions

Web User Permissions

PermissionFeatureSub-FeatureUI

View DashboardDashboard-Dashboard Side bar menu

View profileProfile-View profile option (Actions)

Update profile-Save Button (Profile page)

View UsersUsers & GroupsUsersUsers section

Add UsersUser Mgmt. options (Create & Batch)

Edit UsersManage Column

Delete Users

View GroupsGroupsGroups section

Add GroupsGroup Mgmt. options (Create & Batch)

Edit GroupsManage Column

Delete Groups

View RolesRolesRoles section

Add RolesRoles Mgmt. Options (Create & Batch)

Edit RolesManage Column

Delete Roles

View DevicesDevicesDevices section

Add DevicesDevice Mgmt. Options (Add & Batch)

Edit DevicesManage Column

Delete Devices

View ClassesClassesClasses section

View Server configSystemServer ConfigurationServer Configuration section

Update Seve configSave Button (Server config page)

View PropertiesProperty DetailsProperty Details section

Update PropertiesSave Button (Property page)

View MusteringApplicationMusteringMustering Section

Manage MusteringManage Column (Muster)

View Mustering LocMustering LocationMuster Location Section

Add Mustering LocAdd Mustering Loc button

Edit Mustering LocManage Column

Delete Mustering Loc

View AlarmsCreate & ViewAlarmsCreate & View Alarms section

Add AlarmsCreate New Alarm button

Edit AlarmsManage Column

Delete Alarms

View Docs & ImagesDocuments & ImagesDocuments & Images Section

Add Docs & ImagesAdd Category, New file & Reorder

Edit Docs & ImagesManage Column(EDIT – Category & File)

Delete Docs & Images

View EventsEventsEvents Section

Add EventsAdd Event button

Edit EventsManage Column

Delete Events

View Deployment configConfigurations-Deploy SetupDeployment Setup Section

Edit Deployment configSave Button

View Alert configConfigurations-Alert SetupAlert Setup Section

Edit Alert configSave Button

View Mustering HistoryReportsMustering Event HistoryReports hence Mustering Event history section & View History in Mustering

Device LogsSupportDevice LogsSupport hence Device Log Section

Users

/home/users & /home/users/add-user

Permissions:

View User - Show the users section to display Users table

Add User - Add Single User & Batch Import button to add new users

Edit User - Manage Column Edit Option to edit User details

Delete User - Manage Column Delete Option to Delete a User

User Table Columns: Profile, User ID, First Name, Last Name, Role, Email & Phone, Manage.

Users are created and managed in this section. Users can be added one by one or with batch import option by including necessary information for user account such as: (Red indicates required fields)

First Name

Last Name

Profile Photo

Email

Phone Number

Location

Roles (view/edit)

Groups

Advisor

Email/User ID

Password

Reset password on first login (checkbox)

Users Page

Batch Import:

Download the excel or csv file format and format the user data with required fields and upload the excel or csv file to import many users as a batch.

Users can be filtered using assigned roles and groups or sorted by Name and role or searched. User details show the user count currently displayed in the table. Multiple Roles can be assigned, and user can be in multiple groups. Advisor can be assigned to a user so during mustering by advisor their advisees are listed separately as “My Class”.

Add User Page

Users Batch Import Dialog

Groups

/home/groups

Permissions:

View Group - Show the groups section to display Groups table

Add Group - Add Single Group & Batch Import button to add new groups

Edit Group - Manage Column Edit Option to edit Group details

Delete Group - Manage Column Delete Option to Delete a Group

Group table columns: Group Name, Total count, Created By, Created On, Manage.

Groups are created and its users are managed here. New group can be created here or multiple groups with batch import by providing required fields such as:

Group Name

Users

Devices

Batch Import:

Download the excel or csv file format and format the group data with required fields and upload the excel or csv file to import many groups as a batch.

Groups can be selected to view users of the group or searched. A group can have multiple users and devices. While creating group users and devices can be assigned with a group (more on devices later). Also, Groups can be edited or deleted.

Groups also has attendees registered for an event as group which is auto generated with the name format “{Event Name} Attendees”. It cannot be edited or deleted, only when an event is deleted the autogenerated group also gets deleted. The Created By column will be mentioned as “Event”.

Groups Page

Add Groups Dialog

Groups Batch Import Dialog

Profile

/home/profile

Permissions:

View Profile - Show the profile option on clicking profile icon

Update Profile - Show the Save button to update details

This Profile page shows details of the created user and gives option to edit and save details. It shows the following information:

First Name

Last name

Profile photo

Email

Mobile Number

Location

Email/ User ID

Roles

Advisor

One can only edit the FirstName, Last Name, Photo, Email, Mobile Number, Location of the user in which First and Last name are required and cannot be left empty.

Profile Page

Alarms

/application/create-view-alerts

Permissions:

View Alarms- Show the Create & View Alarms section to display list of Alarms

Add Alarms - Create a new alarm button to add a new alarm

Edit Alarms - Manage Column Edit Option to edit Alarm

Delete Alarms - Manage Column Delete Option to Delete an Alarm

Alarm Table Columns: Alarm Name, Button, Manage.

This Alarm page is where alarm buttons are created and managed. Different buttons can be created for different situations, such as Fire Alert, Intruder Alert, or personal like emergency alert, medical attention alert depending upon situation. To Create the alarm following fields are to be filled:

Alarm Event Name

Button Colour \[Dropdown\]

Icon \[Dropdown\]

Groups, Users & Devices – Selection

Enable Description \[Checkbox\]

Associated Users/Users in Groups/Device will display the associated alarm in the Alarms tab to Trigger them given the permission in cases of user login, if a device is associated with an Alarm, it shows regardless of the user login. Multiple Groups/Users/Devices can be assigned to the Alarm, and it shows up in all of them.

You can also add new Icon by uploading a SVG or PNG file which can then be assigned to the alarm you create. Alarms can be created with random colours which doesn't signify any meaning.

Alarm Page

Create Alarm Page

Add Icon Dialog

Mustering

/home/application/mustering

Permissions:

View Mustering - Show the Mustering section to view Mustering alerts

Manage Mustering - Manage Mustering by Check in, absent status

This Page displays currently active Mustering Alerts (Note: Non – Muster alerts doesn’t show up here). When no Muster alerts are active it shows a card saying, “No Current Events” and with the link to Mustering Event History page – which lists past mustering event

Mustering Page (No Active Mustering Alerts)

Mustering Page (Active Mustering Alert)

When Alert(s) is active it displays all active alerts and “View Mustering Status” button to Mustering page where a particular user can be set to check in to a location/ add a new location to check in or get marked as absent and add notes. In the Mustering page it shows various details – Alarm Name, Date, Triggered By, Current Result – Checked In, Unassigned, Absent (Count), Filter By – Role, Group, Status, Location and shows a table to display the users. This Table shows the Checked In status, medical requirement status (set in Mobile app), Absent status, Full name, Profile Picture, Role, Advisor (if any), Location check in, Last Updated status Date Time, Notes, Manage Column to open status dialog to edit status. On refresh it fetches the latest status of users which are maybe being updated by other web admins or users who are in mustering. Will learn about non-mustering in detail in mobile side. So far when a Mustering or Non-mustering alert is triggered, we have configured who can trigger them, but the configuration of whom to notify is setup in SARA when a button is associated with group, so when a particular alert is triggered the users of the associated groups are notified and sent alerts using SARA.

Mustering Page

Update Status Dialog

Mustering Location

/home/application/muster-location

Permissions:

View Mustering location - Show the Muster Location section to display list of Muster locations

Add Mustering location - Add Mustering Location button to add a new location in the facility

Edit Mustering location - Manage Column Edit Option to edit Muster location details

Delete Mustering location - Manage Column Delete Option to Delete Muster Location

Mustering Location Table Columns: Location Name, Associated groups, Manage.

This Page manages the muster locations within the facility, Location added here are listed duding mustering for users to check in, so to get a sense in which safe location the users have checked in. For add a new Muster location - Location Name and associated Groups are needed to be provided. The Location shows up in the muster location list for the users in associated group when mustering. A location can be fixed for group of users to check in during emergency.

The Table shows List of all Muster Locations in the facility along with associated groups and manage options to edit the name and groups or delete the location entirely. Total entries show the number of locations added.

Mustering Location Page

Add Muster Location Dialog

Classes

/home/classes

Permissions:

View Classes- Show the Classes section to display classes in the facility

Class Table Columns: Class Name, School, Teacher Name, Student Count, View (Student Details).

This page shows classes which can be used when vendor is a school, so that classes can be maintained with school name, teacher for the class, student, count. These details are directly from the UMS (user management system), it's here just for display. Additional configurations can be done with these classes using SARA to assign location, alert and manage attendance based on UMS. These is used only in case of school vendor for others this permission can be revoked and provided.

Classes Page

Devices & Deployment Setup

/home/devices

Permissions:

View Devices - Show the devices section to display list of devices

Add Devices - Add Single device & Batch import devices

Edit Devices - Manage Column Edit Option to edit Device details

Delete Devices - Manage Column Delete Option to Delete a Device

Devices Table Columns: Alarm Name, Button, Manage.

Devices Page displays devices that can be configured for the facility, a particular admin device with certain alarms can be assigned and any user regardless of device can trigger that alarm. Will look more about in mobile setup but generally the deployment config has a user id and password which when used to login in mobile redirect to device registration page where user can provide the created device id to register the device and then login.

Devices Page

The Device Page list all devices of the facility. To add a single new device following details are needed:

Device ID

Device Name

Cell Phone Number

Assigned Alarm buttons

Assigned Groups

There is a triangular relation between Alarms-Groups-Devices, so for device assigned alarms and alarms assigned with groups show up regardless of what user is signed in.

Add Device Dialog

Batch Import:

Download the excel or csv file format and format the Device data with required fields and upload the excel or csv file to import many Devices as a batch.

Devices Batch Import Dialog

After a Device is registered it can communicate with the server to provide many details about it. The server gets details about Device ID, Name, Type, OS version, Battery Level. Current User, Current User login time, Last logged in username, Login time, logout time, logout type. Device Ip address, Client App version, Device status, Device last request date time, Device date time.Fetch details can fetch latest details about the device to server and request logs gets the device logs.

Device Communication Status – Foreground, Background, Logged Out

MQTT Communication Status – Connected, Disconnected

SARA Registration Status – Registered

Logout Type – Manual, detached (There is an option to force detach the current device)

Device Details

/home/application/configurations/deployment-setup

View Deployment Configuration- Show the Deployment Config to display Deployment setup

Edit Deployment Configuration - Save button to edit and save configuration details

The Deployment setup Page contains the configuration details for device registration, it has the username and password required to proceed to device registration page in mobile. It also has other features for mobile inactivity logout and logout while charging.

Deployment Setup Page

Device Logs

/home/support/device-logs

Permissions: Device Logs- Show the Support Section device logs section

Device Logs Table Columns: User/Device Name, Last Received, pending (Status), Manage.

This Device log page can be used to obtain logs from registered devices for debugging purposes. It displays the devices; date time of last log received and Manage option to force fetch logs from the device. It can be sent from mobile by double tapping version number in Menu to send out logs to server. Logs can be downloaded and viewed for knowing about the device activity.

Device Logs Page

Events

/home/application/events

Permissions:

View Events- Show the Events section to display list of events

Add Events - Add new event button to create a new event

Edit Events - Manage Column Edit Option to update/edit event details

Delete Events - Manage Column Delete Option to Delete an event

Event Table Columns: Event Name, Event location, Attendees registered, Link, QR Code, start date & Time, End Date & Time, Manage.

Events is the latest module which can be used in many scenarios. Events can be anything like a small party, school sports day, concert, or any activity where many people are involved and where emergency can happen and hence need to be handled. A new event can be created with the following details:

Event Name

Event Location

Start Date & Time

End Date & Time

Event Description

Image Gallery

Documents

Registration setting

Open Registration

Closed Registration

Events Page

The event name, location, description can provide details about the event and images and documents can be uploaded to share information to event participants. For example, for a concert event, schedule, location map, songs list, and other details that need to shared can be included along with the event creation.

Add Picture Dialog Add Document Dialog

Create Event Dialog (Closed Registration)

There are two types of events, generally all created events show up to all users under the facility so event like maybe general meetings, get-togethers need not require any registration, they can be used to just indicate a certain event is happening within this certain time, this is for existing facility so the alerts can be managed using that.

Now suppose a concert is happening with outsiders as participants now they require registration in to send them alerts and quick messages, for that open registration options give a link / QR code to register an outsider for the event, Scanning the QR or link direct user to download the mobile app if not and the registers the user to the specific event or directly register the user for the event. All users who register using QR/link are made into an automatically created group {Event Name} - Attendees which can be configured in SARA and the admin for alerts or quick messages.

Create Event (Open registration)

History

/home/reports/event-history

Permissions:

View Mustering History- Show the Mustering Event History section to display past list of events.

Event Table Columns: Date, Event name, Check Ins, Absent, Emergency, View.

Mustering History Page

This page as already mentioned in Mustering display history of all past Mustering events with

Date Time

Muster Event Name

Mustering Details

Check Ins

Absent

Emergency

View – to view details

It has option to filter by date and search a particular muster event. In view details show detailed view of each user status and a Download Report button to download all details as Excel or Csv file. It shows the triggered by and cleared by details and overall muster details.

Event History Details Page

Docs & Images

/home/application/documents-images

Permissions:

View Docs & Images - Show the Docs & Images section to display Docs & Images uploaded for facility

Add Docs & Images – Add New Category/File to the Docs & Images

Edit Docs & Images - Manage Column Edit Option to edit categories/files

Delete Docs & Images - Manage Column Delete Option to Delete category/file

Docs & Images Table Columns: Menu category, Last Updated, Created By, Manage.

This page contains Documents & Images related to the facility that can be used in time of emergency, such as floor map, exits, entrances, or any other files that will be in need during mustering situations or general file which can be shared by the admin to the users.

It can be uploaded as files or files under categories, it supports up to 5 subcategories and each category can have files under them. This can ensure organized storage of documents in need so easy to find. There is a reorder option to reorder the listings of documents & Images also. This page lists all these with Menu Category, last updated Date Time, created by and Manage option. Some files are Imported from UMS which are marked as DATA IMPORT under Created by column. Those imported files can only be edited for group restriction and cannot be deleted by user.

For adding a new category or file it requires a Category name/ File Name and information on groups restrictions. This restriction makes the corresponding file and category only visible to the users of the groups associated. This can be edited anytime using manage.

Add Category: Category Name & Groups

Add Document/Image: Parent Category, Name, File (choose file), Groups

Docs & Image Page

Add Category Dialog Add File Dialog

Catergories and Files

Alert Setup

/home/application/configurations/alert-setup

View Alert Configuration - Show the Configuration-Alert Setup section to Alert config

Edit Alert Configuration - Save Button to update and Save config details

Alert Config Table Columns: Tone, Preview & Tone Name, Manage.

Alert Setup Page

Alert Setup page contains general alert configs, while the main configs are in SARA. Here the tone rather Notification sound of alert type can be configured. General Alert, Critical Alert, and Quick Messages (more on this in mobile). Custom tones can be uploaded and assigned.

Add Tone Dialog

Server Config & Property Details

/home/system/server-configuration

Permissions:

View Server Configuration - Show the Server Configuration section to Display All Server Details

Update Server Configuration - Save Button to update and Save config details

Server Config Details: SARA, UMS, MQTT, AZURE.

Server Configuration page contains details about the server being used for the facility, it has details about SARA credentials, UMS server, MQTT for subscription and Azure for storing documents & images or any other media files.

Property Details page has the facility details that were filled by super admin while creating the facility. It provides a Save button to update the details such as

Property Name

Address

Street

Street 2

Apt/Suite

City

State/province

Zip Code

Country

Server Config Page

/home/system/configuration/property-details

Permissions:

View Property details - Show the Property Details section to display facility details

Edit Property details - Save Button to update and Save facility details

Property Details Page

MOBILE

Home Page

Installed CATMO App will land on this page upon opening. This defines the use case for the user. The app has two options as seen here: Sign In & Scan Code

Sign In: Vendor has provided the user with a log in username and password

Scan Code: User has turned up for an event to which he can subscribe by scanning QR Code

This page gives overall motive and displays service provider details and sign in & scan code options

Note: This page is not displayed when it has been registered under a facility as in that case it won't be used as only event device.

Home Page QR Code Scan Page

Sign In Page

Permissions:

Can Login - Permission to login with valid credentials, shows error on login when not provided.

This is the regular user sign in page in which given username (email) and password can be used to sign in to the user account. It has options to reset password using Forgot Password? And remember me to keep the credentials saved for easier login.

This also the page the deployment config username and password need to be provided to be directed to the device registration page in which the device can be registered. On clicking cancel button it takes to the home page, but after device registration the cancel button is removed due to before mentioned reasons.

Sign In Page

Server Change

In general, there is only production level but using the app during development and testing requires use of separate environments for efficient development and testing and then release the developed & tested feature to the production application. Therefore, on long pressing the App logo in Sign In page redirects to the Server config page where the desired Server can be chosen.

Production Server – Customers & Users

Sandbox Server – Development

QA Server – Testing

This configuration in set once and doesn’t change until explicitly changed again to different user. This Server is what links all servers (SARA, UMS, MQTT, Azure & any other service required) with the user.

Server Configuration

Permissions

These permissions are used to conditionally render the features available to user and even the UI – button, bottom tab & drawer menu item

PermissionFeatureUI

Can LoginLogin-

Can Edit ProfileProfileEdit Icon in Top right corner in Profile page

Can Trigger AlarmsAlarmsAlarm Tab & Drawer menu to display alarms

Can Clear AlarmsClear Button – Alarm Tab & Mustering Details

Can View Details of Active Alerts

Can Accept AlertsNon - MusteringAccept Alert in Non-Muster Alert

Can Accept Multiple Alerts

Can Check InMusteringSelf-Check in Option

Can Check Others InMustering tab in Alert Details

Can Mark Absent StatusAbsent option in Status dialog

Can View Details of Past AlertsHistoryHistory tab & Drawer menu

Can Download Report of Past AlertsDownload report button in history details

Can View EventsEventsEvents Tab & Drawer menu to display events

Can Register for EventsScan QR code drawer menu

Can View Docs & ImagesDocs & ImagesDrawer menu Item

User

A Mobile user will have a set of permission provided by the admin who created the user. The above permissions define what the mobile user can and can’t do with their account with the Mobile App.

No User is created when the user just uses the app for an event alone, there only Events page & Scan QR page is displayed, no other permissions are provided. To avail permissions provided by the admin the user has to login to their account.

App Overview

Upon Sign in the default page is Dashboard which is part of the Bottom navigation Bar which contains

Menu – Opens App Drawer

Home – Current events

Events – List of Events

History – List of Past activity

Alarms – List of Alarms Buttons to Trigger

App contains app bar with the leading icon of the vendor then title and then the profile pic of the user. There are three use case – Mustering Alert, Non-Mustering Alert and Quick Message, these three are displayed on dashboard.

Dashboard

The Dashboard is what the user lands on every app open where quick information about status can be seen. When no active alerts are there “All Clear” message can be seen, but when alert(s) is active it displays the active alert, its triggered date time and actions button requesting mustering for user response in case of Mustering alert and other actions during non-mustering and quick message(more on this later). The Home tab shows a little badge indicating current count of alarms active.

Home Dashboard

Menu & Profile

The Menu tab opens the app’s drawer which displays menu items deepening upon the permissions provided. It has three categories:

Alarms – Navigates to Alarm Tab

Docs & Images – Opens Docs & Images page

History - Navigates to History Tab

Event Details - Navigates to Events Tab

Scan QR code – Opens QR Code scan Page

Profile – Opens Profile Page

Logout – Opens Logout Dialog

Profile page displays the user account details and edit option to edit and save details.

Permissions:

Can Edit Profile - Permission to edit the profile details and save it to server

Menu -App Drawer User Profile Page

Alarms

Permissions:

Can Trigger Alarms - Permission to Trigger the associated Alarms (Alarms Screen)

Can Clear Alarms - Permission to clear an active alarm (Mustering Details Tab and Alarms Screen)

Alarms Screen Alarms Description

Alarms Page has list of all Alarm buttons assigned to the user via direct or groups and on clicking user is asked for an activation confirmation depending on Mustering or Non-Mustering Button and Description enabled. If the device is registered it also shows alarm buttons associated with the device in the alarms list.

Alarm Clear Button (Alarms Page)

Mustering

Mustering in one type of alert triggered by alarms. This requires mustering (the process of gathering and accounting for personnel at a designated location (a muster point) to ensure everyone is safe and accounted for during an evacuation or other emergency).

Mustering Details (before check-in) My Status (before check-in)

Permissions:

Can Check In - Check In option to ensure their safeness

On clicking requires mustering, Alert Details page opens with initially 2 tabs, details & My status. The details tab has info about the alert, triggered by, Date Time, Additional Description in any. Upon Tap to check in user must provide their status:

Medical emergency required?

Muster Location?

Notes if any?

This status will be updated for themself, and others can get to know about their safeness. Upon Check in if user has permission, they can change others status.

My Status - Check in Location, Medical Attention toggle & Notes

After Updating their status, the Details and My Status page gets updated. My status page shows the updated status and Details page shows the Clear Alarm button if clear alarms permission is given. Update Status button can edit the status of the user in case if needed. The Clear Alarm button open a confirmation dialog and upon confirmation alert is cleared. If the user has class or advisees assigned upon entering Mustering tab “My Class” is opened if not “All” tab is opened.

Mustering Details & My Status (after check-in)

Can Check Others In - Permission to Muster others and update their status

Can Mark Absent Status - Permission to set status of user as absent

Mustering Page has a Refresh option on the app bar in Top right corner which on clicked refreshed the page and fetch updates details and status of users. Mustering Tab contains two sub sections

All Tab – All users details

My Class – Class assigned to You & Direct Advisees

So, during mustering assigned user can muster their assignees first and prioritize them and ensure their safety. My Class has list of classes for which you are assigned as teacher and for users you are termed as advisor for.

There are three statuses for a user:

Not Checked In \[Default\] - Red empty circle

Absent – Green tick

Checked In (combined with medical attention) - Absent Icon

There is a check All option to set all users status to Checked In and update it, so this can be a quick action to update the status and then if u want to update again u can change status of a particular user again. Check all is available in All and Classes tab so u can quickly update the status of whole class.

Mustering All Tab

Mustering Class Tab

The Check Others in Status update has there params:

Needs Medical Attention?

Absent

Notes

For quick check in option just click the user to set their status as checked in (turns green with a tick mark). To open the dialog to give other status (absent/medical) click on the more three vertical dots adjacent to user. The global search in All and class tab can help to find a specific user.

Note: when a user check other in the muster location of the user is set to the check in location of user who checked them in. Also shows who checked them in.

Status: Checked In (own & others)

Status: Not Checked In & Absent

Check Others in Filters & Search

The Mustering page is well organized and easy to use where users are combined under an expanding list depending upon their status. It even has a Filter option to filter users by

Groups

Advisor

Roles

Class

Location

Status

And shows active filter option and clear filters option for quick look and management of users during mustering. Also has a filter search for each category to find a particular thing within the subject. Non-Mustering

Non-Mustering

Non – Mustering Alert (Dashboard & Details \[Not accepted\])

Permissions:

Can Accept Alerts - Permission to accept non mustering alerts

Can Accept Multiple Alerts - Permission to accept multiple non muster alerts

Non-mustering is different from Mustering alerts, the user flow itself varies. Non-Mustering alert when triggered must be accepted by someone which is updated as “accepted by user” which is visible to others who got the alert. Upon clicking it opens the Accept alert page which has details of triggered by, Date Time, and additional description if any.

Non – Mustering Alert (Accepted & Alarm Cleared)

It has “Accept Alert” button which makes the status to be “accepted”. Then there is option to cancel the acceptance which turns the status to not accepted again. Other button is Clear Alarm which change the status to “Cleared Alarm”. The Alarm is cleared but the alert is active. There is no going back to previous status from alarm cleared only way is forwarded to clear the alert. The user who accepted the alert can only clear the alert. Two types of users:

Upon all users who got alerted only one can accept, the rest others can view the alert, and it display the contact details of the user who accepted it, so that they can be communicated if they must provide any details. Stages:

Not accepted – Blue

Accepted – Yellow

Alarm Cleared – Green

Alert Cleared – Removed from Dashboard

Not Accepted

Accepted

Alarm Cleared

Users other that who accept the alert can communicate to the accepted user via call or message to give them additional guidelines. For this the accepted user must have provided their mobile number in the profile. The call icon hence will open the default dialler and message option opens the default messenger with the provided contact number. When no contact number is provided the communication options are not available. Consider the use case in hospital or old age TakeCare homes, a patient triggers a non-mustering alert then a caretaker/doctor accepts the alert. Other doctors/caretaker who wants to share any info about them can contact the user who accepted it.

Contact available & non available

Quick message

Quick Message is third main feature after mustering and non-mustering alerts. They are triggered directly from SARA and can be sent to any groups to share any urgent info. Details page shows the message and who sent it. The red dot indicator is for every type of alert shown in the dashboard. The red dot indicator is shown till the details pages of the alert/message is opened at least once. After that the red dot indicator is removed. Note: In case the user was in proper sign out state while a quick message is sent upon opening the quick message does not show in dashboard rather it is moved to history tab unlike Mustering & Non – Mustering alerts which would still show up in dashboard if they are active. Upon acknowledge the quick message goes to the history section.

Quick Messages in Dashboard & Details

Red Dot Indicator

Device Registration

This is the implementation of devices from web where the Deployment config details are used to access the device registration page, and a device gets registered using the Device ID. The configuration of the device done in web gets reflected in the Alarms tab.

After device registration there is no remember me and cancel button to go to the main landing page

Device Deployment Device Registration After Device Registration

Devices can be associated directly with alarms or indirectly by groups which is associated with an alarm. So, when a dummy user who has no access to any alarm button but has trigger alarms permission when logged in to a general device no alarms are shown it says, “No Alarms Configured”.

But after the device gets registered and that device has a direct alarm say “Arun-Alarm-Intruder-Test" and another alarm “E2\_Test\_mustering” through a group, both the alarms shown up regardless of the user logged in.

Before & After Device Registration

Events

Can View Events - Permission to view list of events

Can Register for Events - Permission to scan QR code & link to register for events

Events Tab shows list of all events in the facility by categorizing into Current and Previous Events. Upon clicking any event we can see event details page with all details, images & documents which were added by the web admin. The event gets automatically categorized when its time gets over and moves to previous events. Events page just shows the list of events, for open registration events to register to them we must scan the QR or link to register for the event.

Events Tab & Event Details

After registering in the same list an unregister button shows up which unregisters the user from the event. Registration is for the purpose of creating event group so that SARA can be used to send alerts based on that group.

Another use case is the user just using the app only for an event in which only shows the registered event and events tab.

Event Registered User

History

Permissions:

Can View Details of Past Alerts - Permission to view history tab

Can Download reports of Past Alerts - Permission to download reports of past events

This History page shows the user’s history of alerts that have been cleared and messages that have been received and acknowledged. It has a search option to search a specific event or sort by event date. Clicking the event shows the corresponding alert/message event details.

Quick Message details – Message content, Sent By, Sent On, Acknowledged at

Mustering – Event, Triggered by, Triggered at, Cleared by, Cleared at, Check in Details, Download

Non-Mustering details – Event, Triggered by, Triggered at, Cleared by, Cleared at

In logged Out – quick message directly come to history upon login, but active alerts stay in dashboard, but cleared ones are shown in history

History Page Sort by Date Search by Name

Quick Message Details Mustering Details Non-Mustering Details

Docs & images

Permissions:

Can View Docs & Images - Permission to view Docs and Images associated with facility

Documents & Images Page Just displays the Documents & Images uploaded by the admin to the Docs & Images module in Web. They are view only and cannot be edited or deleted. This viewing is also group based only shows up based on the restricted groups by the web admin
