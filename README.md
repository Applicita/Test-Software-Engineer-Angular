# RecruitmentAngularJSTest

**Task requirements:**

-   All stories to be completed with an appropriate level of testing.
-   No actual database implementation is required, feel free to stub it out.
-   No server side implementation is required, although it will be preferable to see how you handle client-server communication.
-   Your code should trend towards being SOLID.
-   Please don't spend too long on it, 60 minutes at most.

**General description:**

Create a simple single page CRUD application using AngularJS v 1.x. The application should allow to see a list of users, events, create/edit an event and link it to a user. You may use Bootstrap for styling and responsiveness.

  **Story 1**

  I want to see a list of users available in the system and number of events they should attend.

<!-- -->

-   Users should be prepopulated (up to 5-6 persons). Use a general fields for a person like Name, Age, Email etc.
-   Use a simple html table to display the users. Table columns: Name, Age, Email, Events (number of events user should attend), View Profile (link to user’s profile page).

**Acceptance criteria:**

-   Table should display all users ordered by name.
-   Clicking on Profile link should lead to user’s profile page.

**Story 2**

I want to see user details on the profile page.

**Acceptance criteria:**

-   The page should display user details and list of events the user should attend.
-   Events list should be in format “Title, Time (hh:mm, DD MMM YYYY)”, i.e. “Project planning – 13:30, 25 Jan 2016”.
-   Display upcoming events first ordered by date ascending, then past events ordered by date descending. Past evets should be dimmed.
-   I should be able to navigate to appropriate user’s profile page by URL.

**Story 3**

I want to see a list of upcoming events and number of attendees ordered by event time.

-   Use a simple html table to display the events. Table columns: Title, Time, Location, Attendees (number of attendees), Edit (link to edit event page).

**Acceptance criteria:**

-   Table should not display past events.
-   Event time should be in format “hh:mm, DD MMM YYYY”.
-   Clicking on Edit link should lead to edit event page.
-   Add Create event link above the table, it should navigate to create event page.

**Story 4**

I want to be able to create new and amend existing event.

-   Event fields:
    -   Title – required, maximum length 64 characters.
    -   Date & Time – required, cannot be in the past. You are allowed to use date and time pickers for convenience.
    -   Location – not required, maximum length 128 characters.
    -   Attendees – at least one person is required. UI control is up to your choice but it must support adding multiple persons.

**Acceptance criteria:**

-   The page should allow me to amend existing or create new event.
-   I should be able to add or remove attendees.
-   Title input should be focused by default. If you’re using “autofocus” attribute you must provide a support for older browsers as well.
-   Event should not be saved if any of the fields is not valid.
-   Invalid fields should be visually indicated so I can correct them.
-   I should be able to navigate to appropriate event page by URL.
