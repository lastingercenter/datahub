# Learner Usage data file  
## About   
The Learner Usage data set includes the activity in the D2L course platform for learners in course oƯerings
provided by the Lastinger Center in 2023 and Jan-Apr 2024. All learners are Florida educators in birth-12 
organizations.  
Files for the same learners and time period are available that include grades, instructor activity, and content 
progress.  
## Fields  
* Course Offering Id: Unique course offering numeric identifier in Brightspace.  
* Course Offering Code: Course offering string code. 
* Course Offering Name: Course offering string name.  
* Parent Department Name: Org unit name of the parent department.  
* Parent Department Code: Org unit code of the parent department.  
* Semester Id: Unique semester numeric identifier in Brightspace. If a course is not associated with a semester, the value is NULL.  
* Semester Code: Semester code associated with the course offering. The semester is the organization unit type as defined by the Standard Semester in Brightspace. 
If a semester is not associated as a direct parent of the course offering being exported, the value is NULL. If a course oƯering is associated with multiple semesters, these are exported as a pipe-delimited list of strings.  
* Semester Name: Semester name associated with the course offering.  
* User Id: Internal numeric user identifier within Brightspace.   
* Username: User name that identifies the learner.  
* Org Defined Id: Organization-defined identifier within Brightspace for the learner.   
* First Name: First name.  
* Last Name: Last name.  
* Is Active: Learner's status.  
* Role Id: The learner's numeric role ID within the course offering.  
* Role Name: A string identifying the learner's role within the course offering such as Learner.  
* Content Completed: Number of content topics completed by the learner.
* Content Required: Number of content topics required by the learner (for user progress).  
* Checklist Completed: Number of checklists completed by the learner.   
* Quiz Completed The total number of unique quizzes the user has attempted and completed. This does not include quizzes that are in progress.   
* Total Quiz Attempts: The total number of quiz attempts the user has attempted and completed. This does not include quiz attempts that are in progress.   
* Discussion Post Created: Number of discussion posts created by the learner.   
* Discussion Post Replies: Number of discussion replies by the learner.   
* Discussion Post Read: Number of discussion posts read by the learner.   
* Last Discussion Post Date: Date the user last posted to a discussion. If the user has not posted in any discussion, this field is NULL.   
* Number Of Assignment Submissions: Number of times the learner submitted an item to assignments within the course offering.  
* Last Assignment Submission Date: Date/time the learner’s last submission/post into an assignment.  
* Total Time Spent In Content: Sum of all the time spent in course content, measured in seconds. If the learner has not visited any of the content in this course, this field is ZERO. If the learner has multiple instances or tabs open with the same content, this tracks each instance as a separate session, and as a result, substantially increases total time spent.   
* Last Visited Date: Most recent visit date/time for the course. If the course has not been visited by the learner, this field is NULL.  
* Last System Login: Date/time the learner last logged in to Brightspace.  
* Number Of Logins To The System: Total number of times the learner logged in to Brightspace.   
* Auditor Name: Username of the user who is assigned as the auditor for this learner.   
* Last Quiz Attempt Date: Date the learner last attempted and completed a quiz.   
* Last Scorm Completion Date: Date the learner last completed a SCORM object.   
* Last Scorm Visit Date: Date the learner last launched or interacted with a SCORM object.   
