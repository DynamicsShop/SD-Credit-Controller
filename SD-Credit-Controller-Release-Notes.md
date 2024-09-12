## SD Credit Controller Releases

### 10.1.4

#### Enhancements

- AppSource App - Update for 2024 wave 2 release. Report Interactions no longer contains a definition for the FindInteractTmplCode function in 2024 wave 2. FindInteractTmplCode function replaced with new functionality.

- AppSource App - The logo in the App was updated to the new logo.

### 10.1.3

#### Enhancements

- AppSource App - New functionality was added to allow bulk deletion of SD Credit Controller Actions. Users can bulk delete by choosing to delete selected or filtered records.

- AppSource App - Links in the About page were updated.

### 10.1.2

#### Bug Fixes

- AppSource App - When creating a follow up action in a filtered view filtered to today's date, the follow up action was created but instantly filtered out of the current view. Users had to reopen the follow up action to enter comments. This was fixed. Now when a follow up action is created in a view filtered to today's date, the follow up action remains open until the user closes it.

### 10.1.1

#### Enhancements

- AppSource App - A change was made to limit the SD ISV Tenant Subscriptions page to display just our SD ISV AppSource Apps and not other SD PTE Apps.

#### Bug Fixes

- AppSource App - A fix was made to an issue where the summary place holder fields were not populating when a reminder email was generated using workflows for a customer a subsequent time with the consolidated email option set to true and the minimum interval set to blank.

- AppSource App - A change was made to the ISV Licence Notification procedure in SD Credit Controller to fix an issue that would raise an error when the language is changed from English to another language.

- AppSource App - An error will raise in the Assisted Setup import if non sequential enum values exist in the imported data. This was fixed.

### 10.1.0

#### Enhancements

- BCv21 App - The Latest ISV Licence Control was added to SD Credit Controller.

- BCv21 App - The Product Activation Page was updated to point to the new CRM URL.

- BCv21 App - The Licence Expiry message/notification was updated to display the App Name.

- BCv21 App - A page was created to display all the Simply Dynamics Apps and subscription details for the tenant.

- BCv21 App - The Licence Message displayed on first install of SD Credit Controller was changed to prompt the user to activate a free trial and to choose Assisted Setup from the Setup Card to create demo data.

- BCv21 App - The links in the About Page were updated to point to new URLs.

- BCv21 App - The ToolTips were updated to look at our new website.

#### Bug Fixes

- BCv21 App - A fix was made to the code for licence key checks on the SD Credit Controller Role Centres. 

### 10.0.0

#### Enhancements

- BCv19 App - The C/AL code base was converted to AL extensions. 

- BCv19 App - The Process Reminder Job which is setup in the Manager Company had quotes around the Parameter Name. These quotes were removed. 

- BCv19 App - Changes were made to the filters in the Blocked and On Blocked cues in the Role Centre. 

- BCv19 App - A small typo was fixed on the SD Credit Controller Managed Companies page. 

- BCv19 App - Changes were made to the HTMP Editor and to the Template Card - the page type was changed to standard dialog, new events were published in the Javascript API to receive content on Change Trigger of document, and the changes are now cached and applied only when "Yes" is pressed on the page.  

- BCv19 App - The SDY CC E-Mail Queue List (43021042, List) was recaptioned so it appears in the Tell Me as SD Credit Controller Email Queue - All. 

- BCv19 App - The Menu groups were tidied up in the Template Card for a Template of Type Word Merge Document. 

- BCv19 App - A Test App was created for AppSource Submission. 

- BCv19 App - Extensions were created on standard Microsoft Dynamics 365 Business Central Permissions for SD Credit Controller objects. 

- BCv19 App - A change was made to make SD Credit Controller features invisible on the extension to the standard Customer Card for Managed Companies. 

- BCv19 App - The actions on the Customer Card extension were reorganised. 

- BCv19 App - The size of the captions in the Detailed Aging Report were increased in size as they were being truncated.  

- BCv19 App - The Issued Reminders Print field was removed from the Workflow Card for Type of Reminder. 

- BCv19 App - Changes were made to the Dimensions FastTab in the SD Credit Controller Setup Card. The Global Dimension 1 Code and the Global Dimension 2 Code fields were removed and the Shortcut Dimensions 1 and 2 were recaptioned to Global Dimensions 1 and 2. 

- BCv19 App - A use Litigation Categories option was added to the SD Credit Controller Setup Card. 

- BCv19 App - The double quotes around the option values of the Parameter String in the SD Credit Controller Job Codeunit were removed and the Customer Running Balances value was updated to Customer Running Balances and sync Ledger Entries. 

- BCv19 App - Some field captions in the Customer Ledger Entries Report were truncated. These field captions were increased in width.  

- BCv19 App - The size of Code fields on SD Credit Controller tables were increased from 10 to 20 characters.

- BCv19 App - A small typo change was made to an action in the Active Repayment Plans list page. 

- BCv19 App - A number of typo fixes were made to Cues in the Activity Groups in the SD Credit Controller Admin Role Centre. 

- BCv19 App - Visual changes were made to the SD Min Controller Role Centre and the SD Min Manager Role Centre. 

- BCv19 App - Visual changes were made to the SD Min Admin Role Centre, the About was removed and typos in cues were fixed. 

- BCv19 App - Visual changes were made to the SD Manager Role Centre, Activity Groups were moved and cues were removed. 

- BCv19 App - A number of typo fixes were made to Cues in the Activity Groups in the SD Credit Controller Manager Role Centre. 

- BCv19 App - A number of typo fixes were made to Cues in the Activity Groups in the SD Credit Controller Controller Role Centre. 

