## Project Exhibition 2

### Features:

 __Ability to input F.I.R data.__
 - Date: DATETIME
 - Time: TIMESTAMP
 - Incident details: VARCHAR
 - Description of Persons Involved: VARCHAR
 - Type of Incident: VARCHAR ENUM(Murder,Robbery, Theft, Rape, Harrasment, other)
 - Incident Zip: INT
 - Reported By: VARCHAR
 - Created At: DATETIME
 - Police Station Id: INT

__Ability to add a Police Station:__
 - Police Station Id: INT
 - Name: VARCHAR
 - Address Street: VARCHAR
 - City: VARCHAR
 - State: VARCHAR
 - Zip: INT
 - Lat: FLOAT
 - Long: FLOAT

__Ability to analyse the data by Police:__
- Map View, Chart View
- Type of incidence
- Incident Zip
- Police Station Name
…….

__Ability to control access based on a RBAC system:__

- Admin: This user role will be able to enter and modify the data : All the changes will be recorded and stored with encryption which even the admin won’t be able to change
- Police: This role will be able to view the data which is required by all or a subset of police officers ; We can also implement further access controls based on internal authorization levels of police officers
- Public : This role is assumed by the general public and they can view only the publicly disclosable information.

__Alert system for public awareness:__
- The summary will be sent by a text message to users who provide their contact number on the portal which will act as an alert system.
- The text message will contain only the highlights of the crimes in their area, the full summary and visualization will be visible on the site
- The police can include precautionary suggestions for the public based on their judgment from the data summary.


#### USE CASE:

- Resource Allocation:
 - Weapon resource
 - Human resource
 - Monetary resource
 - Recommendation for other government bodies.
> MG Road Delhi sees an average of 50 rape cases during December, it’s October and MCD is budgeting out different services they have to implement, looking at this data, Delhi Police advises MCD to increase number of street lights and CCTV Cameras in their next set of expense, also Police Patrol Vehicles was increased from 2 to 5 for the month of December and January.

A platform for police to spread awareness and precautions to the public 
