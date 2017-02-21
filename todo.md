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

**third party provided link override and redirect **

for **override**: write the link before:

`url(r'^accounts/', include('allauth.urls')),`

for **redirect**:

`from django.views.generic.base import RedirectView`

`url(r'^accounts/social/login/cancelled/$', RedirectView.as_view(pattern_name='login', permanent=False), name='facebook_login_cancel'),`

it works for both class based view and function based view



Task:

**share game score with third party api**

**Q**:how to get the score of the game from other website ?

