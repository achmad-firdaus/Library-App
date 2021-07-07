# Library-App
Welcome documentation for library app

![image](https://user-images.githubusercontent.com/77251566/124684403-40c7f000-def9-11eb-99d1-f8a8e2d0399f.png)


Menu List and Role user access

|Dashboard    -> Access: All Role (Admin-Staff(Officer)-Member) <br/>
|<br/>
|Master <br/>
|--Members    -> Access: All Role (Admin-Staff(Officer)-Member) <br/>
|----Add      -> Access: Role (Admin-Staff(Officer)) <br/>
|----View     -> Access: All Role (Admin-Staff(Officer)-Member) <br/>
|----Edit     -> Access: Role (Admin-Staff(Officer)) <br/>
|----Delete   -> Access: Role (Admin-Staff(Officer)) <br/>
|----Enable/Disable     -> Access: Role (Admin-Staff(Officer)) <br/>
|-Officer     -> Access: All Role (Admin-Staff(Officer)-Member) <br/>
|----Add      -> Access: Role (Admin-Staff(Officer)) <br/>
|----View     -> Access: All Role (Admin-Staff(Officer)-Member) <br/>
|----Edit     -> Access: Role (Admin-Staff(Officer)) <br/>
|----Delete   -> Access: Role (Admin-Staff(Officer)) <br/>
|----Enable/Disable     -> Access: Role (Admin-Staff(Officer)) <br/>
|-Books       -> Access: All Role (Admin-Staff(Officer)-Member) <br/>
|----Add      -> Access: Role (Admin-Staff(Officer)) <br/>
|----View     -> Access: All Role (Admin-Staff(Officer)-Member) <br/>
|----Edit     -> Access: Role (Admin-Staff(Officer)) <br/>
|----Delete   -> Access: Role (Admin-Staff(Officer)) <br/>
|<br/>
|Transaction <br/>
|-Loan        -> Access: Role (Admin-Staff(Officer)) <br/>
|----Transaction Loan      -> Access: Role (Admin-Staff(Officer)) <br/>
|----Today's Loan     -> Access: All Role (Admin-Staff(Officer)) only the creator user can see and the admin can see everything <br/>
|------Edit     -> Access: All Role (Admin-Staff(Officer)) only the creator user can see and the admin can see everything <br/>
|------Delete     -> Access: All Role (Admin-Staff(Officer)) only the creator user can see and the admin can see everything <br/>
|-Return      -> Access: Role (Admin-Staff(Officer)) <br/>
|----Transaction Return      -> Access: Role (Admin-Staff(Officer)) <br/>
|<br/>
|Report <br/>
|-Loan        -> Access: Role (Admin-Staff(Officer)) <br/>
|----Loan Report      -> Access: Role (Admin-Staff(Officer)) <br/>
|-Returned    -> Access: Role (Admin-Staff(Officer)) <br/>
|----Returned Report      -> Access: Role (Admin-Staff(Officer)) <br/>
|<br/>
|Setting <br/>
|-Setting      -> Access: All Role (Admin-Staff(Officer)-Member) <br/>
|----Setting Profile Library      -> Access: Role (Admin-Staff(Officer)) <br/>
|----Setting Penalty      -> Access: Role (Admin) <br/>
|----Change Password      -> Access: All Role (Admin-Staff(Officer)-Member) <br/>



Structure Databse, this only pk and index unique iam not use pk

![image](https://user-images.githubusercontent.com/77251566/124686783-e67d5e00-defd-11eb-858f-785989e17f85.png)


How Login ? </br>
Default User login :</br>
User: Admin1A0014 </br>
Password: Admin1A0014TS </br>
User: Officer1A0018 </br>
Password: Officer1A0018TS </br>
User: Member1M0012 </br>
Password: Member1M0012TS </br>
NOTE: Password default in application (username + TS) if username Member1M0012 and your password Member1M0012TS </br>
Link Demo: https://thirtyseven-v1.herokuapp.com/Officer
