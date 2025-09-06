# Assignment on Jmeter chaining in dmoney portal
</hr>
**URL:** [https://dmoney.roadtocareer.net/]

## Description:
</hr>
From the dmoney API collection, create another JMeter collection (dmoney.jmx) for the following scenario: </br>
1. Deposit: 5 agents perform deposits for 10 customers. </br>
2. Send Money: 5 customers send money to another 10 customers. </br>
3. Payment: 5 customers make payments to 2 merchants. </br>

Note: Log in as an admin once and generate a token to use for each of the threads. Create 3 threads under test plan for each type of transaction and set up agent, customer, and merchant accounts in 3 different CSV files (e.g., deposit.csv, sendMoney.csv and payment.csv). The amount must be dynamic using the Random Variable Controller. Use small amounts so that balance can't become empty. Each thread should have a ramp-up time of 120 seconds. Must add assertion to ensure that all transactions are successful.

## Pre-requisites
1. Install **JDK (LTS version)**
2. Install **APACHE Jmeter**
3. Set up **JAVA_HOME** and **JMETER_HOME** environment variables 

## To run this project
1. Clone this project
2. Set up the prerequisites for jmeter
3. Open dmoney.jmx in Jmeter
4. Update the address of the CSV files accordingly
5. Run the test plan to see the output in the summary table and html report

## HTML REPORT
</hr>
Below is a sample execution report </br>
<img width="1102" height="1081" alt="screencapture-file-C-Program-Files-apache-jmeter-5-6-3-bin-b16-DmoneyReports-index-html-2025-09-06-15_57_35" src="https://github.com/user-attachments/assets/fe7df29c-8342-42b0-a6a4-8d881deeb302" />

