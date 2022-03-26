# WorkshopInvoicing
Queries SharePoint Worshop site to create invoice records file for a billing system and closes out those same SharePoint records

Shown with permission of Region 5 ESC. The site this program ran against was replaced with a 3rd party solution around 8 years ago. I have changed server names, database names, and other identifiers. The code will probably not run given these changes and the age of the code and the SharePoint DLL dependency.

The program read several SharePoint lists looking for workshops that had ended. It either pulled all the participant billing information into a CSV file for our invoicing software, and set those same records to close them out and set up data for certificate creation by a SQL Server Reporting Services server I managed.

This is the second project I wrote for an organization. I was learning C# while I wrote this. This program involved learning the SharePoint object model, LINQ, and CAML in addition to the C# language itself. There are obviously many things I would change if I was writing this program today. For one, I would combine some of the classes into a single helper class. I would also provide many more comments to walk a coder through the program.
