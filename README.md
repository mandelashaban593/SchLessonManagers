#  Web application for managing lessons on a calendar in Laravel as Backend and  reactjs with nextjs  as front end School Timetable Calendar

Project showing how to use roles-permissions (students, teachers, admins)
#Features
- 3 types of users: Admins, Teachers and Students. Users should have a first and last name,
type and students should have a grade. (Add more attributes as you see fit)
- Authentication: Users should be able to authenticate and based on the type, perform different
actions on the application.
- Admins should be able to create, read all, update, and delete lessons on the calendar.
- Teachers should be able to read only their lessons and take attendance.
- Students should be able to read only their lessons.
- Calendar view: Users should be able to view lessons on a monthly, weekly, and daily basis.
(Use a library of choice of the front-end)
- A lesson: A lesson may have 1 or more students, one teacher and a limited duration. 
- Search and filter: Users are be able to search for lessons by title and filter by date range,
student or teacher. 

## How to use

- Clone the repository with __git clone__
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- That's it: launch the main URL. 
- Admin's credentials: __admin@admin.com__ - __password__
- Teacher's credentials: __teacher@teacher.com__ - __password__
- Student's credentials: __student@student.com__ - __password__
