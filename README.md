# Honeypot-
Milestone 0
I chose to download and use GCP 
I ran glcoud config list
This enabled me to see my current settings 
I was able to succesfully run GCP, however I kept running into issues when setting the correct zone and region
Milestone 1
I went  through the GCP users firewall setup
I ran into an issue here with the proper syntax
After a few trials and errors, I learned I needed to put a space inbetween each line of code and disregard the "\" 
After figuring out how to do the first firewall rule, the other two were incredibly simple
However in the process of creating the rules, I received an error message telling me the rule I was trying to create already existed
I then had to go to GCP, delete the FW rule, and then try it again
Milestone 2
Next I created the VM "mhn-admin"
Once again I ran into the issue of having an incorrect zone
I was able to resolve that by copying and pasting "us-central1-f" from the assignment page
Next I established SSH access to the VM by gcloud compute ssh mhn-admin
I sucessfully installed MHN admin app with zero problems
Selected "n" for run in debug mode
Chose a username and passowrd and then selected default prompts for the rest of the values
Milestone 3
Next I created the MHN Honeypot VM 
Had no issues with this step 
Milestone 4
Installed Honeypot App
Deployed in my broser
Selected Ubuntu/Raspberry Pi-Dionaea 
Copied the command from the browser page 
Clicked on Sensors and saw the new honeypot listed 
Milestone 5 
This was where I ran into some issues
I ran nmap thru kali/Linux 
I ran nmap -A -T4 (IP address)
However I could not get the honeypot to intercept any attacks
I even tried changing the IP address, thinking it was intercepting the wrong honeypot
But still, I could not get it to interceot

