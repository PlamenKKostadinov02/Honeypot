# Honeypot
For the SSH Honeypot I used the one from pentbox, more specifically the pentbox 1.8.
I got it from GitHub with the "git clone https://github.com/technicaldada/pentbox.git " command. Then I used the following commands in that order:
- "cd pentbox"
- "tar -zxvf pentbox.tar.gz"
- "cd pentbox"
- "./pentbox.rb"

To install ruby I used this commands:
- "sudo apt update"
- "sudo apt install ruby"

After installing the honeypot I opened it with the following command: "sudo ruby pentbox.rb".

Then I navigated to the second tab "Network tools" and then to the third tab "Honeypot"
![image](https://github.com/user-attachments/assets/828540fd-ea25-43d0-a9e4-6920cd4059bc)

After we have 2 options, the "Fast Auto Configuration" or the "Manual Configuration"

For the automatic configuration it will automically open port 80 which is the "HTTP" port.
![image](https://github.com/user-attachments/assets/be925061-2fa5-4c7f-b0b0-40beac75b9b1)

(Image after searching for the IP address on port 80)
![image](https://github.com/user-attachments/assets/37f895bf-6e3e-42b9-990e-c7da8f590018)


For the manual configuration we can open it whatever port we want, in this example, the port 443 which is the "HTTPS" port.
![image](https://github.com/user-attachments/assets/49a72536-bf0c-41b0-a8bb-f721ca7ef3f0)

(Image after searching for the IP address on port 443)
![image](https://github.com/user-attachments/assets/913410f7-4c10-495e-8120-4d380994396b)


As we can see in the images above, the honeypot works perfectly fine.

DISCLAIMER: I first used this honeypot on another laptop which I don't have anymore and I did not document anything, on that laptop I opened the honeypot with the following command "sudo ruby pentbox.rb &" and left it working for 2 days. After these 2 days I opened the .json file I created so I can log all the intrusions it detected and it got over 50 intrusions.
