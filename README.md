You've revised the useState hook. You've also learned about working with primitive (string) data and with complex data (state stored in objects).

In this code lab, you'll practice updating the state stored in an object, based on the user interacting with the app.

This code lab's app shows a Gift Card page of the Little Lemon Restaurant web app, where a visitor initially has a Gift Card that they can use to have a dinner for four.

Note: If you run npm start and view the app in the browser you'll notice that the starting React app works as is.

The starter code shows the following information on the screen:

Gift card page for a customer
In other words, the text that shows on the screen is as follows:

Gift Card Page 
Customer: Jennifer Smith 
Free dinner for 4 guests 
To use your coupon, click the button below.  
Spend Gift Card 

The "Spend Gift Card" button is set up to execute a function when clicked. However, that event-handling function is empty.

That means that when serving the app with the starter code, if you click the "Spend Gift Card" button, there will be no change on the screen.

Your task is to complete the event-handling function for the "Spend Gift Card" button clicks, as detailed in the steps below.

When the code lab is successfully completed, after the "Spend Gift Card" button is clicked, the UI should update to show the following information on the screen:

Gift card page for a customer
In other words, the text that shows on the screen is as follows:

Gift Card Page 
Customer: Jennifer Smith 
Your coupon has been used. 
Please visit our restaurant to renew your gift card. 
