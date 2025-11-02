# NoSql_project
MongoDB University Database Queries: Features and Functions 🛠️
This project contains 14 MongoDB queries executed on a mock university schema. It is designed to showcase mastery of the MongoDB query language, focusing on Aggregation Pipeline techniques, efficient data retrieval, and modification.

Core Functionality Highlights ✨
Advanced Data Retrieval (Read):
$$$lookup Joins: Demonstrates complex multi-collection joins for detailed reporting, such as listing students and their course titles (Q3) or calculating faculty-specific student averages (Q13).
Array Matching: Utilizes operators like $$$all (Q1) and combines $$$addToSet with $$$all (Q11) to filter documents based on the presence of multiple, specific array elements.

Data Aggregation and Reporting (Functions):
Ranking & Limiting: Uses $$$group, $$$sort, and $$$limit to find Top 3 students by average mark (Q5) and the most popular activity type (Q14).
Calculated Fields: Employs $$$project with array operators like $$$size to filter based on calculated values, such as faculty teaching more than two courses (Q2).

Data Modification (CRUD):
Atomic Updates: Features updateMany for bulk updates (Q7) and implements the crucial upsert pattern (Q9) to atomically update or insert a course record.

Prerequisites 📋
MongoDB installed with mongosh access. The following collections must be populated with data: students, faculty, enrollments, courses, and activities.
