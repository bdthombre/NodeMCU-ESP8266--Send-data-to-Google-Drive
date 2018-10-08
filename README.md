# NodeMCU-Current-Measuring-System
In this System, we are measuring current consumption of any Electronic Appliance by connecting it with a Current detecting sensor, which is further connected to **ESP Module(NodeMCU Base ver 1.0)**. We can access or check the value of that sensor remotely anytime from anywhere. Data will be displayed and updated realtime with a proper timestamp in your personal sign-in Google drive(Spreadsheet) account.

## Installation
1. Log in into your google drive and create a new Blank Spreadsheet.
2. Enter Details about the tags into header row, such as: Time, Output1, Output2.Then select Tools/Script editor. 
   A new Script file will be opened, rename it with the same filename that you gave to your Spreadsheet.
3. Copy the code in the file **"Cloud_scriptfile.txt"** and paste it into your Script file. 
    Replace sheet_id wriiten in the code by the Sheet ID of your Spreadsheet.
    https://docs.google.com/spreadsheets/d/**<SHEET_ID>**/edit#gid=0
4. Then save your script and select Publish/Deploy as web app.
	* After Deploying, you will got a link like this: https://script.google.com/macros/s/**<SCRIPT_ID>**/exec?
    > **NOTE:** Select option Anyone or Anyone, even anonymous.
    	    
5. After this open latest version of Arduino IDE code(*.ino) and uplode it in the ESP Module (NodeMCU Base ver 1.0).
6. Connect your Current detecting sensor on **Pin-D4(GPIO5)**.
     
@ karanjeet1
