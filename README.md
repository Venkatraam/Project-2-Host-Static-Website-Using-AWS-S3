# Project-2-Host-Static-Website-Using-AWS-S3

Step 1: Creating a Bucket
Open the Amazon S3 console
Click on Create Bucket.
Choose Bucket Name – Bucket Name Should be Unique
AWS Region –  Choose a region close to you or the region where you want to create the bucket (Example — Mumbai)
Object Ownership – Enable for making Public, Otherwise disable
Uncheck (Block all public access) for the public, otherwise set default. If you uncheck (Block all public keys).
Bucket Versioning:- You have to do Nothing (Disable)
Default encryption: Disable  

Step 2: Now upload code files
Select Bucket and Click your Bucket Name.
Now, click on upload (then click add File/folder) and select your HTML code file from your PC/Laptop.    

Step 3: Once the Files are uploaded successfully, click on Permissions and now follow this Process –
Block public access:
Click on Edit, under Bucket Policy.
Uncheck Block all public access.
Save changes then type “confirm”.

Object Ownership: 
Click on Edit.
Click on ACLs Enabled.
Check I acknowledge ….. restored.
Choose Save Changes.

Step 4:- Make public Object
Now, Click on Objects.
Select your All Objects.
Now, Click on Actions.
Select Make Public Using ACL.
Now, Click on Make Public and Close.

Step 5: Copy your Object URL
Now, click on your HTML File Object Name.
Copy the Object URL.

Step 6: Check out your Website!
Directly Paste this URL into the Other Tab or your other System.
Congratulation, Now Your Website is available in the Public.
You Successfully Host Your Website by AWS S3.
