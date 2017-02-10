TODO


## sub Features:

User authentication \(login & log out\)

class based views provide a generic FormView but for all intents and purposes it is designed to only handle one form. One way to handle multiple forms with same target action url using Django's generic views is to extend the 'TemplateView' as shown below



**problem define:
**
**one LoginView, two form submitted will callbacks the same post methods\(how to use two urls for two forms in one view\)**

solved by give name parameter to the button, when the post is called back, do if judgement to these two buttons.

we decided to use function based view, since button name judgement is a bit hack.

Email registeration


