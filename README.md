<h1>Attendance Marking App | Power Apps & Power Automate</h1>

<h2>Description</h2>
This project is an Attendance Marking App developed to streamline onboarding attendance management for new hires.  
The solution automates attendance tracking, onboarding session monitoring, reminder workflows, and audit record management to support LMS and Workday attendance processes during periods of high onboarding volume.
<br />

<h2>Tools and Technologies Used</h2>

- <b>Power Apps</b>
- <b>Power Automate</b>
- <b>SharePoint Lists</b>
- <b>Microsoft 365</b>

<h2>Business Problem</h2>

As onboarding volume increased, manual attendance tracking became difficult to manage consistently across onboarding sessions.

Key challenges included:

- Tracking attendance across multiple onboarding batches
- Maintaining audit-ready attendance records
- Monitoring onboarding completion rates
- Following up with employees who missed sessions
- Preparing attendance data for LMS and Workday enrollment updates
- Reducing repetitive manual administrative work

<h2>Solution Overview</h2>

The Attendance Marking App was designed as a centralized onboarding attendance management solution.

The application automates the onboarding attendance workflow from Talent Acquisition data intake to attendance monitoring and follow-up tracking.

</b>
<img src="https://github.com/hatr201610-cyber/Attendance-Marking-App/blob/91387f491c62adbfee084ab5cacb9ab4a2eba470/Attendance%20Marking%20App.jpg" height="80%" width="80%" alt="Disk Sanitization Steps"/>
</b>

<h2>Workflow Architecture</h2>

<p align="center">

TA New Hire List <br/>
↓ <br/>
Power Automate Flow <br/>
↓ <br/>
SharePoint Attendance Tracking List <br/>
↓ <br/>
Power Apps Attendance Interface <br/>
↓ <br/>
Attendance Monitoring & Reminder Flow <br/>
↓ <br/>
Workday / LMS Enrollment Tracking

</p>

<h2>Key Features</h2>

<h3>1. Automated New Hire Data Processing</h3>

- Pulled onboarding data directly from Talent Acquisition new hire lists
- Automated duplication of records into a secondary SharePoint attendance tracking list
- Generated onboarding attendance tracking framework for each training session

<h3>2. Attendance Marking Interface</h3>

The app interface allows facilitators to:

- Filter onboarding sessions by:
  - Onboarding date
  - Training session
  - Department
  - Employee name
- Mark attendance status:
  - Attended
  - Did Not Attend
  - Partially Attended
- Add attendance remarks
- Submit attendance records directly into SharePoint

<h3>3. Attendance Monitoring & Reporting</h3>

- Attendance data stored centrally for:
  - LMS attendance tracking
  - Workday enrollment updates
  - Audit documentation
- Attendance completion rate monitoring
- Identification of employees with incomplete onboarding sessions

<h2>Application Interface</h2>

<p align="center">

The interface provides a structured attendance marking experience with onboarding session filters, employee attendance status selection, and attendance remark tracking.  
Employee images within the production application were blurred for privacy and data protection purposes.

</p>

<h2>Business Impact</h2>

- Reduced manual attendance consolidation effort
- Improved onboarding attendance visibility
- Increased onboarding completion tracking accuracy
- Supported audit and compliance requirements
- Streamlined LMS and Workday attendance processes
- Improved operational efficiency for Learning & Development teams

<h2>Key Learning Outcomes</h2>

- Workflow automation using Power Automate
- Low-code application development with Power Apps
- SharePoint list architecture and integration
- Attendance tracking process optimization
- HR operations process automation
- User-focused internal application design

<!--
 ```diff
- Manual onboarding attendance tracking
+ Automated attendance management system
! Faster onboarding follow-up process
# Improved attendance visibility and compliance
@@ Reduced administrative workload @@
