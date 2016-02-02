# Application form

## Create a form on Django Girls website

You can create one application form for each Django Girls website. In order to do that, go to [Django Girls Admin -> Applications -> Form](http://djangogirls.org/admin/applications/form/) and click the "Add form" button. You will see a form like that:

![](https://dl.dropboxusercontent.com/u/527278/Screen%20Shot%202015-06-25%20at%202.20.19%20PM.png)

Now you should edit out all the texts. Confirmation mail is what we will automatically send from your city@djangogirls.org to all applicants after they submit an applications.

You can also specify when the form will automatically become and stop being available from the public, using the date fields at the end.

Once you save the form, you can access it by going here: http://djangogirls.org/yourcity/apply (replace `yourcity` with url to your city website). This is an address you should also add on your website and share with potential applicants.

To see all applications submitted to your event, go to an URL like that: http://djangogirls.org/yourcity/applications/ (remember to replace `yourcity` with your website address).

### Questions

As you probably noticed, when you create a form, we also automatically add default questions. You can always edit, remove or add new questions by going to [Django Girls Admin -> Applications -> Question](http://djangogirls.org/admin/applications/question/). Yay!

It is also a good idea to ask about previous experience in fields like programming (any language), Python, CSS, HTML, Django, databases etc. With that information, you will be able to team up people based on their levels of experience. Also, ask your attendees what language they are comfortable with. Some of your coaches might only speak English so they will need to coach a group who is comfortable being taught in English, and even if there isn't a translation of your tutorial in your country's language available yet, you can at least make sure that the attendees feel comfortable by having a coach who speaks their language.

### Financial aid questions

If you offer a financial assistance to your attendees, here is a list of example questions:

1. Do you need financial assistance to come and stay in [city]?
2. What is your current financial situation? Tell us why you need financial assistance.
3. How much money do you need? Give us an exact amount of Euro/dollars you need. Try to break down costs.

### Form submit notifications

Once your applicants submit their answer, they will receive an automatic confirmation to their email address with a copy of their responses. Woohoo!

## Acceptance/rejection e-mails

To make it easy for you to email all attendees at the same time, we build a way to send the same email to a chosen group of applicants.

In order to do that:

- Go to http://djangogirls.org/yourcity/communication/ (replace `yourcity` with your website address)
- Click the "create new e-mail" button
- You will see a form like that:

 ![](https://dl.dropboxusercontent.com/u/527278/Screen%20Shot%202015-06-25%20at%202.37.42%20PM.png)
 
- You can choose the Recipients:
 - `Application submitted` - means everyone with the application status = `submitted`
 - `Application accepted` - means everyone with the application status = `accepted`
 - `Application rejected` - means everyone with the application status = `rejected`
 - `Application on waiting list` - means everyone with the application status = `waiting list`
 - `RSVP: Waiting for response` - means everyone with the application status = `accepted` and rsvp status = `waiting`
 - `RSVP: Confirmed attendance` - means everyone with the application status = `accepted` and rsvp status = `yes`
 - `RSVP: Rejected invitation` - means everyone with the application status = `accepted` and rsvp status = `no`

## What's up with this RSVP thing?

[RSVP](https://en.wikipedia.org/wiki/RSVP_(invitations)) is sent to all accepted attendees. You should ask them if they still can attend the workshop, because otherwise you will give their spot to someone from the waiting list. 

It's hard to gather information about that from ~30-40 people and make sure you won't mix something up, so we build a tool for that too.

When you're sending your acceptance letter to all accepted attendees, make sure to add `RSVP: yes` and `RSVP: no` links to the email. You can do so by clicking the `Add a RSVP: yes link to email` and `Add a RSVP: no link to email` buttons above Recipients field. This will add a placeholder to the content of your email, something looking like that: `[rsvp-url-yes]`. **You should always include both 'yes' and 'no' links!**.

The content of the message should look like that:

    Hey there!
    
    Congratulations! Your application to Django Girls event in City has been approved. We can't wait to meet you on our workshop!
    
    To confirm your attendance, please go to this link: [rsvp-url-yes]
    
    If you can't attend, we would be really grateful if you could let us know earlier, so we can give your place to someone from the waiting list. To let us know, simply click this link: [rsvp-url-no]
    
    Thank you!
    Django Girls team

Our system will replace these tags with unique generated URLs, and log information about which applicant clicked on which link on the list of all applications, so you don't have to track it manually. Yay!