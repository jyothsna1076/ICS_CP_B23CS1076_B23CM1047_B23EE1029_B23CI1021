# ICS_CP_b23cm1047_cs1076_ee1029_ci1021
ic_project
ic project description:



 This is our project for ATM.


 Firstly, it asks account number of the user

 
 If the account number is not present, It asks the user "Do you want to create a new account? 1.YES 2.NO"
 a) If the user gives input as 1, it asks the user to enter the account number and then password. It askes the user to enetr the pin number again for 
 confirmation.
 If the enetred pin number is correct, the user is asked to enter his/her account holder name. The output is given as "ACCOUNT CREATED THANK YOU VISIT 
 AGAIN" and then the code terminates.
 If the entered pin number is not matching with previously given pin number, it gives output as "The password you have enetred before and now are not 
 matching TRY AGAIN" and then the code terminates.
 b) If the user gives input as 2, It gives the output as "THANK YOU VISIT AGAIN" and then the code terminates.

 
 If the account is already present, it asks to enter the pin number.
 If the pin number that the user have given is incorrect, it gives output as "INCORRECT PASSWORD TRY AGAIN"
 If the pin number that the user have given is correct, it displays the options 5 options namely
 1)check balance
 2)cash withdrawl
 3)cash deposit
 4)change pin number
 5)transfer fund

 
 User have to select one of the options.

 
 When user gives input as 1, check balance option is selected. Then the current balance of the account present is given as output and
 then the code terminates.

 
 When user gives input as 2, cash withdrawl option is selected. The code asks the amount that the user wants to withdraw,
 if the user gives input amount more than his/her balance, it shows "INSUFFICIENT BALANCE" and the code terminates.
 if the input amount is within the balance, it gives output as "Amount withdrawn successfully" and the updated current balance of that account is shown 
 after transaction and the code terminates.

 
 When user gives input as 3, cash deposit option is selected. The code asks the amount that the user wants to deposit,
 User have to give the input amount that is to be deposited. Then the output is given as "Amount deposited successfully" and the updated current balance of 
 that account is shown after transaction and the code terminates.

 
 When user gives input as 4, change pin number option is selected. It asks the user to enter the pin number once again for more authentication. If the given 
 pin number matches with the correct current pin no, it asks to enter new pin no. Then the user is supposed to enter new pin number. The user is again asked 
 to enter the new pin number for security reasons. 
 a)Once the entered pin number matches with the previously given new pin number output is given as "PIN NUMBER CHANGED SUCCESSFULLY" and the code terminates
 b)If the entered pin number does not match with the previously given new pin number output is given as "The pin numbers you entered are not the same CHECK 
 AGAIN THANK YOU" and the code terminates


 When user gives input as 5, transfer fund option is selected. It askes to enter the pin number again for more authentication
 a) If the enetred pin no. is correct, it asks to enter the account number to which the user wants to transfer money. 
 b) If the enetred pin no. is incorrect, It shows "INCORRECT PIN NO TRY AGAIN" and then the code terminates
