# TOH

Administrative Changes/Cleanup

URGENT:  Remove the Link to the Contact PDF
      Remove the link to the Contract PDF.  In the next few days I will provide a cloud link location we will store the contracts.  The file name will remain the same generic name (Rental-Agreement.pdf).
      I will be adding the file to a document version control system and storing the latest pulled version either in Box, DropBox, Google Drive, or OneDrive.  I will provide the URL, AuthToken, and/or id_rsa.pub depending on where I end up hosting the document.

      We have too many locations various versions of this file has been uploaded to and I don't want to have to upload changes to 20 different locations every time there is an update.  So moving forward I will be servicing all locations the Agreement is linked from one cloud space.

      But we absolutely need to remove the link to the current file immediately


1:  Add the following line Above Email Address:
      Please use the information below to contact our Staff

2:  Change email address:
      Remove:  Email Address: "oldhomesteadevents@gmail.com"
      Add to HTML:  <a href="mailto:event.coordinator@oldhomestead.events">Email our Staff</a>


3:  Remove Event Coordinator
      Remove:  Event Coordinator: Keri Marin

4: Replace Telephone Number
    Remove:  510 660 5174 from Contact area and Footer
    Add these Phone Number(s):
      Main Office:  (510) 560-5980
      Event Coordinator:  (510) 560-5977
      
      


Code Changes to theoldhomestead.org

  All 3 javascript snippets need to be added to the main page of theoldhomestead.org

      zoho_salesiq - used to track visitors; integrates  Live Chat function into the website.  Both tie into the CRM for analytics and customer service

      zoho_contactus_form - Replacement for the current Contact Us form.  This form is directly integrated to the CRM so we can centralize our sales and contact data.  The Form will automatically capture all of the data, create a Lead record, and trigger automated tasks in the CRM for sales followup, and quote-to-contract-to-invoice automation.  

        calendly-widget - Online Appointment booking for Homestead Staff.  Initially we will use it for new potential renters to book tours and first time appointments, quick meetings to make payments, and plot map review meetings.  We will be expending the list soon and creating Sales driven meetings; and Service meetings for contracted renters.

      Instructions and Layout:

      zoho_salesiq
      Must be placed BEFORE the </body> tag.  Nested code, no need for Layout

      zoho_contactus_form and calendly-widget
      Both contain height/width layout elements in the script.  Please adjust as needed to accommodate the page space

      I'd like to have these two split side by side in columns at the bottom of the page.  The form on the right where the existing one presently resides; the Booking widget in the left of the form.  As close to the same height/width as we can make them for continuity.  However I will let you be the final judge as to their individual frame size.
