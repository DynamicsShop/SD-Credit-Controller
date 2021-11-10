## SD Credit Controller Releases

### 9.3.14

#### Enhancements

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

#### Bug Fixes

- Fixed an issue raised on posting transactions when recurring payment plans exist in the NAV 2018 build.

- Ported SD-CTCR to a NAV2018 code base.

### 9.3.7

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

- Re-ordered pages.

- Changes ported to NAV 2017.

- Change made to ensure that when pressing enter on the SD CC Customer List, the SD CC Customer Card should open.

- Updated XML Ports for import of setup data.

- Updated XML Ports for export of setup data.

- Created a pared back version of the Manager Role Centre.

- Created a pared back version of the User Role Centre.

- Created a pared back version of the Administrator Role Centre.

- Updated HTML Ports to import and export Templates and Workflows for Setup Import/Export and Action and Action Comments for Data Import/Export.

- Added functionality through an exposed event, OnAddContactToEmailReminder,  to allow users to exclude Contacts from communications generated by Workflows.

- Added Payment Terms as a filter to the Workflows.

- Created a new Report (with option to export to Excel) to generate Customer Ledger Entries that are marked as In Dispute and to display associated Actions based on selected filters.

- Updated the HTML Editor to new CfMD Ready Control Suite. (2016/2017 versions)

- Updated Charts to new CfMD Ready Control Suite. (2016/2017 versions)

#### Bug Fixes

- Fixed a bug in the Workflows where no attachments were generated when the workflow was run with word merge document.

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

- Made a change to show the Calculate Running Balance message box while the procedure is running.

- In the SD-CC Team List the prompt to rename the record on creation of a new team record was removed.

#### Bug Fixes

- Fixed an issue in the syncing of Role Centre Cues.

- Fixed an issue in the Workflow Card when verifying merge documents.

- Fixed issue where the Workflow Type of Reminder will create blank Reminder records even if there is no data pending for Reminders.

- Fixed issue where the Workflow functionality was generating data for Companies which are not set as Credit Control Companies.

- Fixed an issue where the Customer Ledger Entry Detail Report was not generating the correct summary data.

### 9.2.0

#### Enhancements

• Optimised Action Comments Close. 
• W1 Release.

#### Bug Fixes

• For Companies with no Credit Controller setup or for Managed Companies, fix issue where message raised that Credit Classification table is not updated.

### 9.1.0

#### Enhancements

• Updated SD-CC Workflow Card promoted 'Templates' Action to appear on Home tab. 

• On the SD-CC Workflow List Page update the record style colour to red if the Inactive field is checked. 

• Implement check if duplicate record exists on SD-CC Credit Classification Page for Payment Terms Code, Payment Method Code combination. 

• Removed the Action 'Edit List' from the SD-CC Team List Page.

• Created a new factbox 'Team Details' on SD-CC Team List Page to display all Team Members assigned to the Team. 

• Added a confirmation message when adding a Credit Controller to multiple Teams.

• Added a new lookup 'View Credit Controllers' Action on the SD-CC Team List Page. 

• Surfaced the Template Code on the SD-CC Workflow List Page. 

• Added an Action Item to filter on Ledger Entries the My Incomplete Actions List on the Role Centres. 

• Allow the User to specify the number of days before highlighting a customer record when not calculated (Overdue balance) in X days. 

• Create an Aged Account Receivables Report that can be run over multi companies. This report is run for Customers that have been setup in SD CC and who have run the Aged Analysis. 

• In the SD-CC Action Card Page on creation of a Follow Up Action, update the comment from the parent Action. 

• Added Page Actions from the SD-CC Customer List to the SD-CC Customer Card. 

• Surfaced Amount and Remaining Amount on Action Card and Action List. 

• Added a new field on the SD-CC Payment Performance table to stamp the date the Payment Performance was calculated. 

• Created a routine to close Outstanding Actions against a Ledger Entry for Ledger Entries that have been paid/closed. 

• Added functionality to copy an Action logged against one CLE to other selected CLEs. 

• Added a Mail Queue Attachment factbox. 

• Added Preview to Report option on Workflow. 

• Change to show Overdue Actions as overdue on due date plus one day. 

• Created a new Report to use to generate email attachments for reminders that are already issued. 

• Change to SD-CC Customer List to show 0.00 in the Running Balance and Overdue Balance if no value is calculated. 

