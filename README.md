# AEM-Email-Example
AEM email component that uses the ACS Commons Email API

Developer: Scott Westover
Blog: http://scottwestover.blogspot.com/

You can find a tutorial on how to build the component here:

http://scottwestover.blogspot.com/2015/03/aem-component-to-send-email-tutorial.html

This component was built using AEM 6. In order to use this component you must
install the ACS AEM Commons package located on github at:

https://github.com/Adobe-Consulting-Services/acs-aem-commons

Once this is installed, just take the zip file and install it on the package
manager located in crxde. You will then need to configure the Day CQ Mail 
Service component with your details in order to make the component work.

Next you will need to update the email template that was installed located
at: etc/notification/email/en.html and change the recipients email address
with yours or the one you want to send the email to.

Once this is done, navigate to Email Example site, and once the page loads 
it should display a message indicating if the email was able to send or not.

When I built this component, I was using a Gmail account, so you might have to 
change the OSGI configuration to work with another account, or get a Gmail account.

Finally, you might have to update your email settings to allow less secure apps
to access your account so AEM can send out the email.