- BCv19 App - The Actions on the SD Credit Controller Customer List page were reordered for ease of use. 

- BCv19 App - Various layout changes were made to the Admin Role Centre and actions were removed or repositioned. 

- BCv19 App - Changes were made to the About Page to display the latest version of the product, the AppSource URL link, the URL link to release notes on GitHub.  

- BCv19 App - Further additional changes were made to our ISV HTML Editor component and the HTML Editor in SD Credit Controller was updated. 

- BCv19 App - Changes were made to the emailing functionality in SD Credit Controller to use the new Email Accounts and  SMTP Connector functionality in standard Dynamics 365 Business Central. 

- BCv19 App - An automatic refresh was added to the Role Centres to update Action Cues.  

- BCv19 App - A column name in the SD Credit Controller Credit Classification List was updated. 

- BCv19 App - A column name in the SD Credit Controller Controllers List was updated. 

- BCv19 App - A typo on the Assisted Setup action prompt was fixed. 

- BCv19 App - The HTTPClient Request field in the Configuration Settings is now switched on by default on install of the product. 

- BCv19 App - The captions of objects were updated for future translation requests. 

- BCv19 App - The E-Mail caption was updated to Email throughout the SD Credit Controller product. 

- BCv19 App - On conversion of SD Credit Controller from C/AL to AL, Templates of Type Email didn't save content. The code was reworked.  

- BCv19 App - Filters were removed on the SD Credit Controller Admin Role Centre as Customers with a Credit Limit less than their Overdue Balance were not showing in the Customers Over Credit Limit cue. 

- BCv19 App - A freeze frame was added to the SD Credit Controller Actions list to include the Completed and Due Date fields. 

- BCv19 App - On conversion of SD Credit Controller from C/AL to AL, when adding members to Teams the count of members on the SD Credit Controller Teams List was not updated. Code was reworked. 

- BCv19 App - The actions and menu action groups on the  SD Credit Controller List page were reordered and regrouped for clarity and ease of use. 

- BCv19 App - Layout changes were made to the SD Credit Controller Customer Detailed Aging Report. Columns were widened and fields were aligned. 

- BCv19 App - Layout changes were made to the SD Credit Controller Customer Ledger Entries Report. Columns were widened and fields were aligned. 

- BCv19 App - The Synchronisation actions on the SD Credit Controller Managed Companies page were reordered. 

- BCv19 App - A typo on an action in the SD Credit Controller Managed Companies list was fixed. 

- BCv19 App - The Email From Address field in the Setup card was not validating for an email address format as per the standard Dynamics 365 Business Central Customer card. Code was added to validate as per standard Customer card. 

- BCv19 App - Changes were made to the SD Credit Controller Setup - Actions were regrouped, renamed, and reordered and a KPI FastTab was added to the card. 

- BCv19 App - The SD Credit Controller Setup was surfaced as a cue action on the SD Credit Controller Admin Role Centre. 

- BCv19 App - The Activate your product page was removed from the Tell Me. 

- BCv19 App - The check for an expired SD Credit Controller Licence was removed from the Role Centre. 

- BCv19 App - Assisted Setup was added to the product. 

- BCv19 App - Changes were made to the Licence Controller functionality to prevent more than one trial activation per product per site.  

- BCv19 App - Name and description fields were increased to 100 characters in length as per the standard D365BC change. 

- BCv19 App - The SD Credit Controllers list was missing from the Admin Role Centre after conversion from C/AL to AL. 

- BCv19 App - Trial license changes to the ISV Licence Controller were added to the product. 

- BCv19 App - Field lengths of standard fields changed in Dynamics 365 Business Central warnings of field length changes were fixed. 

- BCv19 App - Fixed an issue where an error was raised when sending emails from the Email Queue where the Customer had additional special characters in their name.  

- BCv19 App - Permission sets for SD Credit Controller were modified to remove SD Credit Controller tables that were removed from this version of SD Credit Controller.  

- BCv19 App - The My Personal cue activity groups were removed from the SD Credit Controller Admin Role Centre. 

- BCv19 App - Changes made to add Credit Controller Dimensions to the SD Credit Controller Controllers list page in an earlier product version were reverted.  

- BCv19 App - Some minor changes were made to the SD Credit Controller Admin Role Centre. 

- BCv19 App - Change code to rename the SD Credit Controller Customer Ledger Entry Company Name on rename of the Company in standard Dynamics 365 Business Central. 

- BCv19 App - The Licensing functionality was rewritten to ensure that the Licence Expiry Date prompts with 5 days to go was not stopping functionality.  

- BCv19 App - Functionality around the syncing of dimensions on the SD CC Customer Ledger Entry was reworked again. 

- BCv19 App - Functionality around the syncing of dimensions on the SD CC Customer Ledger Entry was reworked.  

- BCv19 App - Permission sets were created for the product. 

- BCv19 App - The Company Hierarchy FactBox on the SD Credit Controller Managed Companies list was not updating correctly.  

- BCv19 App - On conversion of SD Credit Controller from C/AL to AL the code to send emails from the Email Queue was reworked. 

- BCv19 App - On conversion of SD Credit Controller from C/AL to AL the code to view file attachments from the Email Queue was reworked. 

- BCv19 App - On conversion of SD Credit Controller from C/AL to AL the code to view file the email body from the Email Queue was reworked. 

- BCv19 App - On conversion of SD Credit Controller from C/AL to AL the code to create the place holders in the Template Card was reworked. 

- BCv19 App - The standard event 'OnMoveGenJournalLine' was moved to CodeUnit 12 and the SD Credit Controller code was updated to reflect this change. 

