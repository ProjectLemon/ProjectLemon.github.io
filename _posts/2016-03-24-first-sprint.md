---
layout: post
title:  "First Sprint"
dat

category: MaliciousMango
tags: [golang, angularjs]

author: Jenny Kinert
---
Earlier this month Linus wrote about our new project Malicious Mango. Today we´ve finished our first sprint. Now we can log in with an email address and we can create a new user.  
To be able to log in we validate the email address to actually be a registered user. Similarly as the email validation we control that the new user doesn’t already exists. As a letter in the mail we also got password validation when we implemented the server.  
So we have actually built a complete and rather safe sign in system. We used the scrypt hashing algorithm to hash all the password and not actually saving the password on our database (take a hint Adobe). Supposedly, scrypt is more secure than the predecessor bcrypt since it’s design to resist parallelized brute force attacks.   
We also begun on our next sprint, when done, can create profiles. It will be static though and no changes can be made. But still another step forward. Hopefully we can be done with that about a week from now.  
Happy Easter  
  
  
// Project Lemon  
![Login Desktop Prototype 1](/assets/images/login-desktop-prototype-1.png)
