# Communication with applicants

## Form submit notifications

You don't need to worry about setting notification: once your applicants submit their answer, they will receive an automatic confirmation to their email address with a copy of their responses. Woohoo!

## Acceptance/rejection e-mails

To make it easy for you to email all attendees at the same time, we build a way to send the same email to a chosen group of applicants.

In order to do that:

- Go to https://djangogirls.org/yourcity/communication/ (replace `yourcity` with your website address)
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

While composing messages try to be positive and polite. This could be not that easy given you have to reject a number of applications. Rejecting applications is tough. Being rejected is tough as well. You can find some good examples of messages you might want to use under our [resources](https://github.com/DjangoGirls/resources/tree/master/text_templates) repository.

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
