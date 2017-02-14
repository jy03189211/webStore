TODO

## sub Features:

User authentication \(login & log out\)

problem define:

**one LoginView, two form submitted will callbacks the same post methods\(how to use two urls for two forms in one view\)**

Email registeration



two solution

allauth

```
{% load socialaccount %}
{% providers_media_js %}
<a href="{% provider_login_url "facebook" method="js_sdk" %}" >Facebook</a>
```



