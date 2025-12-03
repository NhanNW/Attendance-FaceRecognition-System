Attendance Face Recognition System. 
Project Status: 70%–80% Completed. 
This system is designed to help organizations manage employee attendance using facial recognition technology. It includes modules for user management, authentication, attendance tracking, shift scheduling, department operations, and face-based check-in/check-out.

I am responsible for:
- Designing the entire SQL Server database (tables, relationships, ERD)
- Building most of the backend APIs using Node.js & Express
- Implementing business rules using stored procedures & SQL logic
- Integrating facial recognition descriptor matching in attendance flow

1. Facial Recognition Attendance
Employees check-in/check-out using facial recognition descriptor comparison
Ensures timestamp accuracy
Automatically determines late/on-time status

2. Role-Based Authentication
Admin: System-level controls
Manager: Approve leave, view attendance reports
Employee: View daily schedule, request leave, check-in/check-out

3. Attendance Management
Daily attendance per shift (CheckIn, CheckOut, Status)
Automatic rules enforced by SQL triggers
API support for updating missing check-out

4. Work Scheduling
Assign shifts using the WorkSchedule table
Prevents check-in for employees who are not scheduled

5. Leave Management
Employees can submit leave requests
Manager/Admin approves or rejects
Auto-populates Attendance during approved leave periods

6. Department & Employee Management
Department creation
Employee profile management

Tech Stack
- Backend: Node.js, Express
- Database: SQL Server
- Face Recognition: face-api.js
- Other: bcrypt/argon2, REST APIs

Repository is still being updated as development continues. 
