info
====

This project is made in the purpose of getting a possibility to build an interface to generate an **integrated info** from all [GOOGLE CLOUDS PLATFORM](https://cloud.google.com/developers/) including *[API's](https://developers.google.com/apis-explorer/#p/), [Application API](https://developers.google.com/google-apps/app-apis), [Application Sripts](https://developers.google.com/apps-script/), [Application Engine](https://developers.google.com/appengine/); [Cloud Storage](https://developers.google.com/storage/), [Cloud Datastore](https://developers.google.com/datastore/), [Cloud SQL](https://developers.google.com/cloud-sql/)* etc. 

It aim to have the access and running all available program language like *[Python](https://developers.google.com/appengine/docs/python/), [Java](https://developers.google.com/appengine/docs/java/), [PHP](https://developers.google.com/appengine/docs/php/), [Go](https://developers.google.com/appengine/docs/go/)* with possible also *[Scala](http://www.scala-lang.org/old/node/1831) and [Ruby](http://code.google.com/p/appengine-jruby/)* and run them in the **same time** in to a SINGLE PAGE using a SINGLE DOMAIN without even need any sub domains! 

Thanks to Google for bring this possibility to the world and making it happen.


##Languange Structure
In order to run all program language in the same time then they are configured as below:
- **[Python](https://www.python.org/)** is used to access all images with an access to any Image Manipulation run from Phyton Frame such as *[Django](https://www.djangoproject.com/)* and compiled as 'images module'.
- **[Java](https://www.java.com/en/)** is used to access all javascript file with an access to Servlet Application run from Java / Javascript Framework such as *[GWT](http://www.gwtproject.org/)* and compiled as 'scripts module'.
- **[PHP](http://php.net/)** is used to generate the front page run from PHP Framework such as *[Zend](http://www.zend.com/), [Kohana](http://kohanaframework.org/)* etc and collected altogether in a 'default module'.
- **[Go](http://golang.org/)** is used to access any application that Support for *[Docker images](https://www.docker.com/)* in Google Cloud Platform with an intention to have a possibility to run and gain access a global structure application that run in other languages such as *[Perl](http://www.perl.org/), [C, C++](http://en.wikipedia.org/wiki/C%2B%2B), etc*.


##Application Structure
Having possibility to run all language then we have no more resistant to gain a **simultaneously** access to any other [GOOGLE PRODUCT](https://developers.google.com/products/) including *Google Talk, [Google Play Androids](https://developers.google.com/android/), [Google Maps](https://developers.google.com/maps/), [Google Drive](https://drive.google.com/), [Google Wallet](https://developers.google.com/wallet/), [Youtube](https://developers.google.com/youtube/), etc* which also open an access to more **widely and global** application such as *[Compute Engine](https://developers.google.com/compute/) and [Big Query](https://developers.google.com/bigquery/)*.

Find More of Google Products [here](http://en.wikipedia.org/wiki/Google_Services).

front page (generated by Php)
- images directory (access by Phyton)
- sripts directory (access by Java)
- styles directory (access by Go)
- plug-ins directory (where Python, Java, Php, and Go codes reside)

The application development is limited until gain the access only means once the communication to a targeted product is successfully provided then no further development will be made unless a necessary improvement required. This will also covering the selection to the *most reliable code* using most appropriated program language to do the job. 

Others programming language like **[Scala](http://www.scala-lang.org/)** and **[Ruby](https://www.ruby-lang.org/en/)** will also brought in to the projects. 

**The following development is on the way**: 
- Build the Front Page using PHP Frame Work ([Zend](http://stackoverflow.com/questions/19824594/zend-framework-1-x-on-google-app-engine) and [Kohana](http://raivoratsep.com/52/kohana-mvc-framework-on-google-app-engine-or-not/))
- Generate Script Manipulation to run Java Servlet using GWT compiled by [Eclipse](https://developers.google.com/eclipse/) or [Maven](https://developers.google.com/appengine/docs/java/tools/maven).

**On Going Development**:
- Generate Image Manipulation to run Python FrameWorks such as [Django](https://developers.google.com/appengine/articles/django-nonrel)
- Generate Styles Manipulation to run Go Framework using [Kubernetess/Docker](https://developers.google.com/compute/docs/containers)


##Documentation Structure
As Google has made a nice and beautiful documentation for each of their product then the documentation of this project will be made as simple as possible in only to explain a specific task on how to make the code running and successfully gain the access to each Google Product. The link to develop in deeper will be provided in the discussed section.

Building and Test is being carried out. As a sample for online demo that create a simple page applying the above scheme using Google App Engine with the Google Cloud Storage as well also use the following Google Products as below:

- [Google AdWords](https://adwords.google.com) to promote the front page
- [Google Analitycs](https://www.google.com/analytics/) to measure the pageview
- [Google Talk](http://www.google.com/talk/whatsnew_more.html) for online communication


##Algorithm Structure

For the time being this project is developed using all benefits on Google Products even all program code available in the planet to generate a widely integrated information to score and rate a group of sites running in **a same business category**.

It is quite hard to find such of business model that easily to be scored or whether our score is really represent the actual situation in the business live. To rectify in a short time that the script is correctly giving an correct result we need to test it on a kind of business model that also can be measured in a short time period.   

Having reviewing many alternatives we came to a business category called hyip ([high-yield investment programs](http://en.wikipedia.org/wiki/High-yield_investment_program)) which we found as a perfect model for us to be started. Following are some reason behind this selection to this busines model:

- Site that running hyip business are mostly online within short period (*a year or less*) and hyip business has to present  exact profit to the user in a short time basis to market their services.
- Most important is since the hyip is mostly a *ponzi scheme* so hyip site cannot be run in a long time period so we could  find whether our algorithm in our script is giving a correct scoring result in a short time as well.
- Hyip site is easily to be considered as dead or as a *hyip scam* when the site is stop paying so we consider that they could not blame our scoring (as we still on start to test it) in the same way that we cannot blame when they collapse or even run and take our investment away.

So base on the above measurement we can take all information of hyip service being offered compare to the trust of the domain that can be put altogether to score and rank the hyip sites, Despite we are still trying hard to predict how long a hyip site can be running online we have came to have a scoring result of best site which is more or less are the same as represent by other site that comparing those hyip sites. However as additional features compares to others we are providing the score with a numbers of category base on the investment or **budget level** start from as low as US$ 1. 

This is just a model to give you a figure on how we are going to start. If you like to see the script in action, it can be visited to the site called [hyip monitor](http://tophyips.info).  

On the long time running we have also want to go to **other widely business** such as scoring of who is *the best domain registrant*, who is *the best web designer*, who is *the best of seo provider*, who is *the best submission service* etc. We are going to present the result in the style as hyip scoring so even the user only have US$ 1 in their budget they could find our scoring is useful for them. As you know that it is really difficult to find such a good services when you have only a little budget. in the contrary you have to be more wise and careful to decide whether you still doing a business with your current partner or go to other more reputable business partner when your budget is growing up. 

That is all what we want to go. We intent to be among the best and trusted company in scoring any business in the same way as Google on giving their amazing service on '*keyword base*' search result to the world.

At last but not least we welcome for your comments or opinion to our project. Please feel free to try your hand at building other formats; any discussion will be opened later once the application is meeting the most targets as described above.

As an update we would like to announce that we have started to make our project documentation. Please don't expect to much on it. We are not a professional author nor even a good writer.    

You may start to browse the documentation. Usually people begin with a tutorial page titled '_Hello World_'. Here we have a little bit different. Let call it ['*Hyip World*'](https://github.com/hyipworld/hyipworld.github.io)
