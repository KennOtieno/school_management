# Multitenant School Management System
This is  a Laravel web application with the following features:

1. Multitenancy
Multiple schools(tenants) share a single database, with data isolation enforced by a tenant_id column.

  * Core Functionality:
    - Manage school specific students, teachers, and courses.
    - Track student enrollments in courses or classes.
    - Provide a dashboard with school statisctis.

2. Database
6 tables entailing (Tenants,Users, Students, Teachers, Classes / Courses, and Enrollments.

   * User Roles
     - School admins(e.g Bursars or Principals) manage their school's data.
     - A super admin sets up schools and users. // Still on development phase.

3. Technology Stack: Laravel(a PHP framework), MySQL database, and Bootstarp for Ui.

   * This Project's focus is to:
     Login, Dashboard,Data Management,Enrollments, and switching between schools to show multitenancy.
