...

## HTML email sample using BeYou assets

Image below is a screen grab of the email rendered inside of the outlook.com email client.

Email was put together by first using [Stripo](https://stripo.email/) to generate a basic grid layout and then add images so they can be served by their own CDN. The advantage of Stripo is it allows you to look past the provided the GUI and instead edit the html directly.

Once the basics were in place, the .html and .css files were copied into [postdrop](https://app.postdrop.io/) for further editing. Postdrop is a small but incredibly useful html email app that allows you to edit the html & css files and see the results straight away. You can then email yourself a copy of the email to make sure it looks as intended (because it never does...)

To see for yourself how the attached files render the final html email, visit [postdrop.io](https://app.postdrop.io/editor) and paste them into the html & css windows and you get an immediate result - no sign up required.

As seems to be the case with most forwarded html emails, they don't tend to preserve very well so the below screenshot and the postdrop app are the best ways of seeing how this email would look when it first lands inside an inbox, before the email clients get a proper chance to mess things up.

Final note - because stripo rendered the initial template html & css, there are a lot of unused css and html references. As this is only meant to be quick a test, just to let me have a play and get my head around html emails, they have been left in but can, and should, be removed at some point.

<img src="assets/html_email_d.jpg">
