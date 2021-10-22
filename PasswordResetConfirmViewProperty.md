## PasswordResetConfirmViewProperty

###  post_reset_login
----------------------------
>after the **PostRequestComplete** whether to redirect to the Login Page Or Not 
>Default=False i.e.. not login into the User Model 

### post_reset_login_backend:-
--------------------------------------
>whenever Multiple **AUTHETICATION_BACKEND** there in that time a dotted path provided after **PostRequestComplete** and if *post_reset_login=True* then redirect to that path 

### reset_url_token
--------------------------------
>the urlprefix will be set as the provided value for **reset_url_token** which will appear while rendering **SetPasswordForm**

### token_generator
----------------------
>By default correspond to default_token_generator
This is an instance of  class   **django.contrib.auth.tokens.PasswordResetTokenGenerator**

