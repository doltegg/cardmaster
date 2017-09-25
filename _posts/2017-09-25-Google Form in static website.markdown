---
layout: post
title:  "Elements"
categories: jekyll update
img: image-4.png
---
Google Form Customization for Static Websites! Google Form customization is done to remove the branding that is present at the end of Google Forms. This way we can have our own style for a form. We can also use these forms on static websites!

Customizing Google Forms is important for someone who trusts Google but doesn’t like their branding at the bottom of the forms. Google offers two ways of using their form. One is embedding the form on our website and the second one is redirecting users to the form page.

Create a Google form Customize Google Form Create a similar form Change Action and Name values Multiple Choice, Options, selects radio inputs Publish it on any website Get responses in a Google SpreadSheet Google Form Redirection Google Form Notification Check if the Google Form is working Improvements like File Uploads Conclusion Both the methods are not that great because you have to choose the template Google provides you and you have to bear the Google branding at the bottom.

Customize Google Forms

This is what I’m talking about. Many of us may not bother about the branding. A real headache is when you embed the form on your website, it may display its own scrollbar and may look totally different from your website’s color scheme.

One of my clients asked me whether it is possible to insert google form in their contact page without the google branding on it. I said it isn’t possible. At that time I did not know that we can not only hide the branding, we can completely transform the Google form.

Create a Google form

Go to Google Forms and create a form with values Name and Email. I’m keeping it simple for this tutorial. The next part is to customize Google form.

Customize Google Forms

Customize Google Form

We are going to scrape this Google form for certain values and implement it in our own form. So the first step is to create a form.

You can have any field in the contact form but I will be using only name and email. Once you create the form, click on Send and it will show you how you can implement the form.

Get the form link and open it in a new tab. It is easier if you’re using a Chrome browser. Now, inspect(f12) each and every field in the form and find name attribute. Copy whatever the value present in it. It will be like entry.742532386.

Find <form> tag and copy the URL found in action attribute.

Customize Google Forms

Create a similar form

Create your own barebone form with the same fields as in the Google form. For this example, a sample form will look like this.

Name  
 Email  
  Send
Change Action and Name values

Now in your barebone form, change the action to whatever the action you find in the Google form inspection. It will look something like this https://docs.google.com/forms/d/e/1FAIpQLSdqGYth5-G2cP8SILJwjOcJ38vit-Rv8E9SXmtnJUu4ifMcGw/formResponse.

Copy this value and paste it in your form’s action. Also, copy respective name values and put it in appropriate fields. The completed form should look like this.

Name  
 Email  
  Send
Multiple Choice, Options, selects radio inputs

For form elements like options and select, the google form will have a hidden 
 tag at the end of the form. Sometimes you will have to select an option in the form to see that hidden 
 tag. Copy the name value from that tag to all the options and selects.

Publish it on any website

The good thing about the form is that it not only works but it works on static websites as well. This is a great way to insert Google forms in Jekyll websites and blogs hosted on Github Pages.

Try not to spam.

Here is a working form that you can check. I have restricted the entries to 18 characters so as to avoid long spams.

Name John Doe

Email john@email.com

Send Style this form however you want to but I’m keeping it simple without any styles applied. You can check the entries here.

Get responses in a Google SpreadSheet

This is a cool feature where you can get the entries in a spreadsheet! In the form, click on Responses tab. You should be able to see all the responses right there. But you will see a spreadsheet icon at the top right corner. Click on it and it will ask you whether you’d like to save responses in a new spreadsheet. Click Create

Customize Google Forms

Once you create it, you should see a spreadsheet created with tabs for Name and Email.

Customize Google Forms

Google Form Redirection

After form submission, you will be redirected to a Google page where it says response is received. You can edit the message and provide a link back to the website. This custom message and link will be shown to the users after they submit the form.

Customize Google Forms

But if you don’t want it to be redirected back to your page, then please use this code instead.

Name  
Name
 
Email  
Email
 
Send
Google Form Notification

Another cool feature is to get notifications to your email upon every entry. You can activate this feature in the spreadsheet by going to Tools » Notification Rules…. Set rules on when to receive notifications and you’re good to go.

Change class ``panel-primary`` to ``panel-warning``, ``panel-success`` and so on to get other panels.
