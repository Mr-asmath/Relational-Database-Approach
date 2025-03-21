### **README.md**  

# **Database Design and Implementation Using ER Model and Normalization**  

## **Overview**  
This project explores database design by creating an ER model and converting it into a relational schema. It involves entity identification, relational mapping, normalization (1NF), and various SQL join operations to ensure data consistency and integrity. The study aims to enhance database efficiency by eliminating redundancy and enforcing constraints through proper relationships and attribute management.  

## **Key Components**  
1. **Entity-Relationship (ER) Model**  
   - Strong Entities: Student, Course, Professor, Department  
   - Weak Entity: Enrollment (dependent on Student and Course)  
   - Relationships: 1:1 (Student & Department), 1:N (Student & Enrollment, Professor & Course, Department & Professor), N:M (Student & Course)  
   - Attributes: Primary Keys, Multi-valued, Derived Attributes  

2. **Relational Mapping**  
   - Conversion of ER Model to Relational Schema  
   - Tables: Student, Course, Professor, Department, Enrollment, Student_Phone, Professor_Phone  

3. **Normalization (1NF)**  
   - Multi-valued attributes (Phone Numbers) are removed into separate tables  
   - Ensures atomicity and avoids redundancy  

4. **SQL Query Implementation**  
   - Table creation with constraints (PK, FK, Unique, CHECK)  
   - Insert sample data  
   - Various Join operations (INNER JOIN, LEFT JOIN, RIGHT JOIN, FULL OUTER JOIN, SELF JOIN, CROSS JOIN)  

## **Implementation Steps**  
1. **Design the ER Model** by identifying entities, attributes, and relationships.  
2. **Perform Relational Mapping** to define schema structure.  
3. **Normalize the Database** by applying 1NF to remove multi-valued attributes.  
4. **Write SQL Queries** to create tables, insert values, and execute joins.  
5. **Test Queries** for data retrieval and relationship verification.  

## **Results**  
- Successfully designed a relational database using ER modeling and normalization principles.  
- Ensured data consistency through constraints and proper relationship mapping.  
- Demonstrated SQL joins to retrieve meaningful insights from the database.  

## **References**  
1. [ER to Relational Mapping - Medium](https://medium.com/@kumarjai2466/er-to-relational-mapping-ac84b3c9f258)  
2. [Normal Forms in DBMS - GeeksforGeeks](https://www.geeksforgeeks.org/normal-forms-in-dbms)  
3. Hingorani, K., Gittens, D., & Edwards, N. (2017). *Reinforcing Database Concepts by Using Entity Relationship Diagrams (ERD) and Normalization Together for Designing Robust Databases*. Issues in Information Systems, 18(1), 148-155.  
4. [Lecture 08: Mapping ER Models to Relational Models - Northeastern University](https://course.ccs.neu.edu/cs3200sp18s3/ssl/lectures/lecture_08_mapping.pdf)  

## **How to Use**  
1. Execute SQL scripts to create the database schema.  
2. Insert sample data into the tables.  
3. Run the provided SQL join queries to analyze relationships.  
4. Modify queries as needed to explore different data insights.  

## **Conclusion**  
This project demonstrates the structured approach to database design, from conceptual modeling to relational implementation. Applying ER modeling, normalization, and SQL queries ensures an optimized, efficient, and well-structured database system.
