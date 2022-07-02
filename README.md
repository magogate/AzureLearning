# Default Free Subscription
Had created default subscription with Sudip
## Creating new Domain & User
- By default when I login with my outlook email, at right hand corner it shows my email id. If I do for myself its Ok, but if I am going to create videos - that's not ok for me as it displays my email id.
- So, its better I should use a different domain - the way I did gogates domain while creating Active - Active cluster. If we check those videos, we had a seperate VM for it wherein I had installed Active Directory and Domain Services and then create a domain and added 2 users - magogate & dgogate.
- I will try to replicate same thing here in Azure. I don't need to install AD here, as its already available. So I did following.
1. After logging with my outlook account, I click on "All Services"
![image](https://user-images.githubusercontent.com/45523211/176974067-3c2cc56f-2d69-4aba-aa38-4bba5b0a5710.png )

2. Then under Identity category - select "Azure Active Directory"
![image](https://user-images.githubusercontent.com/45523211/176974114-ce74a3c7-b7d0-42c5-8989-41458cf00dff.png )

3. In order to create a new Domain - click on "Manage Tenants"
![image](https://user-images.githubusercontent.com/45523211/176974155-8380edba-dae1-42af-a417-c44efef3d8c4.png )

4. Click on Create --> Select Azure Active Directory --> Click On Configuration
5. Specify Organization Name & Domain Name
![image](https://user-images.githubusercontent.com/45523211/176974984-f0636284-86e1-4767-8cf2-4ca87502b838.png )
6. Click create after Validation is Passed
![image](https://user-images.githubusercontent.com/45523211/176975031-f720348c-2df5-495b-aa41-9c8e8b696a27.png )
7. It will take a while (few seconds) to get it created. You will need to fill the Captcha at right side though.
8. Go back to Active Directory and click on Manage Tenants and following screen will appear
![image](https://user-images.githubusercontent.com/45523211/176975184-3a4603a2-00ca-437a-ae72-ab311df5f39b.png )
9. Select newly created domain gogates and click on Switch
![image](https://user-images.githubusercontent.com/45523211/176975200-78065375-78bf-4a5e-8436-d7497a99b508.png )
10. Once you do that, you will be redirected to Gogates domain instead of Default Domain
11. So the domain is created, let's create a new user - magogate (this is my cisco user id, first corporate id when I started my career in 2007, hence my favourite)
![image](https://user-images.githubusercontent.com/45523211/176975301-82e3ce21-b8e0-44fa-ac2b-4ef28b499662.png )
12. Add user info
![image](https://user-images.githubusercontent.com/45523211/176975375-be1295e0-9961-42d9-912a-1a982a8bd4a1.png )
13. You will see new user got created - magogate@gogates.onmicrosoft.com
![image](https://user-images.githubusercontent.com/45523211/176975428-ca226c42-4af3-4f6f-b61b-f8527efe41d5.png )
14. Now - login with new user and it will again ask you to reset the password. as its a first login.

## Free Subscriptions
1. My free subscription ended. To validate that, go to Home --> and click on Subscriptions
2. You will see subscriptions screen as below
![image](https://user-images.githubusercontent.com/45523211/176978823-5b3fd9cc-5966-4f6c-8edb-5dde4ecdf206.png)
3. Click on Add to create new subscription
![image](https://user-images.githubusercontent.com/45523211/176978853-94702c84-6483-4222-9786-ea0152d54fdc.png)
4. My free options is gone, so I had to switch to Pay as you Go. So click on "Click here to upgrade"
5. Select Basic (which is default) option and click on upgrade.
![image](https://user-images.githubusercontent.com/45523211/177005782-63cf9feb-3bdc-46fc-badc-d67a1269c941.png)
![image](https://user-images.githubusercontent.com/45523211/177005802-faa827f7-9495-40af-ae47-3ddf7b7c5404.png)

## Creating new Sql Server
1. Go to all services --> click on SQL Servers under Database Section
![image](https://user-images.githubusercontent.com/45523211/177005851-c6892061-9c5f-4dde-83d6-994525040dbf.png)

2. Click on Create SQL Server
![image](https://user-images.githubusercontent.com/45523211/176978454-50020a34-b167-40a4-adea-32005ab2973b.png)

