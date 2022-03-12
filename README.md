# Java_Maven_xml-config-file-bug-fix

Sometimes when using Spring Framework in Intellij, it may not be able to create a XML Cofig File from to a package.
This is happended because of some complier issue on the build-in Maven3 plug-in.
To solove this, just add the "settings.xml" file to .m2 folder and change the Maven home path from defualt to the path of Maven3 folder.

![image](https://user-images.githubusercontent.com/87108685/158038541-80ad3809-77bc-4fac-9d5c-ea935a3f70b0.png)
