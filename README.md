## Acceptance criteria
GIVEN a command-line application that accepts user input
WHEN I start the application
THEN I am presented with the following options: view all departments, view all roles, view all employees, add a department, add a role, add an employee, and update an employee role
WHEN I choose to view all departments
THEN I am presented with a formatted table showing department names and department ids
WHEN I choose to view all roles
THEN I am presented with the job title, role id, the department that role belongs to, and the salary for that role
WHEN I choose to view all employees
THEN I am presented with a formatted table showing employee data, including employee ids, first names, last names, job titles, departments, salaries, and managers that the employees report to
WHEN I choose to add a department
THEN I am prompted to enter the name of the department and that department is added to the database
WHEN I choose to add a role
THEN I am prompted to enter the name, salary, and department for the role and that role is added to the database
WHEN I choose to add an employee
THEN I am prompted to enter the employee’s first name, last name, role, and manager, and that employee is added to the database
WHEN I choose to update an employee role
THEN I am prompted to select an employee to update and their new role and this information is updated in the database

## Packages used 
npm i inquirer@8.2.4
npm i mysql2
npm i cfonts


## Source codes 
https://www.youtube.com/watch?v=4KXLY5Sf2fU&t=407shttps://www.youtube.com/watch?v=4KXLY5Sf2fU&t=407s
https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-FSF-PT-09-2023-U-LOLC/-/blob/main/12-SQL/01-Activities/05-Ins_Tables/db/schema.sql?ref_type=heads
https://sidorares.github.io/node-mysql2/docs#first-query
https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-FSF-PT-09-2023-U-LOLC/-/blob/main/12-SQL/01-Activities/28-Stu_Mini-Project/Main/server.js?ref_type=heads
https://git.bootcampcontent.com/University-of-Texas-at-Austin/UTA-VIRT-FSF-PT-09-2023-U-LOLC/-/tree/main/12-SQL/01-Activities/18-Stu_Seeds?ref_type=heads
https://www.npmjs.com/package/cfonts
https://stackoverflow.com/questions/74486644/how-can-i-get-the-result-of-a-query-method-with-mysql-in-nodejs


## Walk through video
https://drive.google.com/file/d/1BhhwoQAwBihXTfwGwM4qqxtTMgWHHBD_/view