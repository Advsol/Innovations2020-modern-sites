# Creating Modern Websites in RiSE

Included in this repository are assets so you can include the Latte theme in your instance of iMIS. Please note this website and theme are for demonstration purposes only and have only been tested in Chrome for Windows 10. Additionally, the theme was designed for iMIS Cloud Enterprise version 20.3.44 and some things may not work as expected in earlier versions of iMIS.

**Slide show from the presentation:** https://drive.google.com/file/d/1V2RX5R59_g21kzxKZVSAbl2Ap67j8IcS/view?usp=sharing

**A demo site:** https://imistour15132.imiscloud.com/EcoCauses/
Note: standard Starter DB logins are active on this site. Feel free to log in, click around, and see how we accomplished these designs. However, please do not make any changes to the content on this site. Instead, follow the steps below to install the theme and site on your own instance of iMIS.

If you would like to be notified when changes are made to this repository (e.g. if we make updates or add more resources) click the "Watch" button at the top of the repository.

## Website and theme installation instructions

To install the demo website and theme follow these steps:
1. Download the contents of this repository.
2. Next you will need to zip up the "Latte" folder, which contains all theme assets.
3. Under RiSE > Tagging > Tagged list formats import the ContentTaggedLists.xml file and publish.
4. Under RiSE > Document system select the "images" folder then import the Images.xml file.
5. Under RiSE > Document system select the “Common/Uploaded files” folder then import the Videos.xml file.
6. Under RiSE > Theme Builder > Website layouts import the Coffee_Layout.xml file.
7. Under RiSE > Theme Builder > Website templates import and publish the Coffee_Template.xml file.
8. Under RiSE > Theme Builder > Themes select New > Theme. Name the theme "Latte", be sure the box is checked indicating it is responsive, then select the .zip folder you created in step 2. Select "Coffee" as the website template. Save and publish the theme.
9. Go to RiSE > Page Builder > Manage Layouts import the Page_Layouts.xml.
10. Go to RiSE > Site Builder > Manage websites and import and publish the EcoCauses_Website.xml file. 
11. Go to RiSE > Page Builder > Manage content. If the content was correctly imported go ahead and publish it. If not, you can delete the content that was imported then import and publish the EcoCauses_Content.xml file.
12. (Optional) If you would like to see the "Follow us" navigation items in the footer you will need to add a custom navigation area. Go to RiSE > Site Builder > Manage websites and select your EcoCauses website. Select the Navigation areas tab and click the pencil icon on the tab. Add a new navigation area called "Footer2". Please note that the Navigation Pane Code will need to be 16 in order for the navigation to appear. If you already have a navigation area with the code 16 then you may need to update the "Follow us" navigation items to use the new navigation area instead.

At this point you will have a working website with the new theme.
