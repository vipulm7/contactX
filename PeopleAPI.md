# Usage of People API
ContactX uses PeopleScopes.Contacts scope.\
These scopes are used for 
1. reading the contacts saved in the user's google account
2. adding the contacts to the user's google account
3. deleting the contacts from the user's google account 

### No automation
The task of reading, adding and deleting is performed on the user's action.
ContactX doesn't use these scopes to automatically read, add or delete the contacts from google account.

### When Google contacts are read
ContactX reads contacts only when the user presses IMPORT FROM GBOOK or GBOOK SYNC buttons.
It doesn't read contacts every time the app is opened.
Import from gBook serves the functionality of importing the contacts from user's google account to ContactX's room database.


### What data ContactX read
ContactX reads the contact's name, number, email, birthday, address, website, work, note, SIP, nickname and relation.
This data is used to add that contact to the ContactX's database.



### When contacts are Added or Deleted
ContactX adds or deletes contacts only when user presses GBOOK SYNC or SAVE TO GBOOK buttons.
They are done in the foreground with the user's interaction.
User has to choose contacts to delete or add, as per his desire.

### Data security
Contacts are only imported to the room database.
They are never uploaded to my servers or any 3rd party servers. 
All the data is kept secure and safe in the user's local storage, providing top level security and no chances of data leakage.

### Enhanced User Functionality
The usage of People API provide the user the functionality to control his contacts, right from ContactX.
It provides the user the ease to handle his data, very easily and in an efficient manner.
