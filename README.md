# Traffic Violation Database

This repository contains SQL queries and views for analyzing traffic violation data. The database consists of several tables including `persondetails`, `policedetails`, `vehicledetails`, and `violationdetails`. 
The queries provided here aim to extract insights and statistics from this dataset.

## Queries

### Query 1: Adding Foreign Keys
This query adds foreign keys to the `persondetails` table to establish a relationship with the `vehicledetails` table.

### Query 2: Splitting Date Components
This query splits the composite key `dateofstop` into separate date, month, and year components.

### Query 3: Count Violations by Month
Counts the number of violations that occurred in each month.

### Query 4: Age Analysis of Accident Involvement
Determines the number of people of a certain age involved in accidents without alcohol consumption.

### Query 5: Creating a View for Belt Violations
Creates a view `belts_violations` to filter violations related to not wearing seat belts.

### Query 6: Number of Violations per City
Counts the number of violations per city in descending order.

### Query 7: Number of Males Caught in Violations
Orders males caught in violations by age.

### Query 8: Total Males of Each Age in Violations
Counts the total number of males of a particular age involved in violations.

### Query 9: Creating a View for Property Damage Violations
Creates a view `view2` for violations where property is damaged.

### Query 10: Number of Violations Handled by Each Police
Counts the number of violations handled by each police officer.

### Query 11: Vehicles of White Color Ordered by Year
Finds vehicles of white color ordered by year.

### Query 12: Violations Made Between 25 and 31 Grouped by Year
Groups violations made between 25 and 31 of each month and orders them by year.

## Additional Queries and Operations
- Additional operations such as joining tables and creating views for further analysis.
- Some commented-out queries and operations for reference.

## How to Use
1. Run each query in a SQL environment connected to the database.
2. Ensure the database schema matches the table structure mentioned in the queries.
3. Analyze the results to gain insights into traffic violations.

## Contributors
- [List of contributors or team members who worked on the queries]

## License
This project is licensed under [License Name] - see the [LICENSE.md](LICENSE.md) file for details.
