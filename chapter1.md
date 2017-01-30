# First Chapter

Now the register form has been written in python file

it would be rendered by url.py within the login.html template.

A user is now able to register their username, password and email to the database









problem defined:

**The 'is\_valid\(\)' always false has been solved.**

use{{form.as\_p}} would tell the reason of invalidation below the field

**How does the 'fields' in inner class work?**

The generated`Form`class will have a form field for every model field specified,

in the order specified in the `fields`attribute.

**password widget is not hiding the password**

manually writing passwords fields in the form classes

**password store and management**

[ https://docs.djangoproject.com/en/1.10/topics/forms/modelforms/](https://docs.djangoproject.com/en/1.10/topics/auth/passwords/#how-django-stores-passwords)

Should I write the password field in the user model or not, how it works

