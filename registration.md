# First Chapter {#first-chapter}

Now the register form has been written in python file

it would be rendered by url.py within the login.html template.

A user is now able to register their username, password and email to the database

The 'is\_valid\(\)' always false has been solved.







## problem solved:

**'is\_invalid' always false**

{{form.as\_p}} will show the reason why input is not valid

**How does the 'fields' in inner class work?**

The generated`Form`class will have a form field for every model field specified,

in the order specified in the`fields`attribute.

**password widget is not hiding the password**

manually writing passwords fields in the form classes

**password store and management**

[https://docs.djangoproject.com/en/1.10/topics/forms/modelforms/](https://docs.djangoproject.com/en/1.10/topics/auth/passwords/#how-django-stores-passwords)



## problem to be solved:

**how to save password\(currently explicitly and not hashed stored in the database\)**

User authentication, login logout



