MB-901: Dynamics 365 Fundamentals
Module12, Lab 3: Enhance security by encrypting your data
Scenario: You, as a system administrator need to change and copy the organization encryption key.

Instructions
Navigate to Power Platform Admin center.
These settings can be found in to Environments > [select an environment] > Settings > Encryption > Data encryption.
In the Change Encryption Key box type the new encryption key and then select Change.
Select OK in the confirmation message and then select Close to exit the Data Encryption page.
We strongly recommend that you make a copy of your data encryption key.

Select the same environment you used in steps 1-4 and go to Settings > Encryption.
In the Data Encryption dialog box, select Show Encryption Key, in the Current encryption key box select the encryption key, and copy it to the clipboard.
Paste the encryption key into a text editor such as Notepad.
Note: By default, model-driven apps in Dynamics 365 generate a passphrase that is a random collection of Unicode characters. Therefore, you must save the system-generated passphrase by using an application and file that supports Unicode characters. Some text editors, such as Notepad use ANSI coding by default. Before you save the passphrase using Notepad, select Save As, and then in the Encoding list, select Unicode.

As a best practice, save the text file that contains the encryption key on a computer in a secure location on an encrypted hard drive.