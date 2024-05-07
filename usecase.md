Simplified use case diagram for a course registration system:

EX 1
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


---

EX2 

Here is a more detailed Use Case Diagram for a Course Registration System:

```
System: Course Registration System

Actors: Student, Registrar, Instructor, System Administrator

Use Cases:
1. Student -> Register for Course: A student can register for a course through the system.
2. Student -> Drop Course: A student can drop a course they are registered for through the system.
3. Student -> View Course Catalog: A student can view the available courses in the system.
4. Student -> View Registered Courses: A student can view the courses they are currently registered for.

5. Registrar -> Add Course: The registrar can add a new course to the system.
6. Registrar -> Remove Course: The registrar can remove a course from the system.
7. Registrar -> Update Course: The registrar can update the details of a course in the system.
8. Registrar -> View Course Registration: The registrar can view the list of students registered for a specific course.

9. Instructor -> View Course List: An instructor can view the courses they are assigned to.
10. Instructor -> Update Course Information: An instructor can update the information of the courses they are assigned to.

11. System Administrator -> Create User: The system administrator can create a new user in the system.
12. System Administrator -> Update User: The system administrator can update the details of a user in the system.
13. System Administrator -> Delete User: The system administrator can delete a user from the system.

```

