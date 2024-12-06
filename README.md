# Impledge_QA_Loveleen_Batra
# Overview
This program is designed to address specific business requirements using SQL to manipulate and analyze relational data. The queries were developed to ensure clarity, accuracy, and efficiency in retrieving the required information while adhering to best practices in database management. The program demonstrates the ability to process and validate data while addressing real-world use cases effectively.

It Includes 3 queries
# Design Decisions
        *Modularity: Queries were structured into logical steps to ensure readability and facilitate debugging. Subqueries and Common Table Expressions (CTEs) were used where necessary to break down complex operations into simpler, reusable parts.
        *Performance Optimization: Care was taken to write efficient queries by:
              --Utilizing appropriate indexing strategies.
              --Filtering data early in the query execution process to minimize processing overhead.
              --Avoiding unnecessary joins or nested subqueries.
        *Scalability and Flexibility: Queries were designed to work across diverse datasets, using dynamic filtering and generic column references where applicable.
# Approach
  ### Understanding Requirements: Each query was built to address specific use cases (e.g., filtering data, aggregating results, or joining multiple tables). The focus was on clearly defining the expected outcomes before starting the implementation.
  ### Validation of Results: The queries were tested with a sample dataset to ensure correctness. Edge cases were also considered to validate handling of null values, duplicates, and outliers.
  ### Use of SQL Best Practices:
        **Joins and Relationships: Proper join types (INNER, LEFT, RIGHT) were used to maintain data integrity and relevance.
        **Aggregations and Grouping: Functions like COUNT, SUM, and AVG were leveraged efficiently for summarizing data.
        **Comments and Documentation: Inline comments were added to make the SQL scripts easier to understand and maintain.
# Output 
        • SELECT the details of Doctors(s) who has got Admissions.
        • SELECT the details of Doctors(s) for whom there is no Admissions.
        • SELECT the details of Patients(s) whose Admission can’t be completed due to missing doctor details