• Migrated Action Comments to HTML Control. 

• Updated Workflow process to handle the new HTML Action Comments. 

• Updated the Action Card to use the HTML control and process. 

• Updated the Template Card to use the HTML control and process. 

• Added functionality to allow email consolidation of Workflows. 

• In the SD-CC Setup Card - rename the 'Auto close actions' Action to 'Auto Close Actions'. 

• Added functionality to attach a copy of Invoices to the Reminders when sent via Email to the Customer. 

• Added functionality to check that reports for Workflow email Reminder attachments must have the SD-CC Cust. Ledger Entry table as the report data root item. 

• Created functionality to un-assign a Customer from a Credit Controller. Action surfaced on SD-CC Customer List Page. 

• Created a W1 release. 

• Created a 2017 release.

#### Bug Fixes

• Fixed syncing issue in Page SD-CC Customer List for overdue customer with all entries of closed payments. 

• Fixed issue where running the Create Actions for Overdue functionality is not creating Actions for all overdue ledger entries in the Managed Companies. 

• Fixed issue where when running the Calculate Performance for Selection on one newly created Customer, a message 'Object ID not found' was raised. 

• Fixed incorrect Page Action Name on page SD-CC Customer List. Page Action 'Unassign to Credit Controller' has incorrect spelling in word 'Uassign'. 

• Fixed issue where the SD CC Job errored out due to an issue with Auto Close Action function. 

• In the SD-CC Company List renamed Actions. Renamed "Customer Sync. Fields" to "Customer Sync Fields" and "Sync Customer Ledger entries" to "Sync Customer Ledger Entries". 

• SD-CC Company List was missing the Company Hierarchy Fact Box from Version 8.1.0 of SD Credit Controller. 

• While in a CLE for a Managed Company, on selection of New Repayment Plan in the Action Card, raise a message to inform the user that they are creating a Payment Plan and that payments need to made within the Managed Company. 

• Fixed issue where for the Workflows with a Template Type of Email, the placeholders were not updating in emails.
 
• Fixed synchronisation issue with promised amounts on Action Card not updating on CLE. 

• Fixed an issue where closed entries in a Managed Co that were marked as in dispute were still showing, although closed, in the SDCC CLE in the Master Co.

### 9.0.1

#### Enhancements

• Created a Mail Queueing System to handle E-Mail Reminders. 

• Added Cues to the Controller and Team Role Centres to filter on Repayment Plans. 

• Created a running balance process for Job Queues. 

• Upgraded SD Credit Controller to use the new Simply Dynamics Charts. 

• Created a new Chart to show the Total Overdue Balance per Team. 

• Created an SD CC Administrator Role Centre. 

• Filtered the My Incomplete Actions on the CC Manager Role Centre by Team and added an extra column to the My Incomplete Actions List for the Credit Controller whose Action this is. 

• Created new functionality to allow for Teams of Credit Controllers to be setup. 

• Created new functionality for Credit Controller Workflows. Created Email Templates, created Mail Merge Templates - Mail Merge, Attachment, Report, created Email Logging. 

• Auto create an Action for Invoices when an Invoice becomes Overdue. The Action is assigned to the same Credit Controller User as the Customer is assigned to. 

• Allow All Credit Controllers to use the same common, single, email address as their Credit Controller contact email address. 

• Created a new SD Credit Controller CLE Report. 

• In the SD Credit Controller Action Card, a new Action was added to ‘Print Preview' or display the details of the CLE that the Action is logged against. 

• Added the standard Microsoft Dynamics NAV option "Navigate" to the SD Credit Controller Cust. Ledger Entry List. 

• Created new Role Centre Cues - Overdue Amount; Balance; Overdue on Blocked; Amount in Dispute; a count of the Customers that are over their Credit Limit. 

• Optimised the performance of the SD Credit Controller Customer List Page. 

• Made improvements to the SD Credit Controller Recurring Payment Dialog - updated the 'Document Type' field to have an initial value set to the 'Payments' option; updated the 'Amount' field caption to point the user to enter the value in negative. 

• Added the Open/Closed Actions to the Customer Ledger Entries on the SD Credit Controller Customer List.

#### Bug Fixes

• Fixed an issue where the Role Centre Cues were not filtering correctly. 

• Fixed an issue where the ‘My Overdue Customers’ Cue on the Role Centre was showing a 0 count of the Overdue Customers where Overdue Customers exist. 

