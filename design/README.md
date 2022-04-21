# Interaction Design


## Design Goals
When we initially set out to work on a design, it was in response to the data we gathered in Phase 1 of the project. We realized that the app would need to be centered around a timeline of sorts, and allow faculty an at-a-glance view of the inner workings of the tutoring department. We had initially planned to design separate interfaces for both students and faculty, but quickly realized a lot of the user objectives were the same, including verifying the hours of specific tutors, as well as being able to change account settings and perform searches. Because of this, we settled on a three-column design for our initial draft. Our focus was on learnability, minimalist layout and preventing users from feeling overwhelmed.

## Sidebar
The first-level sidebar located on the left of the screen was designed to convey the program’s current global mode in a high-visibility manner. No matter where you go, this bar serves as a reminder of where the user is in the application. Of these three modes are “locating a tutor through the schedule,” “locating a tutor through an alphabetical list,” and “changing my user account settings.” This sidebar is also a useful place for other expansions to the system in the future, although it has the possibility to grow out of control if heavy restrictions are not placed on what goes in it. 

Ideally, this menu would also translate to mobile by becoming a horizontal bar on the bottom of the screen, following the convention set by apps like Twitter, who also have different global modes of use. Basic information about the user is also conveyed in this sidebar, since the user’s status in the system governs what they are capable of doing in the rest of the application.

## Calendar
The center column of the “Schedule” mode is the calendar view, which follows a traditional calendar layout. This is the primary interface through which users or faculty locate an individual tutor, and serves as a sort of “macroscopic view” before a date is selected for finer focus. The user is given the typical tools to navigate this calendar, including the ability to move forward and backward by a month, as well as to switch the calendar into a “weekly” view, which only shows 7 days at a time. Each cell on the calendar has small circles that represent tutors who are serving for the day, and displays their avatar, as well as an icon to represent how many other tutors were not able to be shown on the cell.

The weekly mode of the calendar simply takes the grid cells of the calendar and stretches a row of them to be full-width, allowing the user to see the finer details of each day while still not navigating out of the “macroscopic view” of the calendar column. Users are able to see the general overview of which tutors are scheduled for which specific times.


## Search and Filters
If a user is looking for a specific subject or tutor, the search bar allows them to look them up. Once selected from the drop-down list, the selected user or subject becomes a “filter” that is applied to the calendar, and which can be dismissed by clicking on the small “x” button to the right of each applied filter. Popular filters are shown beneath the search bar as boxes with uppercase text, and are visually distinct from the applied filters, lacking an ability to dismiss them and imitating a button more clearly. If the “popular filters” list overflows, it scrolls horizontally with a user’s finger, or by clicking and dragging.

## Daily Schedule & Time-Cards

The right-most column is where the “finer details” are managed once a calendar date-cell is selected. When nothing is selected, some quick text prompts the user to make a selection. After making this selection, the grid-cell on the calendar is highlighted, and the right sidebar is populated with “time cards,” representing tutor sessions on a vertical timeline. 

A tutor’s time-slot is represented by a card. By default, the card starts in a minimized state, only showing the name and subject of the tutor’s session. By tapping the name of the tutor, the user can get more details, as well as perform both student and administrative actions, like contacting or scheduling with the tutor. Administrative options appear in the “hamburger menu” on each card, allowing faculty to delete the card, change details about the session, and view the user in the “Tutor List” mode of the program. 

Cards are stacked based on the starting-time of the session they are associated with. Either faculty or the tutor themselves can add a new card by clicking on the plus button at the top right of the sidebar, which then prompts the user to input a starting time, as well as other information about the tutor and the subject they are tutoring on. By scrolling with either a finger or the mouse-wheel, the user can move through the stacked list of cards, of which each are separated by the time they are scheduled to start in the form of a header.
	
Each time card also has a tabbed interface, which by default allows the user to either see biographical information about the tutor, or see more details about the selected session. Other options can be added to the tabbed interface in the future, but it should be kept to a maximum of 3 options.

## Tutor List
The tutor-list is a way for faculty to verify the number of hours that a specific tutor has been logged for in a given payment period. By default, this grid is sorted alphabetically, but modes of sorting can be changed by clicking on the category cells. This section resembles a spreadsheet that is automatically fed information by the “Schedule” mode of the program. Tutor information cannot be edited on this display, as it serves more as a reference.

The “Settings” mode of the program is handled by either horizontally or vertically stacked cards (depending on the screen or window size.) Each settings card is its own widget, with actionable buttons typically located at the bottom.


## Conclusion
Users wanted a uniform, simple system that would reduce redundancies and trust both students and faculty more to manage their affairs. The system was designed to be mostly “shallow” so that users would not get lost in deep menus and therefore find it cumbersome to use. We focused on the simple task of finding tutors as both faculty and student users, as well as getting metadata about them and the sessions they were associated with. Hopefully this calendar system proves useful with further user testing, and can at least supplant the existing solution that utilizes multiple services and personnel to do simple tasks.

[Faculty View Monthly View Card + Menu Opened](../artifacts/Web1366–FacultyViewMonthlyViewCard+MenuOpened.pdf)
