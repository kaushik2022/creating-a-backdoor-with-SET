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
![1](https://github.com/user-attachments/assets/8e3bb125-d21f-441c-937d-35c0527cfd8b)

### It displays the following menu and select 2 for Website Attack Vectors:

![2](https://github.com/user-attachments/assets/c5c6b2dd-5d2f-465b-ad26-679adde44069)

### The website Attack Vectors displays the following menu. In this menu3 for Credential Harvester Attack Method is selected:
![3](https://github.com/user-attachments/assets/ba03ce43-7b42-40e0-9778-c1c5c6a342e5)

### The Credential Harvester Attack Method displays the following menu. In this menu1 for Web Templates is selected:

![4](https://github.com/user-attachments/assets/27e63d5b-13d5-4f20-948e-eb9358598607)

### It shows the following screen in which the ip address of the attacker need to be given which is the default value:

![5](https://github.com/user-attachments/assets/9f178493-578a-47df-9d15-feac3665fca2)

### It shows the following screen in which the option Google can be selected

![6](https://github.com/user-attachments/assets/0f1748e3-9d60-49de-8069-24be0e225bd3)

### SET starts my Kali Linux Webserver on port 80, with the fake Google account login page. The setup is done:

![7](https://github.com/user-attachments/assets/9255140d-5ed5-404e-bbdc-d561c251f3cf)

### In windows IE, on giving the url http://192.168.74.***, the fake Google page is displayed. The victim can enter the username and password
![8](https://github.com/user-attachments/assets/889b0361-824d-4016-aa22-0f35a89eed29)

### SET logs the information regarding the Google credentials:
![9](https://github.com/user-attachments/assets/6593b6e1-2e2e-44db-9319-cddb52748c39)

### SET logs the information in the xml file under /root/.set directory:
![10](https://github.com/user-attachments/assets/f1779572-cb0f-40ed-a1fe-2c2c4898117e)



## RESULT:
The Social Engineering Toolkit (SET) is used to create backdoor is  examined successfully
