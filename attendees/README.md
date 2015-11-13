# Attendees

The goal of Django Girls is to bring new people into technology. __We are focused on women, but it is totally fine to organize workshops without any gender requirement__. We encourage local organizers to give a priority to female applicants, especially when the workshop is organized under the Django Girls name. 

The tutorial is designed for total beginners, so no programming background is needed. Basically, any person with a computer can do it.

However there are some things to look out for. If you organize something for free there is a chance that some people will not appear at all. They didn't invest any time or money, so it is easy for them to simply not come. That's why you should try to find people who really, really care.

The only way you can measure somebody's commitment is their application form. Make sure that it contains questions that will give you necessary hints about the person.

## How do people sign up?

### Local events

If you don't plan on providing any financial aid for participants you should open an application process at least a month (ideally two) before the event. Give people two weeks to apply, and ask them why they should be the ones to attend the event, and what is their motivation. It's easiest to use Django Girls website to manage applications. We will talk more about this below. Send people acceptance/rejection e-mails a week before the event. Make sure they confirm that they will attend.

### International events

If you organize an event and expect to have people from many different countries, you should start much earlier. There is a chance that you will have people who need visas. In this case, you need to let people know if they are invited at least one month before the event.

#### Visa invitation letter

It is also possible that you will need to provide an invitation letter for the participants who require visas. It might look like this:

> Through this paper we certify that _[name of participant]_, born _[birth date of participant]_, living at _[country]_, _[address]_, with passport number _[passport number of participant]_, valid from _[date]_ to _[date]_, is invited during the period of [date] to [date] to participate in the Django Girls workshop organised by _[name of some legal entity or you]_ with the address: _[address]_; phone: _[phone]_, e-mail: _[email]_.

> _[here you can put some info about who organises the event - if it a part of conference you should put some info about it here]_

> Free food and social activities will be provided by organisers during the period of stay.

> We kindly request that you grant a free visa for this particular participant of the Django Girls workshop.

> [your name]

You will need to send this letter (signed!) to the participant. You should also scan the signed papers and send the copy via e-mail.

## Application form

### Create a form on Django Girls website

You can create one application form for each Django Girls website. In order to do that, go to [Django Girls Admin -> Applications -> Form](http://djangogirls.org/admin/applications/form/) and click the "Add form" button. You will see a form like that:

![](https://dl.dropboxusercontent.com/u/527278/Screen%20Shot%202015-06-25%20at%202.20.19%20PM.png)

Now you should edit out all the texts. Confirmation mail is what we will automatically send from your city@djangogirls.org to all applicants after they submit an applications.

You can also specify when the form will automatically become and stop being available from the public, using the date fields at the end.

Once you save the form, you can access it by going here: http://djangogirls.org/yourcity/apply (replace `yourcity` with url to your city website). This is an address you should also add on your website and share with potential applicants.

To see all applications submitted to your event, go to an URL like that: http://djangogirls.org/yourcity/applications/ (remember to replace `yourcity` with your website address).

### Questions

As you probably noticed, when you create a form, we also automatically add default questions. You can always edit, remove or add new questions by going to [Django Girls Admin -> Applications -> Question](http://djangogirls.org/admin/applications/question/). Yay!

It is also a good idea to ask about previous experience in fields like programming (any language), Python, CSS, HTML, Django, databases etc. With that information, you will be able to team up people based on their levels of experience. Also, ask your attendees what language they are comfortable with. Some of your coaches might only speak English so they will need to coach a group who is comfortable being taught in English, and even if there isn't a translation of your tutorial in your country's language available yet, you can at least make sure that the attendees feel comfortable by having a coach who speaks their language.

#### Financial aid questions

If you offer a financial assistance to your attendees, here is a list of example questions:

1. Do you need financial assistance to come and stay in [city]?
2. What is your current financial situation? Tell us why you need financial assistance.
3. How much money do you need? Give us an exact amount of Euro/dollars you need. Try to break down costs.

#### Form submit notifications

Once your applicants submit their answer, they will receive an automatic confirmation to their email address with a copy of their responses. Woohoo!

## Choosing attendees

You can see all applications submitted to your event by going to an URL like that: http://djangogirls.org/yourcity/applications/ (remember to replace `yourcity` with your website address).

There you will see a list of all applications. You can filter them by state or RSVP status, you can see the details of each application and assign them to groups (accepted, rejected, waitlisted) as well as set their RSVP statuses (yes, no, waiting).

### How to choose attendees?

If you receive a lot of applications you will face a very hard problem: who should you choose? It was very hard for us to decide, but we came up with a way to score applications.

Once you click on one of the applications, you can see that there is also a way to score applications there. All of the organizers can add scores for each application.

### Scoring

To ensure that the first score is not influenced by others, each person scores applications without knowing the other people's scores. After making a first scoring, one can see the other marks.

The order of applications is also not determined - we score in random order, so the probability that one person is scored higher/lower only because she was always on top/bottom of the list is lower.

You can score each application from 1 to 5.

Here is a list of things we took into account when scoring (suggested by Daniele Procida):

* what is the realistic benefit to the applicant?

* what is the realistic benefit to others?

* does the applicant have clear, specific, concrete, realistic ideas about what to do with the knowledge?

* does the applicant have clear, specific, concrete, realistic ideas about how she will share it?

* do I feel the applicant really, really wants this opportunity, or is it just an interesting offer to her?

* what is the overall value for money, if the applicant is asking for funds?

* what is my overall feeling about the application?

As you can see, there were a lot of points we took into account when scoring. It was very, very hard to get in. If the application was not very detailed, the chance of it being accepted was very low. But writing a lot was not a recipe for success. We looked for concrete ideas and commitments in applications.

Look for a diverse group: the more different people are, the more crazy/fun/creative ideas will happen during the event.

The final tip: follow you heart! Choose those who convince you the most, those who need it, those who may want to change their lives and follow this path as a career. The choice is yours, but it's never easy.

## Waiting list

It's a good idea to create a waiting list. We informed people that they didn't get in, but they were very close and asked them if they will be interested to join at a short waiting list if a spot will be available. There is always a couple of people who will say that they can't attend, so this way you can still fill the empty slots. 

## People resigning

We had a number of people who said they won't manage to come even though they confirmed their attendance before. The waiting list worked very well in this scenario.

Be prepared to have some last minute (as in, one day before the workshops) cancellations. It's normal. As long as you have people who can fill in, don't worry.

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
