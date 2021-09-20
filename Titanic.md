# Titanic 

challenge's desecription: Tee-Tech is a rising cyber security organization which creates tools and provide cyber security solution to it's clients, but are they themself secure enough? 

# Examming the website
There is (/robots.txt). And in robots.txt, we can see (/server-status).

But we can't go to (/server-status). I spend a lot of time by finding way to bypass the forbidden in apache web server.

And then i am also trying sql injection on (/admin.php).

But i saw the (/urlcapture.php). This service can capture the screenshot of webpage. Cool!.

# Solution
i tried to see the web page of (/server-status). But we can only see blank in (captured.png).

But i remember that the website's server is apache. I think i don't need to explain more about apache.

So i tried (http://localhost/). It was blank too. but when i tried (http://localhost/server-status/), we got it. (but not flag).

We can see the admin's username and password with (GET) request. 

(by the way, If you don't understand why login is requested by (GET), you can read here. (https://security.stackexchange.com/questions/147188/is-it-bad-practice-to-use-get-method-as-login-username-password-for-administrato)

admin's user and pass: root:EYNDR4NhadwX9rtef

We can login with this in (/admin.php) and we got our flag. Nice challenge.

# flag
flag{88269d5ef52a5ee961ea6449e1b610a9}

# Thanks!
