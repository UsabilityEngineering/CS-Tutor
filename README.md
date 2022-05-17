# CS Tutor

Web application that allows Professors and Administrators to manage their student workers (tutors, graders, lab assistants, etc.) in terms of their hours, scheduling, and payroll.

## UX Team Members

* **[Nathan Whitney](https://usabilityengineering.github.io/ux-portfolio-the29ster/)** - Conducted interviews and surveys, Developed personas and scenarios, Wrote up Methods and Findings for the Phase 1 Report, Helped develop ideas for wireframes, Constructed the prototype, Wrote up executive summary for the Phase 2 Report.
* **[Thomas Shelton](https://usabilityengineering.github.io/ux-portfolio-tomleeshelton/)** - Conducted interviews and surveys, Developed personas and scenarios, Wrote up Conclusions and Caveats for the Phase 1 Report, Helped develop ideas for wireframes, Constructed the wireframes, Wrote up full report for the Phase 2 Report.

# User-Centered Design Artifacts
 
* [Personas and Scenarios](artifacts/PersonasandScenarios.pdf)
* [Wireframes](artifacts/CSTutor-Wireframe-V1.pdf)
* [Draft Prototype](https://xd.adobe.com/view/0e7cf291-2f1a-4e88-8e3a-31e7c6be2a19-5b2f/screen/ca615a03-1354-442e-9bb0-63902fd88c63?fullscreen&hints=off)

# Phase 1: Requirements Gathering

**Executive Summary**

The project's goal is to **make the scheduling and payroll process for student workers easier** for both faculty and the student workers themselves. In this requirements gathering phase, we reached out to different faculty members as well as students to get a grasp of how the current system works.

We interviewed **faculty members** to better understand how the current system works and to find out how satisfied they were with the current system.

* Chico State **faculty members (n = 3)** participated in 1-on-1 interviews
* All faculty members felt the current system is extremely **cumbersome**
* Faculty members that process timesheets are especially **displeased** with the process, because they have to email timesheets back and forth between multiple people to verify that it is correct.

We surveyed Chico State students to find out how many people have interacted with the current tutoring system and to see how satisfied they were with the current system.

* Online survey received **(n = 12) students' responses**
* **58.3%** of students were **interested in getting tutoring**
  * Out of the students who were interested in getting tutoring, only **28.6%** of students have **gotten tutoring**
  * The other **71.4%** have not gotten tutoring for the following reasons: **not enough hours available, not sure where to go for tutoring, and time constraints.**

From the requirements gathering, we identified common user needs

* Faculty members need an **easier way of verifying timesheets** and other data from their student workers
* The tutoring system needs to be **easier to access** for students to actually take advantage of it

[Full phase 1 report](requirements/)

# Phase 2: User-Centered Design

**Executive Summary**

In this user-centered design phase, we accomplished our goals of creating wireframes and getting a working click-thru prototype taking into account what we learned from our previous information gathering.

We planned out some ideas for our wireframes and ended up choosing a **calendar based** approach to our design.

* The left panel has information on what is **currently** going on the screen
* The middle is where the calendar is which allows the user to have an **at a glance** look of the tutors working and available.
* The left panel shows **more information** based on which cell of the calendar is clicked.

With our wireframes in mind, we created a click-thru prototype that allows us to better **understand the workflow** of our users.

[Full phase 2 report](design/)

# Phase 3: Usability Evaluation

**Executive Summary**

In this usability evaluation phase, we accomplished our goals of testing and making sure our prototype was exactly how we wanted it. We conducted heuristic evaluations, cognitive walkthroughs, and usability tests using a protocol that we created.

In our heuristic evaluation we used a likert scale of 1 (Very Bad) to 5 (Very Good). We were able to determine people's initial impressions of our interface without extensive usability testing.

Here's a list of significant complaints:
* Lack of helpful documentation.
* Lack of prototype functionality.
* Filter system may be restrictive.

Here's a list of significant compliments:
* Good system visibility.
* Filter system could also be very useful.
* Calendar was familiar.
* Minimalist aesthetic prevented information overload.
* Tri-Column layout prevented users from needing to remember much.

------ Cognitive Walkthrough:
Users tended to pick Ortegga in our cognitive walkthrough, providing us only with the student side of the persona/scenario evaluation. Even though it made it harder to make improvements to the faculty side of things, enough carried over to make this data useful to the entire system.
Users overall shared our mental model of the entire system, and navigated it in a relatively predictable way. They were able to make connections between the calendar cells and the right-sidebar.
Comments were made that the "add a tutoring session" button, represented by a plus, was a bit too vague. Another user attempted to use this button as a student when it was intended for faculty use. This threw off their evaluation of the interface, as they thought they had completed the task, when they had to click on the "contact" button instead.
Overall, the cognitive walkthrough gave us useful information, and the insight to make whether or not sessions are "drop-in" or "scheduled-only" more apparent.
------ Protocol PDF, Interactive Prototype & Data Collection Spreadsheet:
Links to this information can be found in the Full Report.
------ Cognitive Walkthrough:
We designed three tasks based off of the feedback we received, as well as the changes we made to our UI/UX. The first task tested the search bar, as well as user understanding of the filtering system. We wanted to understand how well we were following existing standards, and how intuitive our overall interface was to users without a training session.
The second task asked the users to assume the role of faculty. We wanted to see if the "add a tutoring session" button, represented by a plus symbol, was intuitive enough to users. We had previously received complaints that this button was ambiguous given its lack of a label. Ultimately, we wanted to gauge whether or not users would get lost and feel a lack of control over their ability to manipulate the interface.
The final task tested deleting a tutoring session. This task tested to see if users could relate the card list on the right sidebar to tutoring sessions. This allowed us to see how well users could manipulate the scheduling system. This also showed us whether or not users could intuitively guess where the "delete" button was, despite it being hidden in a shelf close to the user's name.
We also conducted wrap-up questions that would allow us to get an idea of how users perceived the "bigger picture" of the product. This ranged from likes and dislikes to ideas for feature improvements.
------ Methodology:
We chose the "think-aloud" method since we needed to understand how close our mental model of the system was to the user's. We also chose a formative evaluation method, so that we could quickly make changes and rapid improvements on the prototype to improve the overall user experience. 
------ Data Interpretation:
With a sample size of 5 users, we utilized a likert scale of 1 (Very Bad) to 5 (Very Good) to help interpret user feedback. Users tended to immediately use the search bar when performing the first task, and intuitively understood the tri-column layout of the app. The "Tutor List" button in the left sidebar was a little confusing. Because of this, we decided to change the words "Tutor List" to "Payroll," which is much more indicative of the actual purpose of this section. Ease of performing the first task was rated a 4 by three users and a 5 by two users.
The second task revealed that most users were still able to add a tutoring session using the plus button, which was the opposite of what we were expecting. A minority of users still encountered confusion, and mentioned we should label this button. Ease of performing this task was rated a 2 by a single user, 5 by three users and a 4 by a single user. The lowest score came from the user's perception that other people might have difficulty with the task, but made a note that they had little difficulty with it because of their previous experiences.
The third task surprised us, as a majority of users found the delete option hidden within a hamburger menu. Only a single user had issues with this. This user rated the task at a 4, while all other users rated the task at a 5, making the deletion process one of the highest rating tasks we tested for.
Users' overall assessments of our design were positive. We received a few recommendations, from a "block-style" weekly view to removing the "common tags" section of the interface. We also realized our prototype did not completely reflect the final product in ways that confused a few users.


[Full phase 3 report](evaluation/)