- BCv19 App - An extension was created on the standard Customer Card to replace the SDY CC Customer Card. 

- BCv19 App - The Word Merge functionality in SD Credit Controller was converted to AL.  

- BCv19 App - The Customer Blocked fields in the SDY CC Action and the SDY CC Credit Classification tables were changed to a type of Enum. 

- BCv19 App - On conversion of SD Credit Controller from C/AL to AL the code to display the All Incomplete Actions of the Role Centres was reworked. 

- BCv19 App - On conversion of SD Credit Controller from C/AL to AL the code to create and view notifications in SD Credit Controller was reworked. 

- BCv19 App - The SD Credit Controller Customer Ledger Entry Document Type field was changed to a type of Enum to reflect the changes in standard Dynamics 365 Business Central. 

- BCv19 App - The SD Credit Controller product was readied for AppSource submission. 

- BCv19 App - Tooltips were added to the SD Credit Controller pages. 

- BCv19 App - The code on the SD Credit Controller Managed Companies list was updated to use a new control add-in rather than the standard Microsoft ping pong dll. 

- BCv19 App - Changes were made to the code for Workflow functionality. 

- BCv19 App - The CC to Credit Controller and CC to Email From fields were added to the Email Options FastTab on the Workflows. 

- BCv19 App - Translation files were added to the product. 

- BCv19 App - Additional name and description fields were increased to 100 characters in length as per the standard D365BC change. 

- BCv19 App - The HTML Editor was updated to the latest version of our ISV HTML Editor component. 

- BCv19 App - Charts were removed from the product. 

- BCv19 App - Objects were renamed to have a prefix of SDY. 

- BCv19 App - The Application Area and Usage Category properties were added to the SD Credit Controller pages and reports. 

- BCv19 App - SD Credit Controller Licensing Checks were added to the Code. 

- BCv19 App - Additional C/AL changes made to the standard product after conversion to AL began were converted and added to the AL code base. 

- BCv19 App - The Sales Person Code was added to the SD-CC Customer table and displayed on the SD-CC Customer List page. 

- BCv19 App - Additional changes were made to our ISV HTML Editor component and the HTML Editor in SD Credit Controller was updated. 

- BCv19 App - Customer Ledger Entry Detail Report header values were formatted to correct currency formatting. 

- BCv19 App - The performance issue fix when batch posting Sales Invoices was ported to all code bases of SD Credit Controller. 

#### Bug Fixes

- BCv19 App - For Repayment Plans the Generate Journal Lines action was not picking up the Document No. from the No. Series specified in the Journal Batch Setup.

- BCv19 App - An error was raised when processing Workflows of Type Email that had the CC to Credit Controller option switched on and a Credit Controller did not exist for the Customer.

- BCv19 App - An error was raised when users clicked on the "Your Licence has Expired" message. 

- BCv19 App - In the Template Card, choosing the Output Type blanked out the Filename entered in a Template of Type Word Merge Document. 

- BCv19 App - The back arrow in the Action Card had to be pressed three times to exit the card when the content of HTML editor was edited. 

- BCv19 App - The standard Cash Receipt Journal was not opening after generating journal lines for the Repayment Plan. 

- BCv19 App - A fix was made to sync Managed Companies were managed companies that were removed from the SD Credit Controller Manager Companies list were not being cleared from the Companies synchronisation routine. 

- BCv19 App - Fixed an Document No. error raised in the SDY CC Active Repayment Plans when generating journal lines. 

- BCv19 App - Users were unable to cancel out of creating a new Action. 

- BCv19 App - Remaining issue updating the Managed Company FactBox on the SD Credit Controller Managed Companies list were resolved. 

- BCv19 App - Fixed an issue where the standard Customer Card could not be opened in a Company that was Managed by another Company. 

- BCV19 App - Updated the message shown in a Managed Company when a user access SD Credit Controller functionality to show the Manager Company Name.  

- BCv19 App - When adding a placeholder field to the subject or body of the Template card for Type Email, users had to click to exit the page a number of times before the page would close. 

- BCv19 App - Fixed an issue where Subject field in an Email Template Card was not editable. The Templated Card was reworked. 

- BCv19 App - The call to the Assisted Setup was not working. 

- BCv19 App - The invoice summary fields in in the Email Body on the Template Card was including non-document invoices on the email. This was fixed. 

- BCv19 App - Fixed an issue where when email workflows were generated, the CC email was not generated. 

- BCv19 App - The Html Editor Content was not visible when the user exited and then reopened the Email Template Card. 

- BCv19 App - Updated SD Credit Controller to use the Email Accounts and added an assist-edit to the Email Account field on the SD Credit Controller Setup. 

- BCv19 App - Fixed an issue where a Workflow that was setup to generate only emails with attachments did not attach documents to the generated email. 

- BCv19 App - The place holder fields for CC Credit Contact Name and CC Credit Controller Name were not showing in a generated email although they were defined in the Template. 

- BCv19 App - The Credit Controller Customer Ledger Entry table was not syncing from the Managed Companies on drilldown to the Running Balance fields on the SD Credit Controller Customer List. 

- BCv19 App - The Calculated Date on Running Balances was not updating.  

- BCv19 App - The Product Activation page was changed to disable the Activate button by default unless the Product Key is entered. 

- BCv19 App - The Company Hierarchy FactBox on the SD Credit Controller Managed Companies list was not populating after conversion from C/Al to AL. 

- BCv19 App - Fixed an issue where an error was raised when sending emails from the Email Queue where the Customer had special characters in their name. 

