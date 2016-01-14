Bluemix-Gallery-Bootstrap
=========================


There are more and more articles and very good sample applications showing the capabilities of IBM Bluemix. A huge community is making apps every day. Most of these apps are published in Developerworks website, and there is no single view of all that is available out there. That is why I create the “Bluemix Application Gallery”.

<center>![alt tag](http://bluemixanalytics.files.wordpress.com/2014/09/app-gallery.png?w=700&h=476)</center>

The website is developed using [Bootstrap](http://getbootstrap.com/) <BR>
The thumbnail hover effect is coming from here: http://www.bootply.com/90238

To deploy it on Bluemix (or Cloud Foundry) I used the Nginx buildpack for static websites:<BR>

https://github.com/cloudfoundry-community/nginx-buildpack

<BR> Simply push the application using the following command on CF:
<BR>

```
cf push -b https://github.com/cloudfoundry/staticfile-buildpack <appname>
```

<BR>Find more information about Bluemix and this application in my blog:
<BR>http://bluemixanalytics.wordpress.com/2014/09/02/lets-welcome-the-new-bluemix-application-gallery/
