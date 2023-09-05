# BankLoanManagementSystem
Database will include details of customers such as Customer Id (Primary Key),
Name, Account Number, Date of Birth, Email-ID, Address, Home Branch and
Balance. These all are attributes of Customer Entity Set.
Other Entity Set will be of Complaint which will have the following attributes:
Customer ID (Foreign Key)
Current Status
Type of complaint
(Discriminator)No of days
Complaint and Customer Table will have complaint lodge relation between them.
The next Entity set is of Loan Details which have Loan No (Discriminator),
LoanDate, Amount, Customer ID(Foreign Key) as attributes.
Customer and Loan Table will be having borrow relation between them.
No of days since the complaint has been lodged is considered as an attribute of
relation between Complaint and Customer.
If the complaint is not resolved in 15 days, then it will be redirected to higher
authority, Manager in our case. Manager have Name, Manager ID (Primary
Key)Phone Number, Customer ID(Foreign Key) as attributes.
Loan Table and Complaint Table will have Total Participation.

  
<img width="789" alt="Screenshot 2023-09-05 at 10 30 06 PM" src="https://github.com/meharr02/BankLoanManagementSystem/assets/138808971/0b36bbd4-66b1-49ff-bf82-787cdffd2868">
