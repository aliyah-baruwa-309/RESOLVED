PRODUCT REQUIREMENTS DOCUMENT (PRD) FOR RESOLVED: A project by the Tech Nova group, dedicated to helping hostel residents to seamlessly resolve maintenance issues on campus.

PRODUCT OVERVIEW

RESOLVED is a software application that connects hall/hostel residents (students) to artisans who work for Babcock University. The application is designed to remove the need for middlemen (hall porters) and automate the complaints process, allowing for a streamlined approach to resolving these complaints.

PROBLEM STATEMENT

Research carried out shows that students residing in the hostels on campus usually find it very difficult to lodge complaints and have them addressed in good time. These problems include several maintenance and facility issues under categories such as electrical, carpentry, and plumbing. This is because these complaints are not properly documented, as a "complaints notebook" is kept by the hall porters and administrators. These notebooks are flimsy and are not properly looked after; hence, their pages often fall out, leading to data loss. There is also an issue of disorderliness when artisans visit the halls to carry out their duties, as they often use loud voices to disturb the residents when reminding students to lodge their complaints. Finally, hall porters are tasked with the duty of reviewing the complaints notebook to contact the appropriate service providers each day.

This leads to a load of unresolved issues and forces students to live in environments that are not conducive to living. For instance, on interviewing Deji, a student of Babcock University, he stated that he had to purchase a portable rechargeable fan when the ceiling fan in his room was faulty for months. This shows that improper management of records costs students both their finances and their peace of mind. There is therefore a need for a centralized platform that connects students and hall residents directly to artisans, removing the complexities and unreliability of middlemen. However, these middlemen (hall porters and administrators) could be assigned other roles, such as supervision and monitoring.

TARGET USERS

Primary Users - Students residing in Babcock University hostels who need to report and track maintenance issues such as electrical, plumbing, and carpentry faults.
Secondary Users - Babcock University Artisans and maintenance personnel responsible for receiving and resolving students' complaints.
Administrative Users - Hall Porters and Hostel Administrators, responsible for overseeing maintenance activities, monitoring complaints, and ensuring their timely resolution.

USER STORIES 

Students and Hostel Residents:
1) As a hostel resident, I want to submit maintenance complaints through the application so that I can report issues without going through a hall porter.
2) As a student, I want to track the status of my complaints so that I know when they are being addressed.

Artisans (Service Providers):
1) As an artisan, I want to view maintenance requests so that I can attend to them promptly.
2) As an artisan, I want to access relevant complaint details so that I can understand the issue before attending to it.
3) As an artisan, I want to update the status of assigned complaints so that students are informed of the progress.

Hall Porters and Hostel Administrators:
1) As a hall porter, I want to monitor submitted complaints so that I can oversee maintenance activities within the hostel.
2) As a hostel administrator, I want to view resolved and unresolved complaints so that I can monitor the efficiency of maintenance services.
3) As an administrator, I want to access complaint records so that maintenance activities are properly documented and accountable.

FUNCTIONAL AND NON-FUNCTIONAL REQUIREMENTS

FUNCTIONAL REQUIREMENTS

1) Students can create accounts and log in.
2) Students can submit maintenance complaints with descriptions.
3) Students can track the resolution status of their complaints.
4) Artisans can create accounts and log in.
5) Artisans can view maintenance requests in detail.
6) Artisans can update complaint statuses for students to view.
7) Administrators can manage student and artisan accounts.
8) Administrators can view all submitted complaints.
9) Administrators can monitor pending and resolved complaints.

NON-FUNCTIONAL REQUIREMENTS

1) Performance: 
The application should load pages within a reasonable time. 
The application should be able to handle multiple users accessing the platform without crashing or slowing down.

2) Security:
The application should protect users' personal information (login credentials).
The application should restrict access to certain features based on user roles (students/residents, artisans, hall administrators). Another student should not be authorized to update the resolution status of another student's complaint.

3) Usability: 
The application should have a user-friendly interface.
The application should be accessible to users with minimal levels of technical expertise.
Users should be able to submit and track maintenance complaints with little to no difficulty.

4) Reliability:
The application should prevent the loss of complaint records.
The application should ensure that submitted complaints are properly stored and accessible.

5) Scalability:
The application should accommodate increasing numbers of users (students, artisans, administrators) without significant performance issues.

6) Maintainability:
The application should allow developers to fix bugs, implement updates, and introduce new features without disrupting existing functionality.

MINIMUM VIABLE PRODUCT (MVP)
These are the essential features for the first version of RESOLVED:

1) User Authentication - Every category of user should be able to log in.
2) Complaint submission - Students should be able to provide descriptions of their complaints according to the selected category.
3) Complaint management - Administrators should be able to view detailed records of submissions from students.
4) Complaint tracking - Students should be able to monitor the progress status of their complaints.
5) Artisans should be able to view submitted complaints and update the complainant on the progress status. 

ACCEPTANCE CRITERIA

1) Users must provide valid email addresses and passwords during login.
2) A user must have an assigned role (resident, artisan, administrator) and must not access any features outside his/her role.
3) Invalid login credentials rejected at login must be accompanied by an appropriate error message.
4) A complaint category must be selected at the point of complaint submission, alongside detailed descriptions and location details (room number, name of hostel). Descriptions must not exceed the provided character limit.
5) Artisans' selected area of expertise must match the category of complaints that they are allowed to view.
6) Changes to complaint status must be reflected on the students' dashboard alongside the dates and times of updates.
7) Each complaint must have a status at every point in time - Pending, In Progress, or Resolved.
8) Only authenticated administrators should have access to the administrator dashboard.

SCOPE

IN SCOPE (High-Priority):
1) Direct connection between students and university-employed artisans through an administrator-managed process.
2) Centralized storage and retrieval of complaint records.
3) Monitoring and documentation of maintenance activities by administrators.

OUT OF SCOPE(Medium-Priority):
1) Uploading picture attachments of maintenance issues when filing complaints.
2) Filtering of complaints by category and status by the administrator for easier management.
3) Maintaining a centralized database of complaint records for storage, tracking, and future reference.
4) Allowing students to rate artisans based on their service delivery and efficiency.

OUT OF SCOPE(Low-Priority):
1) In-app real-time messaging between students and artisans.
2) AI-based artisan recommendations, excluding artisans who are offline or away from work.
3) Automated responses to acknowledge students' complaints.
4) Proximity-based artisan suggestions to improve faster resolution of complaints.

OPEN-ENDED AND UNANSWERED QUESTIONS

1) How will the university officially recognize and approve the use of RESOLVED?
2) How will the application obtain and maintain an updated list of university-employed artisans?
3) How will urgent maintenance issues be identified and prioritized?
4) What measures will ensure that complaints are resolved within a reasonable timeframe?
5) How will the system handle complaints that require multiple artisans?
6) What happens when a student is dissatisfied with the resolution provided?