- BCv19 App - The SD Credit Controller Customer Ledger Entry was not synced for Managed companies into the Managed Company. 

- BCv19 App - Some of the place holder fields in the Template card were showing with empty names and some other place holders were missing from the place older list. 

- BCv19 App - An error was raised when running the Customer Detailed Aging report.  

- BCv19 App - An error was raised when running the Customer Detailed Aging Excel report. 

### 9.3.15

#### Bug Fixes

- An error was raised when sending emails that had special characters in the Customer Name from the SD Credit Controller Email Queue. 

### 9.3.14

#### Enhancements

- Functionality around the syncing of dimensions on the SD CC Customer Ledger Entry was reworked. 

- Various changes were merged into the standard ISV release. 

- Additional fixes were made into the standard ISV release.

- Placeholders were added to the Summary Invoice List.

### 9.3.13

#### Bug Fixes

- A fix was made to an error raised when trying to modify a field on the Credit Controller Card.

### 9.3.12

#### Enhancements

- Functionality was added to add dimension codes to the SD-CC Credit Controller table. Credit Controllers now have dimension codes surfaced on the SD-CC Credit Controller List. Two Credit Controllers can't have the same dimension combinations. Workflows were modified to filter on Dimension and Credit Controller. The Credit Controller Role Centre was also modified.

- A new Litigation Category table was created. When a SD CC Customer Ledger entry is flagged as in dispute, a Litigation Category can be chosen.

- Dimension Filters were added to the SD-CC Cust. Ledger Entry List Page.

- A new function was created to update SD CC Cust Ledger Entries with Dimensions.

- Dimension fields were added to the SD-CC Cust. Ledger Entry LP page the SD-CC Cust. Ledger Entry LT page.

- Dimension fields were added to the SD-CC Cust. Ledger Entry table.

- Ten Dimension fields were added to the SD CC Company List page.

- Made a change to change the Workflow Dimensions on change of Credit Controller Dimensions.

#### Bug Fixes

- Fixed an issue in the reminder workflow actions where actions were only being created for one document and not for multiple documents.

- Fixed an issue where an error was raised on customer record modification in a stand-alone company. An error was raised that it was a managed company.

- Updated missing captions on fields.

- Fixed issues in Page 43021018 SD-CC Cust. Ledger Entry List with filtering the subpage. Page Type was changed to card type instead of list part.

### 9.3.11

#### Enhancements

- Made a change to allow placeholder fields in the subject of the email template.

- Introduced functionality to create multiple actions (an action per invoice) for consolidated emails.

- To increase performance, keys were added to the SD CC Customer Action table and the SD CC Action table.

- Created functionality to allow users to preview and edit emails in SD Credit Controller.

- For consolidated emails, a change was made to add a list of the invoices attached to the email.

- A change was made to workflow email attachments to parameterise the name of the invoice pdf attached to the email.

- Extra filters were added to certain flowfields on the SD-CC Customer Card.

- To improve performance, keys were added to certain tables in SD Credit Controller.

- The Workflow logic and Multi-Company functionality logic was reviewed. 

- Changes were made to the SD-CC Sales - Invoice Copy report to allow the report to print for a multi-company record in the SD-CC Ledger Entries list.

#### Bug Fixes

- Fixed an issue when printing Documents for multiple companies in the SD CC Ledger Entry Page.

- Fixed an issue to allow viewing and/or printing of documents for multiple companies from the SD-CC Ledger Entry list.

### 9.3.10

#### Enhancements

- Further UI changes were made to the SD-CC Customer List.

- Added the Sales Person Code to the SD-CC Customer List page.

- Added extra columns from the standard NAV Customer page to the SD-CC Customer List page.

- On the SD-CC Workflow List, the "Process Workflow" Action was renamed to "Process Workflows".

- Made a change to how uncalculated records in the SD-CC Customer List are highlighted.

- Added a freeze pane and reordered, renamed and regrouped Actions on the SD-CC Customer List page.

- Added the About Action to the SD-CC Setup Card and removed duplicate Action.

- In the SD-CC Performance Rating List the "Min Period (LCY)" column was renamed to "Min Amount (LCY) in Period" and the . Rename the "Max Period Overdue %" column was renamed to "Max Overdue % in Period".

- In the SD-CC Setup Card reordered and renamed some Actions and removed the standard NAV Links and Notes Actions..

- Made a number of UI changes in the SD-CC Customer List, regrouping and reordering Actions and creating new Tabs.

- Increased performance in SD-CC Customer List. Allow users to Auto Highlight Uncalculated Customer Records when the Page is opened or to choose the new Highlighted Uncalculated Action.

- Reworked the code for Emailing Reminders in the Workflows in NAV 2018 and NAV 2017 code bases. 

- Added functionality to allow users select the Customer E-Mail address when setting up Workflows of Type E-Mail.

- Fixed an issue raised on posting transactions when recurring payment plans exist in the NAV 2016 and NAV 2017 build.

#### Bug Fixes

- Fixed an issue in the SD Credit Controller Role Centre where the My Blocked Customers cue was showing an incorrect count.

### 9.3.9

#### Enhancements

- Updated the Simply Dynamics Control Add-ins in the Credit Controller Codeunits.

- Reviewed and resolved the Control Add-in error raised when running the Credit Controller Role Centre in the NAV 2016 Build.

- Refactored the Control Add-ins to the Simply Dynamics Namespace in NAV 2016, NAV 2017 and NAV 2018 code.

- Created a new key on the SD-CC Customer table to improve performance when users are navigating up and down the SD Credit Controller Customer List.

