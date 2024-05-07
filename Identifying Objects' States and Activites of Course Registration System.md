In a course registration system, various objects undergo states and activities as users interact with the system. Here's an overview of the potential states and activities for key objects within the system:

1. **Course**:
   - **States**:
     - Available: The course is open for registration.
     - Full: The course has reached its enrollment limit.
     - Closed: Registration for the course is closed.
   - **Activities**:
     - Creation: Adding a new course to the system.
     - Modification: Updating course details such as schedule or instructor.
     - Deletion: Removing a course from the system.

2. **Student**:
   - **States**:
     - Active: The student is currently enrolled in the institution.
     - Inactive: The student has left or taken a break from the institution.
   - **Activities**:
     - Registration: Enrolling in courses for the semester.
     - Waitlisting: Joining the waitlist for a course that is full.
     - Payment: Settling course fees and financial transactions.

3. **Faculty**:
   - **States**:
     - Active: The faculty member is currently employed by the institution.
     - Inactive: The faculty member has left the institution.
   - **Activities**:
     - Course Management: Adding, updating, or removing courses they teach.
     - Enrollment Verification: Confirming enrolled students in their courses.
     - Waitlist Management: Managing waitlists for their courses.

4. **Administrator**:
   - **States**:
     - Active: The administrator has access to system functions.
     - Inactive: The administrator account is disabled or removed.
   - **Activities**:
     - System Configuration: Setting up registration periods, enrollment limits, etc.
     - User Management: Managing student, faculty, and other administrator accounts.
     - Reporting: Generating reports on enrollment statistics, financial data, etc.

5. **Registration**:
   - **States**:
     - Pending: The registration request has been submitted but not yet processed.
     - Confirmed: The student is successfully enrolled in the course.
     - Denied: The registration request is rejected, often due to enrollment limits.
   - **Activities**:
     - Registration Submission: Student submits course preferences.
     - Enrollment: Adding the student to the course roster.
     - Waitlist Handling: Promoting students from the waitlist to enrolled status.

6. **Waitlist**:
   - **States**:
     - Active: The student is on the waitlist for a course.
     - Inactive: The student has been removed from the waitlist (e.g., due to enrollment).
   - **Activities**:
     - Waitlist Joining: Student joins the waitlist for a full course.
     - Position Update: Changing the student's position in the waitlist based on priority.
     - Waitlist Removal: Student is removed from the waitlist (e.g., due to enrollment).

7. **System**:
   - **States**:
     - Online: The system is operational and accessible to users.
     - Offline: The system is temporarily unavailable (e.g., maintenance or technical issues).
   - **Activities**:
     - Maintenance: Performing system updates or database maintenance.
     - Backup: Regularly backing up system data to prevent data loss.
     - Recovery: Restoring system functionality after an outage or failure.