• Fixed an issue where the ‘Promised Amount’ and ‘Promised Date’ fields on the the Action Card were not updated on the associated Customer Ledger Entries. 

• Fixed an issues where the Single Company Balance, Multi Balance and Multi Overdue, were not calculating correctly. 

• Fixed an issue on the SD-CC Customer Card Page where the Multi-Balance(LCY) @date and Multi-Overdue (LCY) @date were displaying correctly in the General FastTab but not on the Customer Details FactBox. 

• Made a change to the SD Credit Controller logic to verify that the Customer exists on Payment Recalculation.

### 9.0.0

#### Enhancements

• Added All Incomplete Actions and Active Repayment Plans to the Role Center. 

• UI improvements made to the Customer List. Currency was added to the Aging FactBox. Removed Managed Company Hierarchy FactBox. 

• Renumbered Objects. 

• Reviewed all Cue counts. 

• Reviewed Code. 

• Created Help Files. 

• Reviewed Role Centre UI and Role Centre Actions. 

• In the SD-CC Action List Page, the Customer Name for the Customer was displayed. 

• In the SD-CC Action Card Page, the Customer Name for the Customer was displayed.
 
• An option was added to create notifications automatically on creation of an action. 

• In the Active Repayment Plans List, the Customer Name was displayed. 

• In the Credit Controller Setup Page, the Categories Action was surfaced in the Home Tab in the Ribbon, as per the other classifications. 

• Created a message to notify users that setup configuration for charts must be completed. 

• Updated overdue responsibility check calculation. 

• Created a new field Overdue @ to the Customer Card. 

• Added new fields on SD-CC Action table, Promised Amount, Promised Date, and Company Name to the SD-CC Action List Page. 

• Added Balance and Balance (LCY) fields to the SD-CC Customer List Page. 

• Added new fields to the Customer List Page.

• Made a change to the Setup UI. Moved Sync Manager to Sync Companies. 

• In the CC Recurring Payment List Page, the Document No field was hidden.

#### Bug Fixes

• Fixed an error raised when selecting the Customers field in the Credit Controllers Details FactBox. 

• Fixed an error raised when selecting the Verify Overdue Responsibilities Actions from the SD-CC Credit Controller List Page. 

• Fixed an error raised when running the SD-CC Job Processor Codeunit.
 
• Fixed an issue whereby creating a New Customer auto-assigns all Customers a Credit Controller.

• Fixed an unexpected navigational behaviour issue when creating a new Customer record in SD Credit Controller.

• In the SD Credit Controller Customer List Page - Open Entries - the Sync Date Time was not updating. 

• In the SD-CC Credit Controller List Page, rename Verify Overdue responsibilities to Verify Overdue Responsibilities.
 
• In the SD-CC RC, My Overdue Customers Cue, on drilldown through the Cue, the list is not filtered to Overdue Customers. 

• In the SD-CC Role Centre, in the My Blocked Customers Cue, on drilldown through the Cue, the list is not filtered. 

• In the SD-CC RC, Unassigned Customers Cue, the Cue has a 0 count but on drilldown all customers with a Credit Controller assigned are displayed.
 
• If there is no record in the Credit Controller Setup Page, an error is raised when the Role Centre (Manager Role Centre) is opened.

• In the Actions List, Action Details Fact Box, there is a spelling mistake. Customer Replayment should be Customer Repayment. 

• In the Recurring Payment table, a blank record was inserted on selection of New Repayment Plan Action. 

• Cannot open the SD CC Cust Card if customer assigned a Credit Controller that has a value in the Overdue Responsibility (LCY) and the Customer balance greater than the Overdue Responsibility (LCY).
 
• Fixed an issue in the About Page.
 
• When navigating through the menus on the navigation pane, message was raised that performance history must be set. 

• Promised Amount and Date on CLE should not be updated when CLE Closed. 

• Reviewed the SD-CC Action List Page Behaviour. 

• The Performance Rating in the Customer card was not updated with the last Performance rating calculation. 

• Fixed an issue in the My Credit Customers Page where the Actions list page was not filtered properly. 

• The Create New Action in the ‘Actions’ page does not call page to create a new action.

• Fixed an issue whereby an Action created from Entry level in the New Action card does not validate the Cust. Entry No into the field.

• In the Role Centre, the Cue fields Promised Amount and Promised Amount this week only filter the complete actions whereas the filter should be on open actions. 

