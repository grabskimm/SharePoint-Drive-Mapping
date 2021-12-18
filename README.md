# SharePoint drive mapping

The purpose of the script is to map a SharePoint folder to remotely AD/AAD users.


- Replace lines 52, 53, 54, 56, 57, 58 with data captured from your SharePoint site. To do so you can launch the SharePoint folder > select F12 for developer tools > navigate to Networking tab > stop recording >start recording > select the Sync button for the folder > stop recording > lookup data captured under headers where it will break it down to individual lines. 

- The script must run as-user and not System. 

- The user must have permission to the folder. 
