# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode


### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:

Open terminal and try execute some kali linux commands

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. 
The command sudo setoolkit in the prompt gives menu with set prompt:
## OUTPUT

<img width="1406" height="777" alt="image" src="https://github.com/user-attachments/assets/d0bb5559-86d3-4933-8d58-fd8252247d97" />

<img width="1302" height="1021" alt="image" src="https://github.com/user-attachments/assets/e0ac6975-81b4-4e16-90a5-b76707a3b40a" />



The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:
## OUTPUT

<img width="1360" height="1015" alt="image" src="https://github.com/user-attachments/assets/f8fd493c-e7f6-42ea-99c9-1a113b473c70" />

<img width="1266" height="1020" alt="image" src="https://github.com/user-attachments/assets/792ee52e-1214-4056-b1af-1f7929766584" />



It displays the following menu and select 2 for Website Attack Vectors:
## OUTPUT

<img width="1395" height="1055" alt="image" src="https://github.com/user-attachments/assets/4a75ed71-887d-4155-b3e4-743ff8734c9b" />



The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:
## OUTPUT

<img width="1422" height="1033" alt="image" src="https://github.com/user-attachments/assets/32828b67-361d-4a09-b7af-1ae29e982e84" />


It shows the following screen in which the ip address of the attacker need to be given which is the default value:
## OUTPUT

<img width="937" height="842" alt="image" src="https://github.com/user-attachments/assets/af787360-eabb-42ed-8741-baa8cfceaadf" />



It shows the following screen in which the option Google can be selected:
## OUTPUT

<img width="977" height="447" alt="image" src="https://github.com/user-attachments/assets/a0503102-145c-4c2a-9b4f-d209d4bcd608" />




SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:
## OUTPUT

<img width="975" height="293" alt="image" src="https://github.com/user-attachments/assets/40116318-1da3-417d-8a16-f77ce2590d43" />



In windows IE, on giving the url http://192.168.1.2 (use appropriate IP address), the fake Google page is displayed. The victim can enter the username and password
## OUTPUT

<img width="951" height="1078" alt="image" src="https://github.com/user-attachments/assets/5e430646-b36b-4910-9fbc-f92dded48cdb" />


SET logs the information regarding the Google credentials:
## OUTPUT

<img width="951" height="1078" alt="image" src="https://github.com/user-attachments/assets/e8df3e2f-6e8d-465f-831f-ef1aa6810037" />


SET logs the information in the xml file under /root/.set directory:
## OUTPUT


<img width="943" height="1013" alt="image" src="https://github.com/user-attachments/assets/ec1c5038-dfba-457e-8792-41fbff76ff69" />



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
