# FirstChapter

Now there register form has been written in python file
it would be rendered by url.py within the login.html template.

A user is now able to register their username,password and email to the database



## problem solved:

**'is\_invalid' always false**

{{form.as\_p}} show there a son why input is not valid

**How does the 'fields' in inner class work?**

The generated`Form`class will have a form field for every model field specified,

in the order specified in the`fields`attribute.

**pass word widget is not hiding the password**

manually writing passwords fields in the form classes

**password store and management**

[https://docs.djangoproject.com/en/1.10/topics/forms/modelforms/](https://docs.djangoproject.com/en/1.10/topics/auth/passwords/#how-django-stores-passwords)

**un-hashed password solved**

write save\(\) after set\_password\(\)





