Simplified use case diagram for a course registration system:

```
                                  +---------------------+
                                  |    Course Catalog   |
                                  +----------+----------+
                                             |
                                             | View Courses
                                             |
                      +----------------------+-------------------------+
                      |                      |                         |
            +---------+--------+  +----------+---------+  +------------+---------+
            |   Student        |  |    Faculty         |  |     Administrator    |
            +---------+--------+  +----------+---------+  +------------+---------+
                      |                      |                         |
                      |                      |                         |
             +--------+--------+  +----------+---------+  +------------+---------+
             | Register for     |  |  Manage Courses   |  |     Manage Users     |
             | Courses          |  |  (Teaching)       |  |    (Admin Tools)     |
             +--------+--------+  +----------+---------+  +------------+---------+
                      |                      |                         |
                      |                      |                         |
          +-----------+----------+           |                         |
          |  Waitlist Courses    |           |                         |
          +-----------+----------+           |                         |
                      |                      |                         |
                      +----------------------+-------------------------+
```

In this diagram:

- **Actors**:
  - **Student**: Enrolls in courses, views course catalog, and manages their course registrations.
  - **Faculty**: Manages courses they teach, including updating course details, viewing enrolled students, and managing waitlists.
  - **Administrator**: Manages system-wide functionality such as user accounts, course catalog, enrollment quotas, and system settings.

- **Use Cases**:
  - **View Courses**: All actors can view the available courses in the course catalog.
  - **Register for Courses**: Students can register for courses they want to take.
  - **Manage Courses (Teaching)**: Faculty can manage the courses they teach, including updating course details, viewing enrolled students, and managing waitlists.
  - **Manage Users (Admin Tools)**: Administrators can manage user accounts, roles, and permissions within the system.
  - **Waitlist Courses**: Students can join waitlists for courses that are full, and faculty can manage the waitlists for their courses.

This diagram provides a high-level overview of the interactions between different actors and the system's core functionalities.
