# foodmart-for-mysql
The DDL statements for the famous example database "foodmart".

## Usage
1. You can create the database in MySQL using the DDL(foodmart schema.sql) provided in this project.
2. Then get the derby edition of foodmart from the project like Pivot4J.(Download the war file from http://www.pivot4j.org/download.html, then unzip it and you will find the derby foodmart in WEB-INF folder)
3. Finally, use kettle and account.ktr to load data from derby foodmart to mysql foodmart.
