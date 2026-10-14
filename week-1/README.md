# Week 1 – Planning (Oct. 7, 2026)

Week 1 is the planning step of the course. It has three tasks:

1. Set up the team repository with GitHub Classroom
2. Form a team
3. Understand the RFP

**Deliverable:** team profile

---

## 1. GitHub Classroom assignment

All project work (code, diagrams, reports) must be shared in the team's GitHub repository.
The repository is created through GitHub Classroom. Full instructions with screenshots are in
[github_assignments.pdf](github_assignments.pdf).

Steps:

1. **Open the invitation link** from the lecturer (`https://classroom.github.com/a/...`).
   Each assignment has its own link.
2. **Sign in to GitHub.** Create an account first if you do not have one.
3. **Join the classroom roster.** Select your entry in the form
   `studentID_firstname_lastname`. Double-check before clicking.
4. **Join or create a team.** Click *Join* next to an existing team, or type a new team name
   and click *Create team*. The team cannot be changed later, so choose carefully.
5. **Accept the assignment.** Check it is the right assignment, then click
   *Accept this assignment*.
6. **Wait for the repository to be prepared.** GitHub copies the starter contents into a
   new repository in the course organization. You may also get an email invitation to join
   the organization.
7. **Open the repository and start working.**

## 2. Team forming

- Teams have **3–5 students**.
- The whole team works in one shared repository.
- The team product is graded once and every member receives that score. The individual
  interview and each member's repository activity are graded per person, so every member
  should commit their own work.

### Team profile

| Item | Details |
|------|---------|
| Team name | _TBD_ |
| Members (student ID, name, role) | _TBD_ |
| Repository | _TBD_ |
| Communication channel | _TBD_ |
| Regular meeting time | _TBD_ |

## 3. Understanding the RFP

The project theme is the **"Lab Student Management System"**
([RFP](../ie04_project2026_RFP.pdf)).

**Problem.** Professors at the University of Aizu advise undergraduate and graduate students
in their labs. Today they track students, projects and meetings with a mix of spreadsheets,
chat tools and project-management tools. The new system should replace the spreadsheets and
reduce the professor's workload.

**Users.**
- *Instructor (professor)*: registers students, manages projects, milestones and meetings.
- *Sub-instructor*: another faculty member who co-instructs and enters their available slots.
- *Students*: view projects, milestones and meeting schedules, and enter their course schedules.

**Required functions.**
- **Student registration**: student ID, name, entry and planned graduation year/month,
  program (undergraduate, master's, doctoral), university email.
- **Project planning**: projects (ID, title, description, external links such as GitHub)
  and milestones (date/time, title, status: planned / late / completed, completion date).
- **Regular meeting scheduling**: the system suggests slots that avoid students' classes and
  match instructor/sub-instructor availability. The professor makes the final choice.
  Meetings can be individual or group, and use class-period slots (including half-slots).
- **Project status**: everyone can see meeting schedules, tasks and milestone status.

**Things we are asked to propose.**
- An easy way to enter course schedules, with checks that prevent invalid input
- A clear visualization of the project schedule
- Reminders for meetings and milestones
- Export of meetings and milestones as iCalendar (`.ics`) files
- Extra features that improve usability or administration

**Constraints.**
- Usable on and off campus from users' own devices; ideally no installation needed
  (for example, a web app).
- All data stored in a database. No paid online database service.
- Any online service must use a dedicated project account, handed over at delivery.
- Manages one lab for now, but should allow multiple labs later.
- Language and frameworks are our choice.

**Process.** Weekly progress reports, at least three demos (weeks 5, 8, 11), and delivery on
**Feb. 3, 2027**.

### Open questions for the team

- Web app or installed client?
- Which language, framework and database (free, self-hosted)?
- How do students enter their course schedules quickly and correctly?
- How should slot suggestions be ranked when there is no perfect slot?
- How are reminders sent (email, in-app, calendar)?
