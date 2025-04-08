# CATMO

## App

I have been assigned to a project named **CATMO**, which includes a mobile app and an admin web app. They have provided me with Knowledge Transfer (KT) for the project overview—not the code KT—but only about the modules, user flow, and admin flow of the project. Below, I provide the complete KT details from top to bottom in depth so that I can prepare for my Reverse KT.

## General

This US-based project focuses on **Situational Awareness, Mustering, and Emergency-related use cases**. The project integrates with **SARA** (an emergency alert system) to notify users of triggered alarms and emergencies. This is followed by users being required to safely muster at a nearby safe mustering location and check in via the mobile app to confirm their safety. This allows focus to be directed toward those in need who have not checked in, which can be lifesaving. 

It can be used in:
- Schools
- Universities
- Government organizations  
to ensure the safety of people and instill trust that they will be safe. 

It can also be used in:
- Hospitals
- Elderly living homes  
where, during an emergency, an alarm can be triggered to send notifications to doctors, nurses, or caretakers for immediate action. 

Alarms can be configured for any type of alert, such as:
- Earthquake
- Fire
- Medical attention
- General-purpose emergencies

## WEB ADMIN

### Account & Facility Management

**Endpoints:**  
- `/home/system/account`  
- `/home/system/facility`

This is a **Single Server Application**, which can be customized for different vendors based on their requirements and needs. Vendors can obtain a **Catie Mobile admin account** from the **Catie Mobile Super Admin**. The account is created by the Super Admin for the Catie Mobile admin of an organization. The Super Admin has access to **Dashboard** and **System** modules.

#### Dashboard Contains:
- Total Accounts

#### System Contains:
- **Account** – Add and Manage Accounts  
- **Facility** – Add and Manage Facilities  
- **Integrations**

#### Account Creation Requires the Following Fields:
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
 
### Facility Creation

The Facility creation requires the following fields:

- **Account Name** [Dropdown – Show list of created accounts]  
- **Facility Names**  
- **Address**  
- **City**  
- **Zip Code**  
- **Country**  
- **Time Zone** [Dropdown]  
- **Contact Number**  
- **Total Accounts**  
- **Web Logo** [File Pick]  
- **Mobile Logo** [File Pick]  
