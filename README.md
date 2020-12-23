# tidyCalendar
This is a calendar app. Users create an account before accessing the app.  If required, there can be more than one calendar under the same account. After logging in, users may plan their events on the calendar. Users can be notified of events with alerts. Events can be customized by adding memos and tags. If users require a certain event to occur regularly (ex. piano lessons), they may find it useful to set up a series of events. Users may invite other users to their event. 
Main.java is the start class. It is located in tidyCalendar/src/com/group_0225.

**Collaborators**
This project was completed with [Mark Sanchez](https://github.com/Mark-of-JP), [Daniel Shoichet](https://github.com/idanielsh), [Abhijoy Mandal](https://github.com/Abhijoy-Mandal), Omar Shalash. We submitted it as the final assessement for CSC207 (Software Design) at the University of Toronto.

**Notes**:

A timer refreshes every 30 seconds to check for new notifications. So any alert might be displayed at most 30 seconds after it is scheduled. If there are new notifications, you will automatically receive a message at most 30 seconds later.


**External Code**:

1. Using Java Swing package.

2. Using [Google GSON](https://github.com/google/gson). All code found within src/com/google.

3. Using [JDatePicker](https://github.com/JDatePicker/JDatePicker). All code found within src/org/jdatepicker.

4. Using [OpenWeatherApi](https://openweathermap.org).
