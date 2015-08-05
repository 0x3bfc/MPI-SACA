#GCE Vagrant

**Generate GCE JSON KEY**

Prior to using this plugin, you will first need to make sure you have a Google Cloud Platform account, enable Google Compute Engine, and create a Service Account for API Access.

* Log in with your Google Account and go to Google Cloud Platform and click on the Try it now button.
* Create a new project and remember to record the Project ID
* Next, visit the Developers Console make sure to enable the Google Compute Engine service for your project If prompted, review and agree to the terms of service.
* While still in the Developers Console, go to API & AUTH, Credentials section and click the Create new Client ID button. In the pop-up dialog, select the Service Account radio button and the click the Create Client ID button.
* Make sure to download the P12 private key and save this file in a secure and reliable location. This key file will be used to authorize all API requests to Google Compute Engine. 
* Still on the same page, find the newly created Service Account text block on the API Access page. Record the Email address (it should end with @developer.gserviceaccount.com) associated with the new Service Account you just created. You will need this email address and the location of the private key file to properly configure this Vagrant plugin.
