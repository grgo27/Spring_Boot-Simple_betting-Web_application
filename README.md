This is a simple betting application with PostgreSQL as the database.
Upon running the application, the database is automatically populated with games.
Users can register and log in. Upon successful registration, the user receives 5 credits in their account. 
Users can modify their accounts, as well as add and remove money from them. 
Only logged-in users can place bets. 
When a bet is placed, it is assigned the NOT_FINISHED status. 
In the main controller, under the specific_date variable, users can set a date. 
After that date, the status of the bet is randomly changed to WINNING or LOSING, and the user's balance is adjusted accordingly.
Additionally, games available for betting until that date are automatically removed after that date.

Unit testing for service layers is implemented.

It's crucial to note that users must adjust password in application.properties according to their specific setup.

