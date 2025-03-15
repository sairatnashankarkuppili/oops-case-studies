# School Management System Case Study

## Problem Statement
Design an object-oriented school management system that manages student enrollment, tracks academic performance, schedules classes, manages faculty, and handles administrative tasks.

## System Requirements
1. **Student Management**:
   - Store student personal and academic information
   - Track enrollment in courses
   - Record grades and attendance

2. **Faculty Management**:
   - Store faculty information and qualifications
   - Assign faculty to courses
   - Track faculty workload and schedules

3. **Course Management**:
   - Define different course types and subjects
   - Manage course schedules and classrooms
   - Handle assignments and grading

4. **Administrative Functions**:
   - Generate transcripts and report cards
   - Process student admissions and withdrawals
   - Manage school calendar and events

5. **Resource Management**:
   - Classroom allocation
   - Library resources
   - Educational equipment

## Classes and Relationships

**Person-related Classes:**

**Academic-related Classes:**

**Administrative Classes:**

**Resource Classes:**


## Key OOP Concepts to Identify

1. **Inheritance**: Person → Student/Faculty/Staff
2. **Encapsulation**: Private grade data with controlled access
3. **Polymorphism**: Different course types have different grading policies
4. **Abstraction**: Base classes define common interfaces
5. **Composition**: School contains Departments, Departments offer Courses
6. **Aggregation**: Faculty teaches Courses, Students enroll in Courses
