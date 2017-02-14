TODO

## sub Features:

User authentication \(login & log out\)

problem define:

**one LoginView, two form submitted will callbacks the same post methods\(how to use two urls for two forms in one view\)**

Email registeration

two solution

**allauth **

```
{% load socialaccount %}
{% providers_media_js %}
<a href="{% provider_login_url "facebook" method="js_sdk" %}" >Facebook</a>
```

when class attribute is added for the link

```
class="fb-login-button" 
```

page does not redirect to expected

the href is overriden



**solution**:

use the allauth tag

then style the facebook link manually

