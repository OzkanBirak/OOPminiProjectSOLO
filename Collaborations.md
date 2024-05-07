Below is a chart for collaborations in the Course Registration System. Each example includes the three titles: "An object of class...", "sends the message...", and "to an object of class...".

```
|--------------------------------------------------------------------------------------------------------|
| An object of class...                | sends the message...                  | to an object of class...     |
|--------------------------------------------------------------------------------------------------------|
| Student                              | RegisterForCourse(courseCode)         | Course                       |
|--------------------------------------------------------------------------------------------------------|
| Student                              | DropCourse(courseCode)                | Course                       |
|--------------------------------------------------------------------------------------------------------|
| Student                              | JoinWaitlist(courseCode)              | Waitlist                     |
|--------------------------------------------------------------------------------------------------------|
| Student                              | ViewEnrolledCourses(studentID)        | Registration                 |
|--------------------------------------------------------------------------------------------------------|
| Faculty                              | ManageCourses(action, courseInfo)     | Course                       |
|--------------------------------------------------------------------------------------------------------|
| Faculty                              | ConfirmEnrollment(studentID, courseCode)| Registration               |
|--------------------------------------------------------------------------------------------------------|
| Faculty                              | ViewEnrolledStudents(courseCode)      | Registration                 |
|--------------------------------------------------------------------------------------------------------|
| Administrator                        | ManageUsers(action, userInfo)         | UserManagement               |
|--------------------------------------------------------------------------------------------------------|
| Administrator                        | ConfigureSystem(adminID, settings)    | System                       |
|--------------------------------------------------------------------------------------------------------|
| System                               | AuthenticateUser(username, password)  | UserAuthentication           |
|--------------------------------------------------------------------------------------------------------|
| Course                               | EnrollFromWaitlist()                  | Waitlist                     |
|--------------------------------------------------------------------------------------------------------|
| Course                               | UpdateCourse(courseInfo)              | Course                       |
|--------------------------------------------------------------------------------------------------------|
| Registration                         | ProcessRegistration(registrationInfo)| Course                        |
|--------------------------------------------------------------------------------------------------------|
| Registration                         | WithdrawFromCourse(studentID, courseCode)| Course                     |
|--------------------------------------------------------------------------------------------------------|
```

In this chart:

- **An object of class...**: Represents the class initiating the interaction.
- **sends the message...**: Describes the action being performed by the initiating class.
- **to an object of class...**: Identifies the class that receives and processes the message.
