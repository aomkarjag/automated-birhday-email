Clone the project using the following command 
  git clone "https://github.com/aomkarjag/automated-birhday-email.git"

Install all dependencies using the "npm install" command

This project typically uses the @sendgrid/mail library to send email to all the added recipients 
On order to setup this feature one needs to verify their email in sendgrid and then add that email in the from key.

Then you can use the UI to enter the recipient's email and date of birth. 
At sharp 12:00 am an email will be sent to the intended recipients. You can add multiple recipients at once.
