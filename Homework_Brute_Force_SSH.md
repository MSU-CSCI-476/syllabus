<p>Brute Force SSH Server</p>
<p>I used hydra-gtk to attack the mthack.me server located at 70.39.80.128.  I looked through the wordlists located in the /usr/share/wordlists folder and decided to download others.  I downloaded scowl and friends wordlist from sourceforge and started hydra-gtk on my home computer.  I used a several small lists to test hydra's functionality and then set up one of the larger lists to run.  After finding that the password had been changed to something easier I downloaded a list of the `10,000 most common passwords and started running hydra-gtk from my laptop.  The dictionary attack failed but the the second attempt with the most common passwords found it 10% of the way in.</p>
[Imgur](http://i.imgur.com/NrnSCk1.png)
<p>I created a sha1 of the password 'changeme' and submitted that answer 017ac53e731e11e6c2f5689cfe8ae9f3d35f6c53.  I also found a note in the test account with the hash e4e47ef058431a08d714506a09d155a58279e4ee.</p>
[Imgur](http://i.imgur.com/QTHzSM3.png)

