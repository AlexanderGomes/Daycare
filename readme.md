## Daycare Project with MERN stack

this applications is a personal daycare system that I did for my family.

Visit on: <a href='https://gomesdaycare.herokuapp.com'>www.gomesdaycare.com</a>


## Functionality

clients are required to sign to the website so they can get charged on the daily basis.

the client can do the followings:
1. create a schedule ahead of time and pay for it.
2. see what dates the daycare won't be open (if something happens).
3. check past payments and pending balance.
4. pay for all the schedules through stripe.

the admin can do the followings:
-- check-in clients when arriving at the daycare, which creates a charge of $35 on their account, and sends them a message of confirmation.

-- check-out clients when picking up their kids, if the check-out is done anytime after 6:15 PM, $15 more will be added to their balance, and sends them a message of confirmation.

-- 10 days after the due date the client receives a text message through twillio saying that their account will be blocked in 5 days.

-- keeps track of the total balance of each user.

-- set unavailable dates so clients can see on their calendars.

-- generates the code for the registration of each user and other admins if necessary.

<img width="1040" alt="dashboard" src="https://user-images.githubusercontent.com/98370540/216496234-2a92e76f-51a6-4109-901e-488f16a5ea64.png">


## How to start the Applications

1. Run npm install from the root directory
2. cd into frontend and run npm install
3. from the root directory run the followings:
4. npm run server
5. npm run client
