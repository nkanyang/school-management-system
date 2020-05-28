## Ivy School Management System

**Objective:** Deliver a teaching management system which includes:
- assigns students to specific classes
- supports one classroom to host one class at a specific period
- assigns one teacher to be responsible for one classroom
- submits and reviews assignments

**Level** Three

#### UI Deisgn(Reference)

Add Student

![find](Teachable-System/add-student.png)

Course Details

![find](Teachable-System/course-details.png)

Course List

![find](Teachable-System/course-list.png)

List Student

![find](Teachable-System/list-student.png)

Student Details

![find](Teachable-System/student-details-2.png)

Student Details

![find](Teachable-System/student-details.png)

Student Enroll Course

![find](Teachable-System/student-enroll-course.png)

List Owners

![find](Teachable-System/list-owners.png)

#### Site Structure

- Student Profile:
	- Avatar
	- Name
	- Email
	- School
	- Mobile
	- City
	- Address
	- Introduction
	- Title
	- Enrolments
	- Assignments
- Course Profile:
	- Name
	- Course Code
	- NumberOfStudents
	- PrerequisiteKnowledge
	- CourseLength
	- TeachingMethod
	- CIty
	- CourseObjective
	- Level
	- CommenceDate
	- StartAppliedDate
	- CompleteDate
	- Tuition
	- Teachers
	- Project
	- Assignment
	- Thumbnail
	- Address
- Teacher Profile:
	- Name
	- Title
	- Avatar
	- School
	- Mobile
	- Company
	- Introduction
	- Course
	- Assignment
- Assignment Details
	- Name
	- Title
	- Content
	- Acceptance Criteria 
	- Belong to

#### Features

Only authenticated admin could manage all users, products, service .etc.
Teacher
- CRUD course and wait for approval
- assign course
- Manage assignment
- View students’ assignment

Student
- Login/ Register
- Enroll courses
- Update profile 
- Upload avatar
- Payment
- View Class
