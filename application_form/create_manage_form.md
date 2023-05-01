# Create and manage the form

## Create a form for your event website

You can create only one application form for your event website.

To do that:

* Go to your admin interface.
* Click on `Application Form` in the left menu.
* Click on the `+ Add form` green button on the right.
* You'll obtain this page:

![](../.gitbook/assets/1.png)

Now, you need to edit every field:

* `Text description`: it's the header of your form. It will appear at the top of the apply page like this:

![](../.gitbook/assets/2.png)

* `Confirmation email`: This email will be automatically send from your city@djangogirls.org to all applicants after they submit an applications.
* `Application process is open from/until`: Both fields are mandatory. Potential attendees will be able to register only during this period. After that, the form will be automatically deactivated and they won't be able to reach [http://djangogirls.org/yourcity/apply](http://djangogirls.org/yourcity/apply) \(replace `yourcity` with url to your city website\).
* Don't forget to save your modifications by clicking on the `save` blue button on the right.

Once you've saved the form, you can access it by going here: [http://djangogirls.org/yourcity/apply](http://djangogirls.org/yourcity/apply) \(replace `yourcity` with url to your city website\).

## Add a link from your event website to your form

The link to your form will be automatically created. If you want to check if everything is working:

* Go in your admin interface.
* Click on `Events` in the left menu.
* Click on `Website contents`.
* Click on `apply` in the list.
* Check if `<a class="btn" href="apply">Register</a>` is there or add it.

## Open the application form

The application form will be automatically open at the hour and date you chose when you created it. Note: we have a [timezone problem](https://github.com/DjangoGirls/djangogirls/issues/240)! If your form is supposed to be open, check the hour in the top part of the admin interface and replace `Application process is open from` by this time. It should fix the problem. Sorry :\(

## Close the application form

Your form will be automatically closed at the date you chose when you created it. You don't need to remove the link to it: it will be automatically deactivated too.

To prevent any confusion and minimize the "can I still register?/when will I received an answer?" emails, we strongly recommend you to replace the content of `apply` section of your website by this text:

`Registrations are now closed: we received many applications and are now evaluating them. Acceptance emails will be sent soon!`

## How to find applicants answers?

To find and evaluate all applications submitted to your event:

* Go to an URL like that: [https://djangogirls.org/yourcity/applications/](https://djangogirls.org/yourcity/applications/) \(remember to replace `yourcity` with your website address\)

Or:

* Go to your admin interface.
* Click on `Submitted Applications`.
* You'll be automatically redirect to the applications manager. If you already have organized multiple events, you'll need to chose the event you want in the list.

Or:

* Go to your admin interface.
* Click on `Forms`.
* Click on `See all submitted applications` in the `Applications` column of the table.

## Add or edit questions

Every form is created with default questions. It should cover your need but you can edit them or add new one if you need it.

### To edit a question:

* Go to your admin interface.
* Click on `Application Form` in the left menu.
* Click on `Questions`.
* Click on the question you want to change.
* Make your changes and click on the `save` blue button on the right.

### To remove a question:

* Go to your admin interface.
* Click on `Application Form` in the left menu.
* Click on `Questions`.
* Click on the question you want to delete.
* Click on `delete` button on the right.
* Confirm. It's gone!

Do not remove the question about the Code of Conduct: remember that each event has to follow and enforce our [Code of Conduct](https://djangogirls.org/pages/coc/).

### To add a question:

* Go to your admin interface.
* Click on `Application Form` in the left menu.
* Click on `Questions`.
* Click on `+ add question`.
* Chose your event on the list.
* Create the new content.
* Don't forget to save your modifications by clicking on the `save` blue button on the right.

It is also a good idea to ask about previous experience in fields like programming \(any language\), Python, CSS, HTML, Django, databases etc. With that information, you will be able to team up people based on their levels of experience. Ask your attendees what language they are comfortable with. Some of your coaches might only speak English so they will need to coach a group who is comfortable being taught in English. Even if there isn't a translation of your tutorial in your country's language available yet, you can at least make sure that the attendees feel comfortable by having a coach who speaks their language.

## Financial aid questions

If you offer a financial assistance to your attendees, here is a list of example questions:

1. Do you need financial assistance to come and stay in \[city\]?
2. What is your current financial situation? Tell us why you need financial assistance.
3. How much money do you need? Give us an exact amount of Euro/dollars you need. Try to break down costs.

## What should I do if something isn't working?

First, you can look at our [FAQ](https://faq-organizers.djangogirls.org/) to see if your question isn't already answered there. If not, try to contact other organizers on [Slack](https://djangogirls.slack.com/): they'll be happy to help you! If after doing that you're still stuck, contact the [Support Team](mailto:hello@djangogirls.org).

