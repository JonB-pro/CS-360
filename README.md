# CS-360
## Mobile Architect &amp; Programming

### Requirements and user needs
The goal of this app was to create an application that served as an event tracker. Users needed to be able to login to an individual account, add a custom event, see it in a list with other events, and recieve a notification if the event date matches the current date. This required the app to have a user database and event database for storage, and several pages of the application that displayed dates, allowed creation, editing, and deletion of events, and an option to toggle if the application could send notifications.

### Screens and features
The screens needed for this app were a login page, a settings page, a main page, an event creation page, an event details page, and an event update page. The features needed included user creation and login, event list display, event details display, event creation, update, and deletion, and notification toggling. The designs used in my app were useful and kept users in mind by keeping buttons obvious in useage and size and by making the app flow logically.

### Coding process
The coding process I used was to create the UI first, attach code that allowed each page to function correctly, connect each page one at a time and test, and then replace data storageby attaching a database to the app. Creating the UI first helped me to know what needed to be addressed, and attaching the database last allowed for making sure the app functioned before worrying about storage. These techniques can be used in the future.

### Testing
I tested each page as they were connected, and then once the database was connected I ran through every process once again to make sure everything worked. Testing is important so that any errors can be caught and fixed before project release.

### Challenges
The main challenges I faced were making the app toggle permissions and getting the information already entered for a specific event to show up in the edit event screen upon opening. The permissions issue turned out to be a missing line in the app manifest. The details issue was solved after using getIntExtra instead of a serializable, and just re-accessing the event from storage through its id.

### Successes
I believe the login process was the easiest part to create, and went the smoothest. It still needs an aaddition of hash security, though. Also,the actual UI design, while simple, was mostly straightforward.