- Changes made to calculations in the Credit Activity Cue, Customer Manager Codeunit and Payment Performance Manager Codeunit.

- Refactored the control add-in namespace to Simply Dynamics.

- The Readme file was updated. 

#### Bug Fixes

- Fixed an issue raised on posting transactions when recurring payment plans exist in the NAV 2018 build.

- Ported SD-CTCR to a NAV2018 code base.

### 9.3.7

#### Enhancements

- Made a change to SD-CTCR Jobs so that on re-set of the SD-CTCR Jobs the userid is being set to a new field Job Admin User ID.

#### Bug Fixes

- Fixed compilation errors in the SD-CC Event Manager and SD-CC Merge Manager CodeUnits.

- Fixed an issue in the Add-In Installer.

- Fixed a permission error received on TableData SD-CC Setup when posting a Purchase Invoice.

- Made a change to SD-CTCR Jobs so that on re-set of the SD-CTCR Jobs the userid is being set to a new field Job Admin User ID.

### 9.3.6

#### Enhancements

- Refactored the Cebuella.Navision.Control.HtmlEditor to latest released SimplyD.Control.Suite.Html Editor

- Refactored the Cebuella.Navision.Control.Chart to latest released SimplyD.Control.Suite.Chart

- Updated the About Page to reference www.dynamicsshop.com

- Updated the caption on the SD-CC Job Queue Entry Card and SD-CC Job Queue Entry List.

#### Bug Fixes

- Fixed an issue where editing an entry in the SD-CC Job Queue Entry Card re-sets the Object ID to Run to the SD-CC Job Processor Codeunit.

### 9.3.5

#### Enhancements

- Made a change to verify if the Company is valid on CLE sync.  If the company is not valid, the sync'd record is removed.

- A change was made to ignore any reminders that were already created.

- Made a minor change to the logic in SD-CC Workflow Manager.

- Made a change to the SD-CC Workflow Manager codeunit to calc the Reminder Posting Date with reference to the Overdue Deadline.

#### Bug Fixes

- Fixed an issue where sorting based on a flowfield cannot be done when determining the credit controller with the least amount of customers assigned.

### 9.3.4

#### Enhancements

- Made changes to tracking reminder generation. If a reminder exists for the customer, do not create another. Reminders would either have to be issued or deleted.

- Job Queue Processes were split into individual codeunits.

#### Bug Fixes

- Resolved an issue where syncing the Ledger Entries was not clearing.

### 9.3.3

#### Enhancements

- Allowed the user to create an action once a reminder has been issued.

- Gave the user an option to issue the reminders on creation.

- Change made to prevent generation of duplicate reminders.

- Removed the minimum value from Reminder Level.

### 9.3.2

#### Enhancements

- Changes ported to 2017.

- Exclude records from the overdue cues where the overdue balance is zero.

- Changed functionality to allow an option on the email reminder workflow to create a closed action for the customer/CLE when the email is successfully delivered to the smtp server.

- Allow the email reminder workflow to specify getting the contact email address for the CLE Document.

#### Bug Fixes

- Fixed an issue where the Overdue/Balance was not matching up to the flowfield cue.

### 9.3.1

#### Enhancements

- Added window handling to running balances calculations.

- Removed try functionality from notifications.

- Optimised CLE Syncing.

- Implemented the Simply Dynamics ISV generic export/import module.

- Made the Reminder Level field mandatory only for reminder workflows.

- Enhanced the Role Centre Activity Cues.

### 9.3.0

#### Enhancements

- When the Calculate Running Balances is complete, a message is now raised to indicate to users that the Running Balances have successfully calculated.

- Html Editor is now web client compatible.

- All dlls were stamped with CfMD meta data.

- The Readme file was updated. 

- Fixed compilation issues. 

- Re-ordered pages.

- Changes ported to NAV 2017.

- Change made to ensure that when pressing enter on the SD CC Customer List, the SD CC Customer Card should open.

- Updated XML Ports for import of setup data.

- Updated XML Ports for export of setup data.

- Created a pared back version of the Manager Role Centre.

- Created a pared back version of the User Role Centre.

- Created a pared back version of the Administrator Role Centre.

- Created a version of the SD CC Manager Role Centre with horizontal and vertical scrollbars removed. 

- Updated HTML Ports to import and export Templates and Workflows for Setup Import/Export and Action and Action Comments for Data Import/Export.

- Added functionality through an exposed event, OnAddContactToEmailReminder,  to allow users to exclude Contacts from communications generated by Workflows.

- Added Payment Terms as a filter to the Workflows.

- Created a new Report (with option to export to Excel) to generate Customer Ledger Entries that are marked as In Dispute and to display associated Actions based on selected filters.

- Updated the HTML Editor to new CfMD Ready Control Suite. (2016/2017 versions)

- Updated Charts to new CfMD Ready Control Suite. (2016/2017 versions)

#### Bug Fixes

- Fixed a bug in the Workflows where no attachments were generated when the workflow was run with word merge document.

- A fix was made to prevent creation of actions for the same customer/document no combination if there is an open action already created with the same action type. 

- Removed the redundant actions from the SD CC Customer List Page.

- Fixed an issue where an action to create a new customer on the Credit Customer List page raises an error.

- Fixed an issue where importing the Setup Data raises an error due to XML configuration.

- Updated codeunit to add indirect permissions to the SD CC Customer Pre Payments.

### 9.2.1

#### Enhancements

- Rearranged the Admin/Manager Role Center.

- Added a description to the Triggers FastTab in the Workflow Card.

- Changed the layout of the SD-CC Cust Ledger Entry Detail Report.

