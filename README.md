# Default Free Subscription
Had created default subscription with Sudip
## Creating new Domain 
- By default when I login with my outlook email, at right hand corner it shows my email id. If I do for myself its Ok, but if I am going to create videos - that's not ok for me as it displays my email id.
- So, its better I should use a different domain - the way I did gogates domain while creating Active - Active cluster. If we check those videos, we had a seperate VM for it wherein I had installed Active Directory and Domain Services and then create a domain and added 2 users - magogate & dgogate.
- I will try to replicate same thing here in Azure. I don't need to install AD here, as its already available. So I did following.
1. After logging with my outlook account, I click on "All Services"
![image](https://user-images.githubusercontent.com/45523211/176974067-3c2cc56f-2d69-4aba-aa38-4bba5b0a5710.png =250x250)

2. Then under Identity category - select "Azure Active Directory"
![image](https://user-images.githubusercontent.com/45523211/176974114-ce74a3c7-b7d0-42c5-8989-41458cf00dff.png =250x250)

3. In order to create a new Domain - click on "Manage Tenants"
![image](https://user-images.githubusercontent.com/45523211/176974155-8380edba-dae1-42af-a417-c44efef3d8c4.png =250x250)

4. Click on Create --> Select Azure Active Directory --> Click On Configuration
5. Specify Organization Name & Domain Name
![image](https://user-images.githubusercontent.com/45523211/176974984-f0636284-86e1-4767-8cf2-4ca87502b838.png =250x250)
6. Click create after Validation is Passed
![image](https://user-images.githubusercontent.com/45523211/176975031-f720348c-2df5-495b-aa41-9c8e8b696a27.png =250x250)
7. It will take a while (few seconds) to get it created. You will need to fill the Captcha at right side though.
8. Go back to Active Directory and click on Manage Tenants and following screen will appear
![image](https://user-images.githubusercontent.com/45523211/176975184-3a4603a2-00ca-437a-ae72-ab311df5f39b.png =250x250)
9. Select newly created domain gogates and click on Switch
![image](https://user-images.githubusercontent.com/45523211/176975200-78065375-78bf-4a5e-8436-d7497a99b508.png =250x250)
10. Once you do that, you will be redirected to Gogates domain instead of Default Domain
11. So the domain is created, let's create a new user - magogate (this is my cisco user id, first corporate id when I started my career in 2007, hence my favourite)
![image](https://user-images.githubusercontent.com/45523211/176975301-82e3ce21-b8e0-44fa-ac2b-4ef28b499662.png =250x250)
12. Add user info
![image](https://user-images.githubusercontent.com/45523211/176975375-be1295e0-9961-42d9-912a-1a982a8bd4a1.png =250x250)
13. You will see new user got created - magogate@gogates.onmicrosoft.com
![image](https://user-images.githubusercontent.com/45523211/176975428-ca226c42-4af3-4f6f-b61b-f8527efe41d5.png =250x250)
14. Now - login with new user and it will again ask you to reset the password. as its a first login.

