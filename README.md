
Wild Cats Conservation Federation Website.

Overview

On this project i decided to make a charity website. I did not have any particular idea but i recently saw a documentary on wild cats and how endangered they where so that is where is got the inspiratio, i guess. I have never been good at this kind of stuff. Even as i sit here at 1:39 i am not happy but it is no use thinking about at this point i have about 60 hours left to get this done, minus sleep. 

If i was going to make something i thought it would be something that would atleast try to benefit people, or animals in this case. 

Essentially, this part is your sales pitch.

UX

This website is for anyone looking for a charity specificly targeting cat rescue/conservation. 

Design process. I looked at several other charity websites that focus on the conservation of wild cats and saw what things they had. The first and most important aspect of a charity is the donation page. Since we are trying to raise money for a cause i determined that this was the number one most important part. A big button that says donate on every page. 

User story: As a person looking for a suitable charity i want to get information on what type of work the organisation does. 

I also want a place to donate. If i decide to make a contribution to the organisation i want that process to be as clear and easy to understand as possible. A big button.

I want to be able to recive updates on the organisations ongoing efforts. A newsletter. 

I want to be able to access information and to be able to make contact with the people behind the project easily. 

In particular, as part of this section we recommend that you provide a list of User Stories, with the following general structure:

Link to wireframe. Link to user story. 


Features
In this section, you should go over the different parts of your project, and describe each in a sentence or so.

Existing Features

Feature one - Donation button/form. A place where one can make donations is available on every page and sits in the navigation bar at the top of the page. 

Feature two - Newsletter signup form. Same as the above, if a user finds themselves interessted in the project a button to signup to our newsletter. 

Feature three - Gallery. An easily expandable gallery is available to acces from the menu and proves insight on the different animals the organisation is targeting and some light information about them. The page also directs users to some more heavy reading they can do elsewhere on the internet. It just takes them to the wikipedia article for each species but i decided that this would be sufficent. 

Feature four. Contactt form. If one wished to get in touch with us they are provided with a form in the footer section on every page. Allows users to fill out a contact form.

Additional Feature. Expanding the gallery section to include additional information and having a video section. Also a section where perhaphs people can vote on different cat species they want us to work with, like an intergrated strawpol. 

For some/all of your features, you may choose to reference the specific project files that implement them, although this is entirely optional.


Technologies used in this project. 

For this project i used VScode as my editor. 
https://code.visualstudio.com/. VScode is has wide functionally. I used a bootstrap extension to autogenerate the templates with a simple !bscn,although i found later on that the template did not pass the w3c validation. Still saved me from having to copy paste the scripts from their website. Link to extension: https://marketplace.visualstudio.com/items?itemName=eventyret.bootstrap-4-cdn-snippet


Libraries/frameworks.

Bootstrap version 4.1. https://www.getbootstrap.com. It provided a simple way to speed up development and made it easier to make the site look good across media platform. Also made it possible to have the submission forms as modals instead of them being their own separate pages.

Jquery. The project uses JQuery to simplify DOM manipulation. Bootstrap 4 also uses jquery for some of it's functionality. The extent of its use is limited but allow the form functionaly to work properly.

Testing

Donate form. Doesn't let you continue unitl you have filled out all the required fields. Although it does not connect to an external api that can process donations so for now it is just for show. 

If you dont fill it out correctly it will tell you as so: 

<img src="docs/images/donatetest1.png">

And if you fill out the form it will take you to a small confirmation page as so:

<img src="docs/images/donatetest1.png">

Newsletter form. Same as the above. Takes you to a confirmation page if you fill it out, doesnt let you pass otherwise. 

<img src="docs/images/newslettertest1.png"> 

And if you fill it out corretly it takes you here: 

<img src="docs/images/newslettertest2.png">

Contact form. Works the same as the other two. Doesn't let you pass until you fill out all the fields. 

<img src="docs/images/contacttest1.png">

And here is the page you will see after making a valid submission:

<img src="docs/images/contacttest2.png">

Gallery. The gallery proves you with pictures of cats. If you click on one you will be presented with a couple of paragrafs on detailing threats facing them along with a button that takes you to their wikipedia article.

Look and feel across media platforms. The navbar changed based on your screen size i used a bootstrap class nav-bar-expand-xl for this as this required me to automate and not have to incorporate media queries in my css file. xl covered all cases from the smallest phone up to the largest tablet on the chrome devtool, the ipad pro. 

<img src="docs/images/ipadprolook">

This look is retained across all the pages (since the code is the same).

Problems/bugs. I had alot of trouble making the gallery look good. The card class i found difficult to work with. 


In addition, you should mention in this section how your project looks and works on different browsers and screen sizes.

You should also mention in this section any interesting bugs or problems you discovered during your testing, even if you haven't addressed them yet.

If this section grows too long, you may want to split it off into a separate file and link to it from here.

Deployment

I used github. Deployed it on pages. Run it locally on chromes, i use vscode. 

This section should describe the process you went through to deploy the project to a hosting platform (e.g. GitHub Pages or Heroku).

In particular, you should provide all details of the differences between the deployed version and the development version, if any, including:

Different values for environment variables (Heroku Config Vars)?
Different configuration files?
Separate git branch?
In addition, if it is not obvious, you should also describe how to run your code locally.

Credits
Content
The text for section Y was copied from the Wikipedia article Z

All the text on the gallery comes from wikipedia and the indangered species list.

Media

The pictures where mainly taken from https://unsplash.com/. In the gallery the main species pics are from their respective article. Atleast for some of them. 

The photos used in this site were obtained from ...


Acknowledgements

I was inspired by panthera.org mainly. 

I received inspiration for this project from X