- Mark Expired records on the SD-CC Recurring Payment List so the user will notice Expiration is overdue.

- When generating a Workflow action check for a unique constraint.

- Change made to allow users to select workflow option to only send mails if emails have attachments generated (i.e. Reminders).

- When a Company is assigned as a Managed Company, clear out any extended data (Customer/CLE/Actions).

- Removed un-needed sections from the Customer Detailed Aging Report's request page.

- Created new Functionality to create a link to the custom Gen Journal Template from the Repayment Journal.

- Improvement made to the 'Create Actions for Invoices' job - new actions should only be created for Invoices that have become overdue since the job was last run.

- The functionality for the 'Create Actions for Invoices' Job was reworked. 

- Made a change to show the Calculate Running Balance message box while the procedure is running.

- The option in the Workflows was changed from E-Mail Reminder to E-Mail. 

- In the SD-CC Team List the prompt to rename the record on creation of a new team record was removed.

- The Readme file was updated. 

#### Bug Fixes

- Fixed an issue in the syncing of Role Centre Cues.

- Added the  SD CC Customer field to the Workflow Report ID 43021001. 

- Fixed an issue in the Workflow Card when verifying merge documents.

- Reworked the code to sync the standard CLE into the SD Credit Controller CLE. 

- Fixed issue where the Workflow Type of Reminder will create blank Reminder records even if there is no data pending for Reminders.

- Fixed issue where the Workflow functionality was generating data for Companies which are not set as Credit Control Companies.

- Fixed an issue where the Customer Ledger Entry Detail Report was not generating the correct summary data.

### 9.2.0

#### Enhancements

-  Optimised Action Comments Close. 

-  W1 Release.

#### Bug Fixes

- For Companies with no Credit Controller setup or for Managed Companies, fix issue where message raised that Credit Classification table is not updated.

### 9.1.0

#### Enhancements

- Updated SD-CC Workflow Card promoted 'Templates' Action to appear on Home tab. 

- On the SD-CC Workflow List Page update the record style colour to red if the Inactive field is checked. 

- Implement check if duplicate record exists on SD-CC Credit Classification Page for Payment Terms Code, Payment Method Code combination. 

- Removed the Action 'Edit List' from the SD-CC Team List Page.

- Created a new factbox 'Team Details' on SD-CC Team List Page to display all Team Members assigned to the Team. 

- Added a confirmation message when adding a Credit Controller to multiple Teams.

- Added a new lookup 'View Credit Controllers' Action on the SD-CC Team List Page. 

- Surfaced the Template Code on the SD-CC Workflow List Page. 

- Added an Action Item to filter on Ledger Entries the My Incomplete Actions List on the Role Centres. 

- Allow the User to specify the number of days before highlighting a customer record when not calculated (Overdue balance) in X days. 

- Create an Aged Account Receivables Report that can be run over multi companies. This report is run for Customers that have been setup in SD CC and who have run the Aged Analysis. 

- In the SD-CC Action Card Page on creation of a Follow Up Action, update the comment from the parent Action. 

- Added Page Actions from the SD-CC Customer List to the SD-CC Customer Card. 

- Surfaced Amount and Remaining Amount on Action Card and Action List. 

- Added a new field on the SD-CC Payment Performance table to stamp the date the Payment Performance was calculated. 

- Created a routine to close Outstanding Actions against a Ledger Entry for Ledger Entries that have been paid/closed. 

- Added functionality to copy an Action logged against one CLE to other selected CLEs. 

- Added a Mail Queue Attachment factbox. 

- Added Preview to Report option on Workflow. 

- Change to show Overdue Actions as overdue on due date plus one day. 

- Created a new Report to use to generate email attachments for reminders that are already issued. 

- Change to SD-CC Customer List to show 0.00 in the Running Balance and Overdue Balance if no value is calculated. 

- Migrated Action Comments to HTML Control. 

- Updated Workflow process to handle the new HTML Action Comments. 

- Updated the Action Card to use the HTML control and process. 

- Updated the Template Card to use the HTML control and process. 

- Added functionality to allow email consolidation of Workflows. 

- In the SD-CC Setup Card - rename the 'Auto close actions' Action to 'Auto Close Actions'. 

- Added functionality to attach a copy of Invoices to the Reminders when sent via Email to the Customer. 

- Added functionality to check that reports for Workflow email Reminder attachments must have the SD-CC Cust. Ledger Entry table as the report data root item. 

- Created functionality to un-assign a Customer from a Credit Controller. Action surfaced on SD-CC Customer List Page. 

- Created a W1 release. 

- Created a 2017 release.

#### Bug Fixes

- Fixed syncing issue in Page SD-CC Customer List for overdue customer with all entries of closed payments. 

- Fixed issue where running the Create Actions for Overdue functionality is not creating Actions for all overdue ledger entries in the Managed Companies. 

- Fixed issue where when running the Calculate Performance for Selection on one newly created Customer, a message 'Object ID not found' was raised. 

- Fixed incorrect Page Action Name on page SD-CC Customer List. Page Action 'Unassign to Credit Controller' has incorrect spelling in word 'Uassign'. 

- Fixed issue where the SD CC Job errored out due to an issue with Auto Close Action function. 

- In the SD-CC Company List renamed Actions. Renamed "Customer Sync. Fields" to "Customer Sync Fields" and "Sync Customer Ledger entries" to "Sync Customer Ledger Entries". 

- SD-CC Company List was missing the Company Hierarchy Fact Box from Version 8.1.0 of SD Credit Controller. 

- While in a CLE for a Managed Company, on selection of New Repayment Plan in the Action Card, raise a message to inform the user that they are creating a Payment Plan and that payments need to made within the Managed Company. 

