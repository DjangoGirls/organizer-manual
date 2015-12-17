# Administrating your website

We have built a simple Django application that allows you to create your events website in a really simple way. You don't have to know how to code to change it but a little knowledge about HTML and CSS will be helpful :).

Your website will be created after you filled a [request](https://djangogirls.org/organize/) for organizing an event and confirmed you read this manual ;)
Don't forget to give us the name and email address of the other members of your team if you have any.

All your team will receive an access to the Django Admin panel. It looks like this:

![](images/1.png)

## Edit your event

You can access and edit basic information about your workshop in the event section of your admin interface:

* Click on `events list` in the left panel
* Clicked on your event and you will get this page:

![](images/4.png)

You can edit most fields but keep those few rules in mind:

* You can change the event date if you want to set a more precise date and postpone or delay an event.
* You can modify the cover picture for your event. Remember that this picture should be under Creative Common Licence. To find a new one, you can look on [Flickr](http://flickr.com/) or [Wikipedia](https://en.wikipedia.org/wiki/Main_Page). Don't forget to update photo credit and link.
* You can't edit your team: if you want to add or remove someone, [contact us](mailto:hello@djangogirls.com)

## Create a mailing list

You want to create your website but your event is far away? You may want to create a mailing list to keep people inform.

* Go to [MailChimp](http://mailchimp.com/) and create a free account.
* Create a list.
* Click on your list in the `lists` tab.
* Click on `Signup forms` and `Embedded form`.
* Edit your form and copy the code.
* Go to `Website Contents` in your Django Girls admin interface.
* Click on the item where you want your form to appear.
* Past the code in the `Content` section and save your modifications!

:tada:

We recommend you to read [Getting Started With MailChimp](http://mailchimp.com/resources/guides/getting-started-with-mailchimp/html/) and [Create Signup Forms and Response Emails](http://kb.mailchimp.com/lists/signup-forms/create-signup-forms-and-response-emails) if you want to know more about how to create a mailing list and a signup form.

## Manage and edit content

### Structure of your website

Your website will come with some default items that you can adjust to your needs:

* `about`: catchphrase for your event!
* `values`: general description of your event.
* `apply`: link to application form for attendees.
* `faq`: questions attendees frequently ask.
* `coach`: information for potential coaches and link to application form.
* `partners`: sponsors!
* `footer`: link to social media and Code of Conduct.

### Edit content

To change the content of your website:

* Go to `Website Contents`.
* Click on the item you want to modify.
* Edit the html in the `Content` field.
* Don't forget to save your modifications by click on the `save` blue button on the right.

:tada:

### How to add sponsors?

First, go to `Website Contents` and click on `partners` in the list. You will obtain this page:

![](images/3.png)

To add a sponsors, go at the bottom of this page and look if your sponsor isn't already in the drop down menu. If it's the case, select it and click on `Add another Eventpagecontent-Sponsor Relationship`. If your sponsor isn't in the menu, click on the `plus` button and a new window will open:

![](images/5.png)

* Add the name of the sponsor.
* Choose a picture from your computer with a sponsor's logo. Make sure it is not too big or too small. You can leave this field empty - in this case the name of the sponsor will be displayed instead of the picture.
* Add the website address of the sponsor.
* You can add some extra description, but we usually leave it empty.
* Click on save.
* Add as many sponsors as you want by clicking on `Add another Eventpagecontent-Sponsor Relationship`.
* Don't forget to save your modifications by click on the `save` blue button on the right.

:tada:

### How to add coaches?

You may want to add a list of the people who will coach at your event.

* Go to `Website Contents`.
* Click on the `Add Website Content`green button.
* Select your website in the `Page` field.
* In `Name`, add `coaches`.
* In content, you can copy past this: 

```html
<h3>Coaches</h3>
<p>Join these awesome people as Django Girls coach! Contact us!</p>
```

* Don't add a background.
* Check the `Is public` box.
* Go at the bottom of the page in the `Coaches` section.
* Look if your coaches aren't already in the drop down menu. If they're not, add them by clicking on the `plus` button. The only field required is the name. If you don't have pictures for your coaches, put Django Girls [logo](https://github.com/DjangoGirls/resources/blob/master/Design/Logo/logo_square.png). Click on save.
* Add as many coaches as you want by clicking on `Add another Eventpagecontent-Coach Relationship`.
* Don't forget to save your modifications by click on the `save` blue button on the right.

:tada:

## When you're ready!

To make your website available to everyone, click on `Website` and on your website in the list, you'll obtain this:

![](images/2.png)

The most important thing here is the `Is live` checkbox. When your website is ready, click on it and save your page. Tada: your website is now online!

Remember that you don't need to make it "live" to test your website: as an administrator of your website, you'll always have to access it.