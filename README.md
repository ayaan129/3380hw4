# Cell Company Web App

Our project is a web app for a database of a phone company that tracks the specifics of basic phone plans in the company's perspective. Data usage, bills, etc. 

### ER Diagram

![ER Model](CellCompanyERD.jpg)

### Schema

~~~
-- Phone Plan Table
CREATE TABLE phone_plan (
    phone_plan_id INT PRIMARY KEY,
    plan_type VARCHAR(50) NOT NULL,
    monthly_charge DECIMAL(10, 2) NOT NULL,
    data_limit INT NOT NULL
);
~~~
This phone plan relation creates the table holding values for the customer's phone plan ID, the specific phone plan, their monthly charge, and their data limit.


