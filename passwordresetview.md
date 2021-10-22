## template_name
--------------------------------------------
*default to registration/password_reset_form.html and can be over ridden by the custom defined template_name.*

## email_template_name
-----------------------------------------------------
> default to password_reset_email.html and can override the default template_name	

## subject_template_name
-----------------------------------------------------------
>default subject_template_name refers to password_reset_subject.txt but can be overridden by **PasswordResetView** Class

## html_email_template_name
-------------------------------------------------------------------
>refers to the html_email_template which should be provided for text/html multipart/email inside the form tag 
>By Default these html_email_template_name are not often used

## token_generator
-------------------------------------------------
>By default correspond to default_token_generator
>This is an instance of  class   **django.contrib.auth.tokens.PasswordResetTokenGenerator**

## form_class
---------------------------------------------
>By Default *PasswordresetView* renders **PasswordResetForm** inside the form_class
>if we want we can over Ride the default for i.e. **PasswordResetForm** In order to display Our Form By Default

## success_url
-----------------------------------------
>The URL to redirect to upon successful **PasswordResetForm Submission**
>By default it corresponds to **PasswordResetDoneView** *password_reset_done.html*

## extra_Context
--------------------------------------------
>we can pass extra  context to **PasswordResetForm** template i.e. *password_reset_form.html* as dictionary


## extra_email_context:-
-----------------------------------------------------------
>we can also provide extra Context to email Template i.e. **password_reset_template.html**

## from_email:-
--------------------------------------
>this defaults to settings.py **DEFAULT_FORM_EMAIL**
>we can also provide from the view which inherit the **passwordResetView**