# Free-windows-RDP-Method-ngrok-rdp
Description
What is RDP?

RDP (Remote Desktop Protocol) is a network communications protocol developed by Microsoft, which allows users to connect to another computer from a remote location.
How long does this RDP stay active?

This RDP stays active for up to 6 hours.
How to use it?
HOW TO USE:


First Step
Press the fork button
Login or signup to ngrok: https://ngrok.com
Now visit here for token: https://dashboard.ngrok.com/auth/your-authtoken
You'll get token from here. It'll be needed to the next step.

Second Step
In your forked repo: Go to Settings > Secrets > Action > New Repository Secret
In the name section, enter this text: NGROK_AUTH_TOKEN
In the value section, enter the ngrok token
Then press Add Secret
Now go to Action > AWS (Left Menu) > Run Workflow
Refresh the page and go to AWS > build option
You'll get IP, Username & Password from Connect to RDP section.
Third Step
Search Remote Desktop Connection from Windows Start Menu and open.
Put IP without tcp:// and enter Username & click Connect.
Later on, put the password for credential/auth.
ss



![image](https://user-images.githubusercontent.com/105972220/234501248-1bc78448-e652-4201-8f6b-e27eeea4ed65.png)


Screenshots
ss![image](https://user-images.githubusercontent.com/105972220/234501298-d6275e78-650c-4b8d-81ce-4b4b26dca5cd.png)


ss
![image](https://user-images.githubusercontent.com/105972220/234501355-81b3cf26-1e45-4fae-bf4b-cb7eb1a1c387.png)
