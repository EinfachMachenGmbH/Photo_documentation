## Photo_documentation
In this repo we provide a straightforward solution for mobile photo documentation using power apps &amp; power automate. There are basically two components important for maiking thi solution work

## Note
You will need to import or create the flow with the account that will be used later to save the photos to sharepoint.
That means:
If you want to use a separate mailbox for the photo documentation and do not want to send everything to your own mailbox, then import the solution best with this account
This way the flow will be triggered later when an email is sent to a specific mailbox (the one you imported the flow/solution with). 

## How It Works
1. At first import the solution using the .zip File in this repo.
   <img src="https://i.imgur.com/uSU55iQ.png" align="right"
     alt="Import solution" width="120" height="178">
2. The Flow and the Power App should now be visible in your environment
4. At first edit the flow. You need to reconfigure the connections and assign them to your Outlook & SharePoint Online Connection
   <img src="https://i.imgur.com/PhntuAk.png" align="right"
     alt="Import solution" width="120" height="178">
     3. If you want to use more metadata in your document library, you can add more information here in the json. You also need to add this in the app later.
4. Activate the flow after all connections work well and you have assigned your document library
5. Open the powerapp in edit mode
   <img src="https://i.imgur.com/fL2TmTN.png" align="right"
     alt="Import solution" width="120" height="178">
6. Test the app in power apps studio. You should receive an e-mail with photos to your inbox
   <img src="https://i.imgur.com/fL2TmTN.png" align="right"
     alt="Import solution" width="120" height="178">
7. Now you could pass more information in the JSON or send the photos still a separate mailbox if you imported the flow to process the photos on SharePoint with another account.
   <img src="https://i.imgur.com/kQUJ92O.png" align="right"
     alt="Import solution" width="120" height="178">

