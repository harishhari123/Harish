# SwatchBharath

Project Solution Document

1) Registering the user 
 
    User wil be asked to Signup or Login.
    
  User will be register with the following information:

   Name
   Mobile Number
   Email Address
   
Once user is registered , the date will be stored in a Jason file for further tracking.

We display a message “Registered successfully.”
 
If user tries to login before signup, then he will be asked to sign up first.

User can login , if he is already registered.

If he fails to login, then he will be asked to check name, email and password and try again.

If he fails to Login in three attempts, then he will not be given any other chance to login.
    
 If he logged in succesfully then display a message “Logged in successfully.”
 
2) Garbage Collection:

  Once user logged in , ask user “Do you want to submit wastage”
  If user says NO .. then logout from the application. 
  If user says Yes The following message will be displayed

What kind of Wastage do you want to submit:
    Plastic
    Metal
    Glass
  User has to provide one of the option
  
  What is the brand 
    Coke
    Pepsi
    Sprite
    Other

        Assign weight based on the wastage and brand.

  Display a message “Do you want to submit another wastage”

  If user says  Yes , repeat the above steps again, if user says “NO” 

    Display message “do you want to generate a report” 
 

3) Report Generation:

we have to calculate the rewards points, based on the weight and generate the report with the following information.

           selected brand, wastage and reward points which user earned.
           
--Pull request created on develop branch to merge the changes into master branch

