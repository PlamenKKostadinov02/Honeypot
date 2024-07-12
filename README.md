# Honeypot
##For the SSH Honeypot I used the one from pentbox, more specifically the pentbox 1.8.
I got it from GitHub with the "git clone" command. After installing the honeypot I opened it with the following command: "sudo ruby pentbox.rb".

Then I navigated to the second tab "Network tools" and then to the third tab "Honeypot"
After we have 2 options, the "Fast Auto Configuration" or the "Manual Configuration"

For the automatic configuration it will automically open port 80 which is the "HTTP" port.
For the manual configuration we can open it whatever port we want, in this example, the port 443 which is the "HTTPS" port.

As we can see in the images that the honeypot works perfectly fine.

DISCLAIMER: I first used this honeypot on another laptop which I don't have anymore and I did not document anything, on that laptop I opened the honeypot with the following command "sudo ruby pentbox.rb &" and left it working for 2 days. After these 2 days I opened the .json file I created so I can log all the intrusions it detected and it got over 50 intrusions.
