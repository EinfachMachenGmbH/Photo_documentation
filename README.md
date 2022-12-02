## Photo_documentation
In this repo we provide a straightforward solution for mobile photo documentation using power apps &amp; power automate. There are basically two components important for making this solution work.

## Components 
1. power app - The power app "photo documentation" is used to take the photos and send them to an email inbox, e.g. photo@mycompany.com, along with a JSON with metadata in the email text. The JSON can be customized in the app AND flow to match your own SharePoint document library columns.
2. power automate - the flow "photo documentation | save to SharePoint Doc Lib" is used to store the photos recieved in the inbox to your sharepoint document library with the flow. The flow MUST be created with the account that will be used to receive the photos, since the trigger is "When a new e-mail is received (V3)"


## How It Works
1. At first import the solution using the .zip File in this repo.
2. The Flow and the Power App should now be visible in your environment
4. Edit the flow. You need to reconfigure the connections and assign them to your Outlook & SharePoint Online Connection
5. If you want to use more metadata in your document library, you can add more information here in the json. You also need to edit this in the app later, if you are making any changes in the json.
4. Activate the flow after all connections work well and you have assigned your document library
5. Open the powerapp in edit mode
6. Put the mailbox you are using for the flow to store the photos to sharepoint in the "To" Parameter at btnSendMail_Upload.OnSelect
6. Test the app in power apps studio. You should receive an e-mail with photos to your inbox
7. The flow gets triggered when there is a new E-Mail and stores all attachments to your Document library

## Contact us for issues
info@ema-sh.de
