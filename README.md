# creating-a-backdoor-with-SET
creating a backdoor with SET - Ethical Hacking Techniques course

# AIM:
To Create a backdoor with Social Engineering Toolkit (SET)

## DESIGN STEPS:
### Step 1:
Install kali linux either in partition or virtual box or in live mode.

### Step 2:
Investigate on the various categories of tools as follows.

### Step 3:
Open terminal and try execute some kali linux commands.

## EXECUTION STEPS AND ITS OUTPUT:
Social Engineering attacks are the various cons used by the hackers to trick people into providing sensitive data to the attackers. The command sudo setoolkit in the prompt gives menu with set prompt:

![Screenshot_2024-04-28_11_52_37](https://github.com/JananiSoundararajan/creating-a-backdoor-with-SET/assets/119477549/e67abd28-edff-40a1-973f-50e402357549)


The command sudo setoolkit in the prompt gives menu with set prompt. Select menu1 for Social Engineering Attacks:

It displays the following menu and select 2 for Website Attack Vectors:

![image](https://github.com/Yamunaasri/creating-a-backdoor-with-SET/assets/115707860/880a2bde-a9f3-452a-90f1-bdd2a2a9f572)

The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:

![image](https://github.com/Yamunaasri/creating-a-backdoor-with-SET/assets/115707860/8ed9bef6-f39f-4666-83d3-ea373ef49105)

The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected: 

![image](https://github.com/Yamunaasri/creating-a-backdoor-with-SET/assets/115707860/3c59ee6c-17fb-4fe6-a892-ca404e6f809c)

It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![Screenshot_2024-04-28_12_02_27](https://github.com/JananiSoundararajan/creating-a-backdoor-with-SET/assets/119477549/aae80965-20fa-46fa-878d-f0f912e8dc2e)


It shows the following screen in which the option Google can be selected: 

![Screenshot_2024-04-28_12_08_44](https://github.com/JananiSoundararajan/creating-a-backdoor-with-SET/assets/119477549/77bf3ede-6f37-4abf-9e5c-5a0a20f71a38)


SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done: 

![Screenshot_2024-04-28_12_14_00](https://github.com/JananiSoundararajan/creating-a-backdoor-with-SET/assets/119477549/2b41ad0b-3065-490f-bc59-d5a641acb56f)


In windows IE, on giving the url http://10.0.2.15, the fake Google page is displayed. The victim can enter the username and password.

![Screenshot_2024-04-28_12_19_43](https://github.com/JananiSoundararajan/creating-a-backdoor-with-SET/assets/119477549/136422da-1e97-471c-9ff9-273da837ac37)


SET logs the information regarding the Google credentials: 

![image](https://github.com/Yamunaasri/creating-a-backdoor-with-SET/assets/115707860/2d9872e5-1ad5-461b-8977-8ceef46349d6)

SET logs the information in the xml file under /root/.set directory:

![Screenshot 2024-04-24 091439](https://github.com/Yamunaasri/creating-a-backdoor-with-SET/assets/115707860/d5cb5cc7-d79a-4a16-a3e9-2cf6bf9a03c5)

## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully

