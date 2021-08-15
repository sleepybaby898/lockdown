# lockdown
A home webserver.

## Installation
Note: the installation guide will only go through how to host lockdown, not how to run it using apache etc.

1. Open your terminal of choice and type: ```git clone https://github.com/oblicue/lockdown.git && cd lockdown && nvim index.html``` (replace nvim with your editor of choice, e.g ```code```
2. Go through the file until you find a json table called users. (approx. line ```165```
3. Replace the username with your username of choice, and the password with an md5 encrypted password. The password should be lengthy and complicated so it is not easy to crack if somebody comes across the webserver.
4. Find the div with the id of ```loggedin```. Add any elements you would like into this div. I would not reccommend adding anything which is very powerful (e.g turn off the power at your house) as lockdown can be hacked relatively easily. The goal of lockdown is to be minimal and fit all into one file, not to be super secure.
5. Done! Run lockdown somehow (reccomend using apache) and you are done! Lockdown works on all devices so you can run it on your phone etc.
