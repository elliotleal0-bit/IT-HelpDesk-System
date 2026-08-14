# IT- osTicket Creating a ticket until resolution
# Description
This demonstration outlines logging on to osTicket through Azure and a Virtual Machine, creating a ticket and completing until resolution
# Enviornments and Technologies Used
- Microsoft Azure (Virtual Machine)
- Remote Desktop
- Internet Information Services (IIS)

- # Operating Systems Used
- Windows 12
# Overview
- Logging on
- Creating a ticket
- Working on the issue
- Resolution
# Logging on
- Before accessing osTicket, you will need to login to your Azure account and start up the Virtual Machine you created.
<img width="1117" height="606" alt="Screenshot 2026-08-13 at 15 18 34" src="https://github.com/user-attachments/assets/e2865781-72bf-436d-9945-fd14e727aa56" />
- After your VM engine has started, if using a Mac you will need to open up a session on the windows app using the Public IP address from your VM. Using the credentials saved, you will be able to open up a remote desktop session.
<img width="1117" height="606" alt="Screenshot 2026-08-13 at 16 17 21" src="https://github.com/user-attachments/assets/af2a8d39-7bd1-4e44-a476-d49ea406c24a" />
- Open up a browser and use the following link to get to the osTicket login page http://localhost/osTicket/scp/login.php
<img width="955" height="637" alt="image" src="https://github.com/user-attachments/assets/c4096c4f-5363-4065-a071-11ccfb36054f" />
# Creating a Ticket
- Before creating a ticket you will want to make sure you have all the information you need to create a ticket. Did the ticket come in through text, call or email. What is the issue, when did it start, how long has it been going on. After gathering all this information we are able to identify which department will be needed, what is the priority, characterized as High, Normal and Low. SLA for resolve on High priority  is 8 hours, Normal 24 hours, Low 3 days, and some other cases, Emergency which is 1 hour. When you have all your information click the new ticket icon.
<img width="992" height="394" alt="image" src="https://github.com/user-attachments/assets/5b4f901f-c491-40bd-8169-5f9c7349f53d" />
As you enter the New ticket screen you will want to fill out all your information. Ticket Source, Help Topic, Department, SLA plan if there are any available. In this case, only option available is Default SLA, 18 hours. Due date, who to assign to, issue summary, giving any additional details you can give on the customers issue. When that all is completed you can go ahead and create your ticket.
<img width="1012" height="735" alt="image" src="https://github.com/user-attachments/assets/e1779ba7-b699-4e97-8c4a-3612ea5d4b72" />

