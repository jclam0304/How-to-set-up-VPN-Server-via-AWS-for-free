# How-to-set-up-VPN-Server-via-AWS-for-free
A free VPN Service via AWS (Template provided by webdigi)
# Step 1: 
Register a free Amazon Web Service Account at: http://aws.amazon.com/free/
# Step 2: 
Verfy your identity with a Credit Card (which must payable with USD)
# Step 3:
Choose your VPN region in the Admin Console: e.g. Tokyo
# Step 4: 
Select "CloudFormation" from the Service Portal
# Step 5:
Create a Stack 
# Step 6：
Using Amazon S3 Template to add https://s3.amazonaws.com/webdigi/VPN/Unified-Cloud-Formation.json
# Step 7:
*Configure the VPN Server:
*Stack Name
*speed： Standard.VPN-Free
*Username
*VPNPassword
*VPNPhrase： L2TP Secure Connect
# Step 8: 
Tag: No Tag is needed
# Step 9: 
Publish
# Step 10: 
Get the VPN ip address in the instance management portal
# Step 11: 
Have fun and enjoy the VPN service!
