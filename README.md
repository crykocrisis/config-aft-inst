# osTicket: Configuration After Installation

This guide describes how to configure the open-source help desk ticketing system osTicket after installation.

<h2>Environments & Technologies Used</h2>

- Microsoft Azure
- Remote Desktop
- IIS

<h2>Operating Systems Used </h2>

- Windows 10 (21H2)

<b>Names & emails used are not real, they are just examples for the tutorial.</b>

Login for admins & analysts: http://localhost/osTicket/scp/login.php

URL for end users: http://localhost/osTicket

<b>Compare the Admin Panel & the Agent Panel.</b> 

Admin Panel (settings, manage, agents, etc.):

![Screenshot 2025-06-23 213914](https://github.com/user-attachments/assets/f3d95340-73ba-4983-b786-25a8a4b9d240)

Agent Panel (tasks, tickets, users, etc):

![Screenshot 2025-06-23 213630](https://github.com/user-attachments/assets/5934f80b-ec9a-445b-b5b9-b965e7e29798)

1. Set up roles to group permissions.

a. Admin Panel (changes to Agent Panel once you are in the Admin Panel), followed by Agents & Roles.

![Screenshot 2025-06-23 214356](https://github.com/user-attachments/assets/761e593b-28d8-4f64-972b-63075c1b9c5c)

b. Set a new Role "Supreme Admin"

![Screenshot 2025-06-23 212743](https://github.com/user-attachments/assets/81051a8a-3d57-479d-adaa-d9712571e391)
![Screenshot 2025-06-23 213044](https://github.com/user-attachments/assets/4b037dc4-5aaf-41f2-880e-f416efeedde9)
![Screenshot 2025-06-23 212938](https://github.com/user-attachments/assets/eeee4910-2426-4591-a0ae-8e96d23f9204)
![Screenshot 2025-06-23 213159](https://github.com/user-attachments/assets/5fcdacd0-5383-4c11-8689-45a604ef0bfa)
![Screenshot 2025-06-23 213255](https://github.com/user-attachments/assets/3f3826d0-0768-4677-a1f1-f5f134fc01da)

2. Set up departments, such as networking, help desk & ticket visibility.

a. Admin Panel, followed by Agents & Departments.

![Screenshot 2025-06-23 214531](https://github.com/user-attachments/assets/613778f4-75f9-4ff3-be0f-064517d9aad0)

b. Create a new department "SysAdmins"

![Screenshot 2025-06-23 215123](https://github.com/user-attachments/assets/1a857914-6eea-43ef-b043-f85e62781991)
![Screenshot 2025-06-23 215217](https://github.com/user-attachments/assets/a7033c1a-4b6e-4a63-b8bc-d18bad53b576)

3. Set up Teams

a. Admin Panel, Agents & Teams.

![image](https://github.com/user-attachments/assets/c87d589e-fa6b-4108-88b5-e7a8f991bb98)

b. Add a new team "Online Banking"

![Screenshot 2025-06-23 215632](https://github.com/user-attachments/assets/3fc703a0-d395-4b37-bd53-ddacaf9e3559)
![Screenshot 2025-06-23 215748](https://github.com/user-attachments/assets/a2b4e4f6-1f38-40a1-987b-bb0fa9d8af4f)

4. Let anyone make tickets.

a. Go to Settings in the Admin Panel, then Users (UNCHECK: Require registration... ).

![Screenshot 2025-06-23 220408](https://github.com/user-attachments/assets/d6aaee50-e994-4c9f-8a05-79b8dc39ad0c)

5. Set up agents, or employees.

a. In the Admin Panel, choose Agents & Add New.

![Screenshot 2025-06-23 220941](https://github.com/user-attachments/assets/3d3d6918-8235-4ff7-aee0-07b70efab06e)

- Jane Doe 

![Screenshot 2025-06-23 221821](https://github.com/user-attachments/assets/7af3d6df-9640-4f25-934b-5795d97e37e8)
![Screenshot 2025-06-23 222730](https://github.com/user-attachments/assets/91f531f7-72bf-4c86-bb21-e7148af31d4e)
![Screenshot 2025-06-23 221942](https://github.com/user-attachments/assets/6d387b7e-3cc8-4fd4-a57a-b9b25b06dc77)
![Screenshot 2025-06-23 222023](https://github.com/user-attachments/assets/d6b13005-afaf-4f40-bc01-ad74d1273ad1)
![Screenshot 2025-06-23 222240](https://github.com/user-attachments/assets/8b4a1aeb-756c-4909-9a91-f6f11db49e79)

- John Doe

![Screenshot 2025-06-23 222445](https://github.com/user-attachments/assets/e4f1f659-e72d-4316-8d24-083840a0258e)
![Screenshot 2025-06-23 222730](https://github.com/user-attachments/assets/c06bf046-7517-4c0e-a593-8a6a361c6c41)
![Screenshot 2025-06-23 222425](https://github.com/user-attachments/assets/e3c5b310-cb68-4534-a27d-286d8c94ef7f)
![Screenshot 2025-06-23 222945](https://github.com/user-attachments/assets/abfcf75d-5891-4451-b52d-edc988f2ca90)

6. Set up users (clients).

a. Go to the Agent Panel, choose Users, then Add New.

![Screenshot 2025-06-23 223620](https://github.com/user-attachments/assets/7ab00f80-1f95-45b9-b465-f00d77ca6579)

- Karen

![Screenshot 2025-06-23 224625](https://github.com/user-attachments/assets/aeacdb38-a185-44af-93ad-de54f0c0fe14)
![Screenshot 2025-06-23 224715](https://github.com/user-attachments/assets/1f083065-c0c5-4f31-bc8b-11fe56ca49dd)

7. Set up SLA.

a. From the Admin Panel, choose Manage & SLA.

![Screenshot 2025-06-23 224945](https://github.com/user-attachments/assets/9b247fa0-90ba-4f06-9bb9-b6429ada395f)

- Sev-A (Grace Period: 1 hour, Schedule: 24/7).

![Screenshot 2025-06-23 225248](https://github.com/user-attachments/assets/4b378534-6598-489f-b652-392568562ee6)

- Sev-B (Grace Period: 4 hours, Schedule: 24/7).

![Screenshot 2025-06-23 225445](https://github.com/user-attachments/assets/e43f66d3-71d4-45b7-8ae9-e9b139bbd746)

- Sev-C (Grace Period: 8 hours, Business Hours).

![Screenshot 2025-06-23 225537](https://github.com/user-attachments/assets/ceab07d6-e0b9-4984-a452-ecff3f46717f)
![Screenshot 2025-06-23 225624](https://github.com/user-attachments/assets/c391f14a-d826-48ef-b0b1-06fed53d884f)

8. Set up Help Topics for when people submit a ticket.

a. Go to the Admin Panel & choose Manage & Help Topics.

![Screenshot 2025-06-23 233144](https://github.com/user-attachments/assets/191f54b6-4de1-422b-9c43-ebd00157d6bb)

- Business Critical

![Screenshot 2025-06-23 233559](https://github.com/user-attachments/assets/0fbaa0be-833a-4767-a2ac-0a241a1780fa)

- Personal Computer Issues

![Screenshot 2025-06-23 233751](https://github.com/user-attachments/assets/0a67d651-3272-4df9-9e43-b4428ab6787f)

- Equipment Request

![Screenshot 2025-06-23 233902](https://github.com/user-attachments/assets/2e51aeea-8341-41ce-be98-a72048ca0c5d)

- Password Reset

![Screenshot 2025-06-23 234032](https://github.com/user-attachments/assets/feacf4ed-dce0-454e-b3e7-a464adf4f37c)

- Other

![Screenshot 2025-06-23 234138](https://github.com/user-attachments/assets/4a4c456a-a0b2-4e91-8e25-34e0fc538604)
![Screenshot 2025-06-23 234232](https://github.com/user-attachments/assets/5949e942-ffb0-4b8e-97c4-e0a4b0b2c302)

