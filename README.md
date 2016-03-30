<h1>Active Directory Management Tool</h1>

<h1>Introduction</h1>
This tool allow users to manage individual accounts on Active Directory through a user-friendly GUI. It provides many attributes including email, title, description, office, department, phone numbers, home path, accout expiry, etc.

<h1>Running the Tool</h1>
Save the .exe to the C: drive of your Windows machine. The machine must have Powershell downloaded and connected to Active Directory. Double-click on the .exe to run the file. To set fields for a user, it requires elevated access. If elevated credentials are required, please run the .exe as a different user. 

<h1>How-To</h1>
Once the tool is up and running, the first search will allow the tool to load all its required modules. To search, please enter the user's name (first and/or last) or the user's SAM account name. Then click on "Search". To set properties, please search for the user first, then change the desired fields and click "Set Properties". This applies to enable, disable and reset password for accounts. To perform a new search, click on "New Search". See the tool's help menu for additional information.

<h1>Versions<h1>
Version 1.0: Template running, get all properties (ext attr 1-15, display name, etc)
 
Version 1.1: Addition of assistant field, added textbox of read-only, added help menu,
             password reset, and enable/disable users

Version 1.2: Addition of member of field

Version 1.3: Addition of Generate report by fields

Version 1.4: Addition of user location (address, postal code, city)