- Fixed issue where for the Workflows with a Template Type of Email, the placeholders were not updating in emails.
 
- Fixed synchronisation issue with promised amounts on Action Card not updating on CLE. 

- Fixed an issue where closed entries in a Managed Co that were marked as in dispute were still showing, although closed, in the SDCC CLE in the Master Co.

### 9.0.1

#### Enhancements

- Created a Mail Queueing System to handle E-Mail Reminders. 

- Added Cues to the Controller and Team Role Centres to filter on Repayment Plans. 

- Created a running balance process for Job Queues. 

- Upgraded SD Credit Controller to use the new Simply Dynamics Charts. 

- Created a new Chart to show the Total Overdue Balance per Team. 

- Created an SD CC Administrator Role Centre. 

- Filtered the My Incomplete Actions on the CC Manager Role Centre by Team and added an extra column to the My Incomplete Actions List for the Credit Controller whose Action this is. 

- Created new functionality to allow for Teams of Credit Controllers to be setup. 

- Created new functionality for Credit Controller Workflows. Created Email Templates, created Mail Merge Templates - Mail Merge, Attachment, Report, created Email Logging. 

- Auto create an Action for Invoices when an Invoice becomes Overdue. The Action is assigned to the same Credit Controller User as the Customer is assigned to. 

- Allow All Credit Controllers to use the same common, single, email address as their Credit Controller contact email address. 

- Created a new SD Credit Controller CLE Report. 

- In the SD Credit Controller Action Card, a new Action was added to ‘Print Preview' or display the details of the CLE that the Action is logged against. 

- Added the standard Microsoft Dynamics NAV option "Navigate" to the SD Credit Controller Cust. Ledger Entry List. 

- Created new Role Centre Cues - Overdue Amount; Balance; Overdue on Blocked; Amount in Dispute; a count of the Customers that are over their Credit Limit. 

- Optimised the performance of the SD Credit Controller Customer List Page. 

- Made improvements to the SD Credit Controller Recurring Payment Dialog - updated the 'Document Type' field to have an initial value set to the 'Payments' option; updated the 'Amount' field caption to point the user to enter the value in negative. 

- Added the Open/Closed Actions to the Customer Ledger Entries on the SD Credit Controller Customer List.

#### Bug Fixes

- Fixed an issue where the Role Centre Cues were not filtering correctly. 

- Fixed an issue where the ‘My Overdue Customers’ Cue on the Role Centre was showing a 0 count of the Overdue Customers where Overdue Customers exist. 

- Fixed an issue where the ‘Promised Amount’ and ‘Promised Date’ fields on the the Action Card were not updated on the associated Customer Ledger Entries. 

- Fixed an issues where the Single Company Balance, Multi Balance and Multi Overdue, were not calculating correctly. 

- Fixed an issue on the SD-CC Customer Card Page where the Multi-Balance(LCY) @date and Multi-Overdue (LCY) @date were displaying correctly in the General FastTab but not on the Customer Details FactBox. 

- Made a change to the SD Credit Controller logic to verify that the Customer exists on Payment Recalculation.

### 9.0.0

#### Enhancements

- Added All Incomplete Actions and Active Repayment Plans to the Role Center. 

- UI improvements made to the Customer List. Currency was added to the Aging FactBox. Removed Managed Company Hierarchy FactBox. 

- Renumbered Objects. 

- Reviewed all Cue counts. 

- Reviewed Code. 

- Created Help Files. 

- Reviewed Role Centre UI and Role Centre Actions. 

- In the SD-CC Action List Page, the Customer Name for the Customer was displayed. 

- In the SD-CC Action Card Page, the Customer Name for the Customer was displayed.
 
- An option was added to create notifications automatically on creation of an action. 

- In the Active Repayment Plans List, the Customer Name was displayed. 

- In the Credit Controller Setup Page, the Categories Action was surfaced in the Home Tab in the Ribbon, as per the other classifications. 

- Created a message to notify users that setup configuration for charts must be completed. 

- Updated overdue responsibility check calculation. 

- Created a new field Overdue @ to the Customer Card. 

- Added new fields on SD-CC Action table, Promised Amount, Promised Date, and Company Name to the SD-CC Action List Page. 

- Added Balance and Balance (LCY) fields to the SD-CC Customer List Page. 

- Added new fields to the Customer List Page.

- Made a change to the Setup UI. Moved Sync Manager to Sync Companies. 

- In the CC Recurring Payment List Page, the Document No field was hidden.

#### Bug Fixes

- Fixed an error raised when selecting the Customers field in the Credit Controllers Details FactBox. 

- Fixed an error raised when selecting the Verify Overdue Responsibilities Actions from the SD-CC Credit Controller List Page. 

- Fixed an error raised when running the SD-CC Job Processor Codeunit.
 
- Fixed an issue whereby creating a New Customer auto-assigns all Customers a Credit Controller.

- Fixed an unexpected navigational behaviour issue when creating a new Customer record in SD Credit Controller.

- In the SD Credit Controller Customer List Page - Open Entries - the Sync Date Time was not updating. 

- In the SD-CC Credit Controller List Page, rename Verify Overdue responsibilities to Verify Overdue Responsibilities.
 
- In the SD-CC RC, My Overdue Customers Cue, on drilldown through the Cue, the list is not filtered to Overdue Customers. 

- In the SD-CC Role Centre, in the My Blocked Customers Cue, on drilldown through the Cue, the list is not filtered. 

- In the SD-CC RC, Unassigned Customers Cue, the Cue has a 0 count but on drilldown all customers with a Credit Controller assigned are displayed.
 
