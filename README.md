# ETHParis
Repo for ETHParis 2023

In here is only the index.html file that is uploaded to ipfs and can be used at hotparis.eth.link. 

System description: 
My project aims to create an simple, open source code that can be added on top of any API to grant access to anyone that pays up. No registration needed. Just add the code to your API and watch the money stack up! 
During setup you can define an existing address or have an new address be created. Than you need to add a good description and set the price, done! 

How it's done: 
The entire code executes in the users browser. A user that got to know that there is an amazing info he would like to have can access it through a ENS domain name and retrieve the website from IPFS. The website than prompts the user to connect his Metamask to the website. He can click a button to send the required payment. The website will wait for some seconds and check the Airstack API to get notified when a payment is received. Once the payment has successfully been received the website will request the requested information from the sensors API. That information will than be displayed. 
The User has the option to refresh the information by paying again.  
