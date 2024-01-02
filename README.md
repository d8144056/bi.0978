# biREATE TABLE departments (
  DepartmentId INT PRIMARY KEY,
  DepartmentName VARCHAR(50)
);
CREATE TABLE students (
  DepartmentId INT,
  StudentId INT PRIMARY KEY,
  StudentName VARCHAR(50),
  FOREIGN KEY (DepartmentId) REFERENCES departments(DepartmentId)
);
Given the database schema above, generate valid insert statements include 4 rows for each table..0978
