# PasswordChecker
This is python project aimed to check if passwords have been tried by hackers. it uses CLI and it tells you how many times the password was tried.  

This project is an actual tool used for security reasons. This project is legitimately the most secure way app to check if your password has ever been hacked. So, it allows us to type in our terminal, python3 and then have a checkMyPassword.py file that is written from scratch. When the app runs, we are going to be able to input any password that we have and check if it’s ever been hacked.

Now, how this tool is built?

It is built on top of other massive database that stores usernames and passwords that have ever been hacked using REST API. We determine if username and password have leaked by dictionary attacks and when we find this attempt we initialize a brute force attack on these passwords by looping over them.

I built this app as I merely said because, I wanted to check passwords for myself without using any other web tool as they are out there, and minding that when we send a password through those apps they are stored somewhere in the word and we don’t have to trust this as when you submit for check there could be someone on the middle and intercept it. The best security is to trust no one.
So, this app is free and uses the best technique used by legitimate and expensive password managers like keeper, 1 password, Blur, sticky password that keep your password secure.

