# CATMO

## App

I have been assigned to a project named **CATMO**, which includes a mobile app and an admin web app. They have provided me with Knowledge Transfer (KT) for the project overview—not the code KT—but only about the modules, user flow, and admin flow of the project. Below, I provide the complete KT details from top to bottom in depth so that I can prepare for my Reverse KT.

# General

This US Project focuses on Situational Awareness, Mustering, and Emergency-related use cases. The project integrates with SARA (emergency alert system) to notify users of the triggered alarm and the emergency, which follows up with users requiring them to safely muster to a nearby Mustering safe location and check in via mobile app to confirm their safety. This allows focus to be put on those in need and not checked in, which can be lifesaving. It can be used in schools, universities, and government organizations to ensure the safety of people and give them trust that they will be safe. It can also be used in hospitals and elderly living homes, where during an emergency, one can trigger an alarm to send notifications to doctors, nurses, or caretakers for immediate action. Alarms can be configured for any type of alert for any emergency, such as Earthquake, Fire, Medical Attention, or general purpose.

---

# WEB ADMIN

## Account & Facility Management

- `/home/system/account`
- `/home/system/facility`

This is a Single Server Application that can be customized for different vendors based on their requirements and needs. Vendors can get a Catie Mobile admin account from the Catie Mobile Super Admin. The account is created by the Super Admin for the Catie Mobile admin for an organization. The Super Admin has Dashboard and System modules.

### Dashboard contains:
- Total Accounts

### System contains:
- **Account**: Add and Manage Accounts
- **Facility**: Add and Manage Facility
- **Integrations**

#### The account creation requires the following fields:
- Account Name
- Address
- City
- Zip Code
- Country
- Contact Number
- **Primary User Details**:
  - First Name
  - Last Name
  - Email
  - Contact Number

#### Add Account Page

#### The Facility creation requires the following fields:
- Account Name [Dropdown – Show list of created accounts]
- Facility Names
- Address
- City
- Zip Code
- Country
- Time Zone [Dropdown]
- Contact Number
- Total Accounts
- Web Logo [File Pick]
- Mobile Logo [File Pick]

#### Add Facility Page

Multiple facilities can be created under a Mobile Admin account for handling multiple branches of a vendor. The primary admin can manage everything in all the facilities listed under the account. When logged in as a CATIE Mobile Admin, they can switch facilities using the Gear icon near the current facility name.

---

## Sign In & Sign Out

- `/user/login`

Account Email is essential for Mobile Admin creation, which sends a login link to reset the password via email. This link can then be used to log in to the account. The Email ID provided during the account creation process is used for Sign In purposes. Sign Out can be performed from the profile options in the top right corner of the Web Admin page.

### CATIE Mobile Admin Login Page

---

## Web Page

The CATIE Mobile Admin page has all the modules and features. After login, the user is directed to the main home page, which displays the current user logged in and the current facility in the top left corner, a profile tab with actions to view the profile and logout in the top right corner, and a sidebar containing:

- **Search Bar**: Search feature
- **Dashboard**: Shortcut to basic actions
- **Users & Groups**: Manage Users, Groups, Roles, Devices & Classes
- **System**: Server config & Facility Details
- **Application**: Alarms, Mustering, Events, Docs & Images
- **Reports**: History
- **Support**: Device Logs

---

## Dashboard

- `/home/dashboard`

### Permissions:
- **View Dashboard**: Show the dashboard section

This page displays three quick-access buttons to:
1. Add User (Users)
2. Add Group (Groups)
3. Manage System (Server Config)

The three quick-access options are displayed based on the user permissions provided:
- **Add User Option**: If Add User Permission is granted
- **Add Group Option**: If Add Group Permission is granted
- **Manage System Option**: If View Server Configuration permission is granted

### Dashboard