• Fixed an error raised in Repayment Plans when posting cash receipt journal line generated from recurring journal with a 1W frequency where the current posting date based on frequency is lower then Expiration Date. 

• In the Company Synchronisation display a message that the Synchronisation is finished.

• Fixed issue in Balance Due calculation.


### 8.1.0

#### Enhancements

• Created Promised Payments functionality. Promised Amount and Promised Date. 

• Added Ageing FactBox to the SD Credit Controller Customer Ledger Entries page.
 
• Added Overdue Actions Cue to the Role Centre. 

• Added Repayment Plans Overdue Cue to the Role Centre. 

• Display the amount of Actions assigned to a Customer in the Credit Controller Customer List. 

• Create follow up Action on completion of an Action. 

• Auto close action on payment of transaction. 

• Do not allow access to the SD Credit Controller module if the user is in a Managed Company. 

• Created an additional Role Centre for the Credit Controllers. 

• Created About Dialog page. 

• Removed Report Inbox from the Role Centres. 

• Surface Repayment Plans Actions.
 
• Surfaced Credit Controller field on the All Credit Customers page.
 
• Enhanced Customer assignment to Credit Controllers. 

• Unable to assign Credit Category Code to a Customer in the Credit Controller Customer page. 

• Credit Categories Page surfaced on SD Credit Controller Setup page.
 
• Actions Due this Week’ are highlighted with a style to highlight Actions due. 

• Changes to SD Credit Controller Action functionality.

#### Bug Fixes

• Drilling down on the Customer Cues in the Role Centre records after first import of objects raises an error regarding the Credit Controller Setup. 

• Cannot drill through on some of the Cues in the Role Centre that have a count of 0. 

• Navigation through menus on navigation pane in the Role Centre records after first import of objects raises an error regarding the Credit Controller Setup. 

• Entering a value into the Performance Period field on the Credit Controller Setup, updates the performance without needing a value in the Performance History Length field.

• The count on the My Blocked Customers Cue, in the Role Centre, doesn't correspond to the count of the Blocked Customers on drill through to the list page of My Blocked Customers. 

• The length of the Bank No. field on the Repayment journal is incorrect (too long). 

• Error message raised on posting of Cash Receipt Journal. 

• The My Blocked Customers Cue in the Role Centre is not filtering correctly. 

• Recurring Journal posting with multiple lines and with different recurring frequencies. 

### 8.0.0

#### Enhancements

• Initial release. NAV 2016 complete re-write of SD Credit Controller. 

• Created Customer Sync fields and associated functionality. 

• Created Credit Controller Customer table, pages and associated functionality. 

• Created Credit Category table, pages and associated functionality. 

• Created Credit Controller table, pages and associated functionality. 

• Created Credit Classification table, pages and associated functionality. 

• Created Risk Category table, pages and associated functionality. 

• Created Credit Controller CLE table, pages and associated functionality. 

• Created Payment Performance table, pages and associated functionality. 

• Created Recurring Payment table, pages and associated functionality. 

• Added an Action to navigate to Standard NAV Reminders. 

• Created Aged Debt functionality. 

• Created Credit Controller Action table, pages and associated functionality. 

• Created synchronization functionality from parent company to child company. 

• Created Credit Controller Setup table, pages and associated functionality. 

• Created Credit Controller Company table, pages and associated functionality. 

• Created Credit Controller Role Centres, Cues, Graphs, Factboxes.

### 7.0.0

#### Enhancements

• Basic Table and UI layout changes to Setup, Credit Controllers, Customers, Transactions, Risk Groups, General Categories, Credit Status. 

• Take existing codebase and rebuild for Nav2013R2. 

• Remove the AddIn folder. 

• Code refactoring and rebuild. Clean up and refactor the Codeunits. 

• Add Average Debtor Days to SD Credit Controller and include in Aged Debt calculations. 

• Add VIMA Verification to Credit Controller customer record. 

• Communications. Ability to send Email, SMS, and Phone using contact details. Communications logged on the Credit Controller Communications Log table. 

• Actions. Allow to copy an Actions Comment to the Customer Comments table. 

• Approvals of Sales Orders. If Sales and Receivables Setup has a credit warning, then create an entry in the SD Credit Controller Approval Entry. 

• Create a Worksheet for SD Credit Controller.

• Review UI.

