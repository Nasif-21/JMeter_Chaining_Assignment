# API Chaining using JMeter 
## Summary:
In this project, deposit, withdraw, and send money APIs of a fintech application are executed using JMeter to demonstrate API chaining, where multiple requests are run sequentially to validate end-to-end functionality.

## Description:
**Dmoney** is a fintech application that allows customers to deposit, withdraw, send money, and make payments. Agents can deposit money and pay merchants, while merchants receive payments from customers.  
This project focuses on building an API chaining workflow for **deposit, withdraw, and send money**, using test data stored in a CSV file.


## Technical Requirement
+ Apache JMeter
+ JSON formatting
+ Control statement
+ API request

## Running API chaining in JMeter
+ clone this repo
+ Open dmoney.jmx using Apache Jmeter
+ Under a test plan, there are different thread for deposit, withdraw and send money
+ To see each test is successful, open the View result tree

## Generate the JMeter report
+ Go to the file where ``dmoney.jmx`` file is stored.
+ Open command line
+ Write this command : ```jmeter -n -t .\booking.jmx -l .\booking.jtl -e -o Reports```
+ An report folder, jmeter log and jtl file will be created
+ Under report folder, there is an html file name index, open to view the reports

## Attachment
### Screenshot of JMeter Dashboard
<img width="1913" height="881" alt="image" src="https://github.com/user-attachments/assets/b83a3a27-6a21-4494-9463-6f540690ed0a" />