- If there is no record in the Credit Controller Setup Page, an error is raised when the Role Centre (Manager Role Centre) is opened.

- In the Actions List, Action Details Fact Box, there is a spelling mistake. Customer Replayment should be Customer Repayment. 

- In the Recurring Payment table, a blank record was inserted on selection of New Repayment Plan Action. 

- Cannot open the SD CC Cust Card if customer assigned a Credit Controller that has a value in the Overdue Responsibility (LCY) and the Customer balance greater than the Overdue Responsibility (LCY).
 
- Fixed an issue in the About Page.
 
- When navigating through the menus on the navigation pane, message was raised that performance history must be set. 

- Promised Amount and Date on CLE should not be updated when CLE Closed. 

- Reviewed the SD-CC Action List Page Behaviour. 

- The Performance Rating in the Customer card was not updated with the last Performance rating calculation. 

- Fixed an issue in the My Credit Customers Page where the Actions list page was not filtered properly. 

- The Create New Action in the ‘Actions’ page does not call page to create a new action.

- Fixed an issue whereby an Action created from Entry level in the New Action card does not validate the Cust. Entry No into the field.

- In the Role Centre, the Cue fields Promised Amount and Promised Amount this week only filter the complete actions whereas the filter should be on open actions. 

- Fixed an error raised in Repayment Plans when posting cash receipt journal line generated from recurring journal with a 1W frequency where the current posting date based on frequency is lower then Expiration Date. 

- In the Company Synchronisation display a message that the Synchronisation is finished.

- Fixed issue in Balance Due calculation.


### 8.1.0

#### Enhancements

- Created Promised Payments functionality. Promised Amount and Promised Date. 

- Added Ageing FactBox to the SD Credit Controller Customer Ledger Entries page.
 
- Added Overdue Actions Cue to the Role Centre. 

- Added Repayment Plans Overdue Cue to the Role Centre. 

- Display the amount of Actions assigned to a Customer in the Credit Controller Customer List. 

- Create follow up Action on completion of an Action. 

- Auto close action on payment of transaction. 

- Do not allow access to the SD Credit Controller module if the user is in a Managed Company. 

- Created an additional Role Centre for the Credit Controllers. 

- Created About Dialog page. 

- Removed Report Inbox from the Role Centres. 

- Surface Repayment Plans Actions.
 
- Surfaced Credit Controller field on the All Credit Customers page.
 
- Enhanced Customer assignment to Credit Controllers. 

- Unable to assign Credit Category Code to a Customer in the Credit Controller Customer page. 

- Credit Categories Page surfaced on SD Credit Controller Setup page.
 
- Actions Due this Week’ are highlighted with a style to highlight Actions due. 

- Changes to SD Credit Controller Action functionality.

#### Bug Fixes

- Drilling down on the Customer Cues in the Role Centre records after first import of objects raises an error regarding the Credit Controller Setup. 

- Cannot drill through on some of the Cues in the Role Centre that have a count of 0. 

- Navigation through menus on navigation pane in the Role Centre records after first import of objects raises an error regarding the Credit Controller Setup. 

- Entering a value into the Performance Period field on the Credit Controller Setup, updates the performance without needing a value in the Performance History Length field.

- The count on the My Blocked Customers Cue, in the Role Centre, doesn't correspond to the count of the Blocked Customers on drill through to the list page of My Blocked Customers. 

- The length of the Bank No. field on the Repayment journal is incorrect (too long). 

- Error message raised on posting of Cash Receipt Journal. 

- The My Blocked Customers Cue in the Role Centre is not filtering correctly. 

- Recurring Journal posting with multiple lines and with different recurring frequencies. 

### 8.0.0

#### Enhancements

- Initial release. NAV 2016 complete re-write of SD Credit Controller. 

- Created Customer Sync fields and associated functionality. 

- Created Credit Controller Customer table, pages and associated functionality. 

- Created Credit Category table, pages and associated functionality. 

- Created Credit Controller table, pages and associated functionality. 

- Created Credit Classification table, pages and associated functionality. 

- Created Risk Category table, pages and associated functionality. 

- Created Credit Controller CLE table, pages and associated functionality. 

- Created Payment Performance table, pages and associated functionality. 

- Created Recurring Payment table, pages and associated functionality. 

- Added an Action to navigate to Standard NAV Reminders. 

- Created Aged Debt functionality. 

- Created Credit Controller Action table, pages and associated functionality. 

- Created synchronization functionality from parent company to child company. 

- Created Credit Controller Setup table, pages and associated functionality. 

- Created Credit Controller Company table, pages and associated functionality. 

- Created Credit Controller Role Centres, Cues, Graphs, Factboxes.

### 7.0.0

#### Enhancements

- Basic Table and UI layout changes to Setup, Credit Controllers, Customers, Transactions, Risk Groups, General Categories, Credit Status. 

- Take existing codebase and rebuild for Nav2013R2. 

- Remove the AddIn folder. 

- Code refactoring and rebuild. Clean up and refactor the Codeunits. 

- Add Average Debtor Days to SD Credit Controller and include in Aged Debt calculations. 

- Add VIMA Verification to Credit Controller customer record. 

- Communications. Ability to send Email, SMS, and Phone using contact details. Communications logged on the Credit Controller Communications Log table. 

- Actions. Allow to copy an Actions Comment to the Customer Comments table. 

- Approvals of Sales Orders. If Sales and Receivables Setup has a credit warning, then create an entry in the SD Credit Controller Approval Entry. 

- Create a Worksheet for SD Credit Controller.

- Review UI.

