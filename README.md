# Lock-System-Project

***Lock System is an authenticated Locking System*** in which user Register new Door(Lock) with his Account. 


## Click Below Image to watch full video 👇

[![IMAGE ALT TEXT HERE](https://img.youtube.com/vi/0MjGroM0Yys/0.jpg)](https://www.youtube.com/watch?v=0MjGroM0Yys)



## Opening of the Gateway

Upon Registering, user will always have to generate OTP which is generated by arduino and then OTP and door Id are send to backend from user Device( i.e. Mobile App) and at backend OTP is send to E-mail with which the door is linked.  
After the user enters the OTP, Gateway is opened !! 

## Closing of the Gateway
After the gateway is opened, An Alert is generate in App to close Lock Again the Door and user have to just press the "Lock Again" button. If User forgets to lock, then the gateway is automatically closed after few time (i.e. 10 sec, 10 mins or more. Can be set in Arduino Code) 

## Guest Login
Another Feature of this Lock System is that owner can generate temporary password which will valid for particular time( here 10  mins. Can be changed in Mobile App Code). 
Using owner username and this temporary password, anyone can login to app and can generate the OTP which will again be send to onwer's registered E-mail Address. 
After specific time, the guest account will logout.

## Github Links for Complete Project


Arduino Code => [Click Here](https://github.com/harshagrawal30/Lock_System_Arduino_Code)

Mobile App using React Native => [Click Here](https://github.com/harshagrawal30/Lock_System_React_Native_App)

Backend using NodeJs and ExpressJs => [Click Here](https://github.com/harshagrawal30/Lock_System_Backend)



**Note :** As of Now, one user account can link only one lock.  
