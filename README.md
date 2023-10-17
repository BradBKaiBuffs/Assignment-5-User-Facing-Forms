# Assignment 5: User Facing Forms

## Tasks completed
1. Added all models to the Django admin
2. Added in a few records
3. In a separate user-facing view, show a list of all records of each model type using dedicated individual pages or a single page
4. Also included the ability to sort these records by column

## Assignment Detail
1. Each model (Student, Course, Major, Requirement, Enroll, Course_requirement, Major_requirement, Major_selection) has a creation and edit user form. The dedicated pages for address 127.0.0.1:8000/:

- majors/<int:pk>/
- majors/new/
- students/<int:pk>/
- students/new/
- courses/<int:pk>/
- courses/new/
- coursereq/<int:pk>/
- coursereq/new/
- majorsel/new/
- majorsel/<int:pk>/
- majorreq/new/
- majorreq/<int:pk>/
- enroll/new/
- enroll/<int:pk>/
- requirement/new/
- requirement/<int:pk>/

Example: 127.0.0.1:8000/majors/1 to edit ID #1 and 127.0.0.1:8000/majors/new/ to create a new entry
   
2. User will need to view each model under it's own dedicated page. The dedicated pages for address 127.0.0.1:8000/ are:

  - Student/
  - Major/
  - Course/
  - Requirement/
  - Major_requirement/
  - Major_selection/
  - Enroll/
  - Course_requirement/
  
Example: 127.0.0.1:8000/Student/ to view student records in a table
