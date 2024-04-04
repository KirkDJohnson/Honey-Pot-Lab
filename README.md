<h1>Honeypot Lab</h1>



<h2>Description</h2> This lab involved me creating a live honeypot sever using Vultr to create the instance and T-Pot for the honeypot. After launching the server with the desired configureation I needed to make a firewall group for the server to ensure only I would enter the admin and webpage for the server so I it gave me hadns on expierence configuring a fireall that allows all traffic to all ports except the range of ports where the admin and other pages were. Once the firewall was configureda nf T-Pot had fullyinstalled into the sever I removed the .iso and restarted the server. After the sever restart, interacting with the terminal provided the IPs used to access the backend webpages and I logged in and went first to the attack map. The attack map shows real-time attacks against the honeypot from accross the globe. The honeypot was also configured to send logs to Kibana/ElasticSearch in which a dashboard breaksown of the attackers is displayed where I can learn more about the aorigian of the attacks or parse throuhg the logs. Lastly, I conducted some threat intelligence on the top attackers using Cisco Tallos Intelligence and found most of the being known attackers or spammers. 

<br />


<h2>Languages and Utilities Used</h2>

- <b>Vultr</b>
- <b>T-Pot</b> 
- <b>Kitbana</b>
- <b>Elastic Search</b>

<h2>Environments Used </h2>

- <b>Windows 10 </b>

<h2>Lab Overview</h2>

<p align="center">
Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/b4e28d36-b288-4d8e-adcc-096b00d79412)" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/8bd43332-6502-4c75-bf6b-affb04867073" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/b0ba5d27-2a52-4d03-aaec-3e520cb1cc40" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/fb9a268f-a3f8-4b8f-91c4-7416453fa0a9" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/f7178354-2eb5-4bc0-9d88-339b944e02c8" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/0de92319-a75f-4ba0-9610-5ac571269ad2" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/ae7c8728-3436-4d22-8f17-34279efad144" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/0032748d-b8d4-491f-a4a0-39f9c52f96ef" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/d37f619a-4ce9-4a15-b816-b8b7023f1110" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/36d86f3c-4da5-4869-b0bc-471f4682b2a1" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Text<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/bb627c34-5a5c-4606-bb7d-fab80eed26bc" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />


<h2>Thoughts</h2>
This lab was extremely fun to setup and run. It was nice to become familiar with setting up a cloud instance and was suprised at how easy it was. Thankfully, using Vultr I used a referral code to get $100 credit so completing the lab was free of charge. The highest was definitely watching the attack map live. I was actually pretty suprised at the fact the highest attacking country was the United States, I would of thought it would be Russia or China. Not only did the lab expland my knowledge of setting up a honeypot instance it also gave me hands on experience with kibana by sorting/filtering the logs that were injested from the honeypot and being able to create tables using different inputs such as source IP, destination port and so on, which would be a great skill to have in a live enviornemnt. 
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

