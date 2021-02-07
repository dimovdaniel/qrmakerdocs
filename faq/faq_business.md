## Add more download print templates / change existing

At the moment, manually upload your zip of template directly in the "**public**" folder or create a new folder in there. You can also upload the zip in some File Storage like Google Drive, One Drive etc..   
Then, get the link to the zip file, and in your .ENV editor add or edit variable **linkToTemplates** that will link to the zip. 

To change the images displayed there, upload the images to the public folder or in some image share tool like Imgur.  Get the links and enter them as .ENV variable templates, comma-separated. 

ex

```text
linkToTemplates="/impactfront/img/templates.zip"
templates="/impactfront/img/menu_template_1.jpg,/impactfront/img/menu_template_2.jpg"
```
