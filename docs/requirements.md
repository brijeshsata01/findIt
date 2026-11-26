
# FINDIT – SYSTEM REQUIREMENTS

## 1. Functional Requirements

### 1.1 Student Module

01: The system shall allow students
to register an account.

02: The system shall allow students
to log in and log out.

03: Students shall be able to report
lost items.

04: Students shall be able to report
found items.

05: Students shall be able to upload
photographs of reported items.

06: Students shall be able to view
uploaded item photographs.

07: Students shall be able to search
and filter lost and found items.

08: Students shall be able to view
item details.

09: Students shall be able to submit
claim requests.

10: Students shall be able to track
their reports and claim requests.

11: Students shall be able to update
or cancel their own reports, subject to
system rules.

### 1.2 Admin Module

12: The system shall provide secure
admin authentication.

13: Admin shall be able to view
dashboard information.

14: Admin shall be able to manage
student accounts.

15: Admin shall be able to view and
manage lost and found reports.

16: Admin shall be able to upload
and view item photographs.

17: Admin shall be able to verify
item reports.

18: Admin shall be able to review
claim requests.

19: Admin shall be able to approve
or reject claim requests.

20: Admin shall be able to update
item statuses.

21: Admin shall be able to handle
fake and duplicate reports.

## 2. Non-Functional Requirements

01: The application should provide
good response time.

02: User passwords must be stored
securely using password hashing.

03: The system must implement
role-based access control.

04: The interface should be
user-friendly and easy to navigate.

05: The application should support
mobile, tablet and desktop screens.

06: The system should handle
invalid inputs and errors properly.

07: The system should maintain
data consistency.

08: User personal information
should be protected.

09: The application should be
maintainable and modular.

10: Image uploads must include
file type and size validation.

## 3. System Modules

1. Student Authentication Module
2. Admin Authentication Module
3. Lost Item Management Module
4. Found Item Management Module
5. Image Management Module
6. Search and Filter Module
7. Claim Management Module
8. Admin Dashboard Module
9. Student Management Module
10. Status Management Module

## 4. Business Rules

1. Only authenticated students can
   submit item reports.

2. Admin and student permissions
   must be different.

3. Only authorized administrators
   can approve or reject claims.

4. Ownership must be verified before
   returning an item.

5. Returned items must have an
   updated status.

6. Invalid and rejected reports must
   not appear in normal public listings.
