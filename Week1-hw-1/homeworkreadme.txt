Home work. 

First step create a security group and set the inbound rules. We can use Ipv4 along with SSH & Http.
Do not touch outbound rules.
Next click on create security groups.

Next create an instance Name it with no spaces. 
Select instance types t2.micro free version.
Under keypair select proceed without a key pair. 
Next select the security group that was created. 
Click on advanced details. Scroll to the bottom where the user date is. 
Copy the script from git hub the raw file. 
Past the script under user data section then launch instance. Then check the status to see if its running.

Select the instance and copy the public Dns. Clicking on the double blue boxes. Open a new browser tab and paste it there. 

Tare down- Click on your instance, next under instance state click on stop. Then click on terminate. 