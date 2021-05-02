# -P.I.-Works-Technical-Assignment-Answer

## Definition
This is a user interface specification document for the user management screen for PI Works job application. The screen has two duties which are adding new user data to database and sorting/observing the user list from data base. 

## Screen Parts
- Upper Bar
   - New User Button
   - Hide Disabled User Check Box
   - Save User Button
- User Information List
   - ID Sorting Button
   - User Name Sorting Button
   - Email Sorting Button
   - User Status Sorting Button
   - Display User List
- New User Information Screen
   - Username Text Box
   - Display Name Text Box
   - Phone Text Box
   - Email Text Box
   - User Roles Option Box
   - User Status Check Box
   
## Detailed Explanation
  ### Upper Bar
  -------------
  This bar is on the top of the screen. It has three components. First two component is in the right side of this bar, which are New User Button and Hide Disabled User Check Box. Third one is in the left side  which is Save User Button.
  
  ## New User Button
  -It is a button that first clears the screen and then allows you to enter information about new user.

  ## Hide Disabled User Check Box
  -It is a check box that allows users to choose option to see just enabled user or with disabled user.  

  ## Save User Button
  -This button saves and uploads the user information that written on the screen. 
  
  ### User Information List
  -------------
  This list is on the left half of the screen. It is used for getting and viewing the list from database by wanted sorting options. That list includes in order of ID, User Name, Email and Status. Each list element have a sort button on the name of itself.

  ## ID Sorting Button
   -This button sort the data list by ID. It has two options which are sorting from smaller to bigger and from bigger to smaller according to ID variable is integer.

  ## Email Sorting Button
   -This button sorts data list by Emails. It has two options which are sorting from A to Z and from Z to A  according to Email variable is string.

  ## User Status Sorting Button
   -This button sorts data list by User Status. It has two options which are sorting from enabled to disabled and from disabled to enabled according to User Status variable is boolean which is 1 for enabled and 0 for disabled.

  ## Display User List
   -This user gets data from database and shows by wanted sorting options.


  ### New User Information Screen
  -------------------------------
  This part is on the right side of the screen. It is used for inserting new user data. It includes the input parts for new user which are username text box, display name text box, phone text box, mail text box user role option box and user status check box.

  ## Username Text Box
   -Username information can be written as a string to this box.
 
  ##  Display Name Text Box
   -Display Name information can be written as a string to this box.
 
  ## Phone Text Box
   -Phone Number information can be written as a string to this box.
 
  ## Email Text Box
   -Email information can be written as a string to this box.
 
  ## User Roles Option Box
   -User can determine its role according to three choice which are Guest, Admin, SuperAdmin. 
 
  ## User Status Check Box
   -According to the choice of enabled or not, new user's status can be enabled.
  
  
