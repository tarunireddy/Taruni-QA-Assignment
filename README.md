# Taruni-QA-Assignment
Taruni Reddy Sarikonda

QA Assignment(week-2)


1.) Gmail compose functionality:

User must log into the website with valid id and password and should be able to Send mail with/without cc, bcc address, subject, message. Once sent, user must receive a notification saying email was sent and a popup should appear when no email id or no subject is entered.

BDD Acceptance criteria:
Given Gmail Login details
When Compose Gmail is selected
And user enters the cc, bcc address, subject and message
And selects an option to send
Then user’s email is successfully sent.

2.) Transfer amount from one account to other account 

User must Login with valid user id and password and select the transfer option either from savings/checking account and selects the recipient name or email or telephone number you are sending to. Enter the amount and then select the date you wish to transfer and click transfer.

Can’t transfer negative amount or insufficient funds, from a blocked account

BDD Acceptance criteria:
Given User logins a Banking website
When selects transfer option from savings/checking account
And enters recipient name or email or phone number
And enters the amount along with the date 
And selects transfer option
Then the user will successfully transfer the amount.


3.) Shopping cart functionality from amazon.com:

When User logs into amazon, user should be able to select multiple items and add to cart then should be able to add discounts or coupons at the time of payment in shopping cart then the total price including shipping charges and taxes are calculated. An automatic email with an order number should be sent once the payment is made and confirmed.


The user would not be able to submit a form if all the mandatory fields are not entered.

BDD Acceptance criteria:
Given amazon website
When user selects multiple items
And selects add to cart
Then products are added to cart
And after adding discounts or coupons the total price is calculated along with shipping charges and taxes.
Then after payment an email with an order number is sent.

4.) Adding dependent to existing health insurance:

User should log into desired portal, select an option to add a dependent in the home page to the plan you choose and provide the dependent personal details and click on enroll.

BDD Acceptance criteria:
Given user logins a desired portal
When user selects an option to add a dependent
And provides dependent personal details 
And chooses a plan
And clicks on enroll
Then the dependent is added successfully.


5.) Remove service from mobile plan:

When user logins a respective mobile website, from menu select a plan you are in and click on an option to remove a service. Select agree to discontinue a service. 

BDD Acceptance criteria:
Given user logins to desired Mobile website
When chooses current plan
And selects option to remove a service from menu
And selects to deactivate the plan
And clicks on agree
Then the service is removed from a mobile plan.


6.) Enrolling student into course:

 To enroll a student, check whether student’s GPA & Test Requirements are met and submit the Application as well as Admission documents and pay the necessary tuition fee then a student will be enrolled.

BDD Acceptance criteria:
Given student’s GPA and test requirements are met
When student fills all the application forms
And completes the admission documents
And pays tuition fee
Then a student will be enrolled.

7.) Checking if Gmail is showing proper emails or not

When user logins the Gmail and opens inbox, check if any mail has invalid email id or the received date and time according to the time zone does not match.

BDD Acceptance criteria:
Given Gmail user id and password
When user logins 
And if any mails have invalid email
And if date and time does not match the current time zone
Then Gmail shows improper emails.




   
