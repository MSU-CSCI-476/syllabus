<h1>Josh Behm's report on breaking into the ssh acount on mthack.me.</h1>
<p>I was given in advance that the user name for the ssh acount was test. First to find the ip address of the website I used the ping command in the windows 7 command prompt. This gave me that the ip address was 70.39.80.128. I started up metasploit through the msfcounsle and used the ssh_login Check Scanner to brute force the password. The enteries I had for the ssh_login were test for the username, 70.39.80.128 for the ip address, and ipmi_passwords.txt for the password list.This then found that the password for the ssh account test was changeme. After logging in I was greated with a message that said that test was not authorized to connect to the localhost.localdomain and gave me the flag e4e47ef058431a08d714506a09d155a58279e4ee. the image below is a screen shot of when I succeded in connecting to the ssh account.</p>
![alt text](https://cloud.githubusercontent.com/assets/8918773/5893676/a53efe1a-a4aa-11e4-9a4c-c2f503474805.png "Logo Title Text 1")



