# Backend_Projects_using_Django
Backend Web Development Project using python framework Django 2.0 
***
# List of Projects:

*  Forms :taking Input from User
*  Static Blog
*  CRUD Blog- Create, Read, Update and Delete
*  Authentication -login and logout
*  To-Do-List
*  Interaction with Databases
*  Templating

***

# Forms: taking Input from user
 A Video request page in which user has to fill the form `/videorequest/vrform` containing name and Content of video. That filled information is displayed on Video request page `/videorequest` and gets updated in the database.

[See the Project](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/tree/master/05Forms "Forms")


The empty form will look like this:<br>

![Form](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/05Forms/form.png "Form")

After filling the form and pressing `submit` button:

![filled](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/05Forms/filled.png "filled")

The filled information is displayed on the Video Request Page:<br>
![Added](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/05Forms/added.png "Added")

if you click on `Enter your video request` button, you will be redirected to `/videorequest/vrform/` .

***

# Static Blog
Personalised Blog Website of Static pages using Backend and interaction with databases as well.

[See the Project](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/tree/master/04StaticBlog "Static Blog")

![Home](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/04StaticBlog/home.png "Home")

![blog](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/04StaticBlog/frontEnd.png "blog")

***

# CRUD Blog- Create, Read, Update and Delete
in the above project we added the functionality of CRUD- Create, Read, Update and Delete using databases and forms.

[CRUD](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/tree/master/06CRUD-Blog "CRUD Blog")


To Add the Blog click on `Save` button:<br>

![Add](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/06CRUD-Blog/save.png "Add")

![Added](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/06CRUD-Blog/added.png "Added")

The blog is added on the home page.

To Update the Blog information click on `Update` button:

![Update](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/06CRUD-Blog/edit.png "Update")

To Delete the Blog:

![Delete](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/06CRUD-Blog/delete.png "Delete")

click on `confirm` button

***

# Authentication- Login and Logout
Adding the Authentication like login, logout, signup and Contect restrictions facility in the above Blog Application.

To Create the new Account:<br>
Navigate upto project directory and type following commands in terminal
```cmd
/python manage.py makemigrations website

/python manage.py migrate articles 

/python manage.py createsuperuser

username:
password:

Enter the username and pasword to create your new account.

superuser successfully created!

```
[See the Project](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/tree/master/08Authentication "Authentication")

To login into your account and access the content click on `login` and fill the information username and password:

![Login](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/08Authentication/login.png "Login")

After clicking on `Login Me` button, `You are logged in ` message is shown at top.
Now you can access the content.

![Loggedin](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/08Authentication/loggedIn.png "Loggedin")

Click on `Logout` to logout from your account.

![Loggedout](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/08Authentication/loggedOut.png "Loggedout")

***

# To-Do-List
A to-Do Web Application using Backend that lets user add tasks, Mark them Done and Delete them. 

[See the Project](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/tree/master/07To-Do-List "TODO")


To Add the Task, click on `Do it` button.

![Add](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/07To-Do-List/add.png "Add")

The task is added in the list sucessfully.

![Added](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/07To-Do-List/added.png "Added")

Checkmark the Done Tasks:

![Done](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/07To-Do-List/done.png "Done")

Detete the Task:

![Delete](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/07To-Do-List/deleted.png "Delete")

The Tasks are Deleted sucessfully.

***

# Interaction with Databases
 Fetching the Commands and their meaning from Database.<br>
 Database queries are written in [models.py](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/03Databases/commandr/cmdr/models.py "models")

[See the Project](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/tree/master/03Databases "Databases")

![Commands](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/03Databases/commands.png "Commands")

***

# Templating
**Templating**: Breaking the webpage into smaller parts. <br>
Designed a simple 'home' ,'About Us' and 'Contact Us' page  using Backend. Navigate between them using navigation bar.

[See the Project](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/tree/master/02Templating "Templating")

![Home](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/02Templating/home.png "Home")

![About Us](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/02Templating/AboutUs.png "About Us")

![Contact Us](https://github.com/IamVaibhavsar/Backend_Projects_using_Django/blob/master/02Templating/ContactUs.png "Contact Us")

***
# Thank You!





