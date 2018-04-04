---
title: Phraseapp Interface
book: tutorials
section: walkthroughs
chapter: phraseapp
slug: building
weight: 90
---
With our form built, make sure the form `access` is configured for your intended use case. In this example, permissions 
are set to `anonymous`. Now we need to create and retrieve two items from [phraseapp.com](https://phraseapp.com/account/login).
The first is a `ProjectId` and the second is an `Access Token`. additionally, we'll have to define which languages
our project should support. Once you've logged in go ahead and create a new project. 

![Project Create](/assets/img/tutorials/walkthroughs/translations/phrase-app-1.png)

Now that the project appears in your dashboard, hover over the and `more` → `project settings` → `API` and copy
the `ProjectId`

![Project Settings](/assets/img/tutorials/walkthroughs/translations/phrase-app-2.png)

Next, enter the project and click `locales`, in this demo I've setup and English and Spanish Language.

![Project Locales](/assets/img/tutorials/walkthroughs/translations/phrase-app-3.png)

Next, we need to create an `Access Token`, you can find the option under your username's drop down menu. 

![Where is Access Token](/assets/img/tutorials/walkthroughs/translations/phrase-app-4.png)

We don't have any tokens yet, go ahead and click `Generate A Token`

![Generate an Access Token](/assets/img/tutorials/walkthroughs/translations/phrase-app-5.png)

Since we only want people to read the translations and no change then, set the `scope` to `read` only.

![Access Token Settings](/assets/img/tutorials/walkthroughs/translations/phrase-app-6.png)

Finally, copy down your project's access token. 

![The Actual Token](/assets/img/tutorials/walkthroughs/translations/phrase-app-7.png)