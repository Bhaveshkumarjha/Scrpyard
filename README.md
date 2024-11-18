# Scrpyard
Scrpyard is online E-Commerce Website to Buy and Sell Products, User Can Share Product, and Buy Product. It has the feature of Cart, where user can checkout. Scrpyard is integrated with Razorpay.
![image](https://github.com/user-attachments/assets/83d47df4-5c29-4610-ad54-ce6aada7116b)
w to set-up locally"

cd scrpyard
Now install dependencies

cd backend
npm install

cd ..

cd frontend
npm install
now make your setup .env

cd ..
cd backend
mv .env.example .env
Paste the MongDB link, and If need also add your Razarpay API KEY and SECRET.

Now start the server.

node server.js
open new terminal in project folder

cd frontend
npm start
Done, Now Open localhost:3000 in your browser.
