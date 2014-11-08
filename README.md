This project uses gradle (gradle-appengine-plugin) to build, test and deploy the simplest possible "Hello World" servlet.

To build, deploy and test locally: (Assuming you have **git** and **gradle** installed)

1. git clone git@github.com:oakstair/gradle-gae-plugin-tryout2.git
1. cd gradle-gae-plugin-tryout2
1. gradle appengineRun        
1. In a web browser goto http://localhost:8888


To build, deploy and test on appengine:

1. git clone git@github.com:oakstair/gradle-gae-plugin-tryout2.git
1. cd gradle-gae-plugin-tryout2
1. Edit ./build.gradle and set appId and appEmail to your own values.
1. Edit war/WEB-INF/appengine-web.xml  Change application to your application name.
1. gradle appengineUpdate  
1. In a web browser goto http://your-app-name.appsot.com
