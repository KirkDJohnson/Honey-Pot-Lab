<h1>Honeypot Lab</h1>



<h2>Description</h2> This lab involved creating a live honeypot server using Vultr to establish the instance and T-Pot for the honeypot. After launching the server with the desired configuration, I needed to create a firewall group for the server to ensure that only I could access the admin and webpage for the server. This provided hands-on experience in configuring a firewall that allows all traffic to all ports except for the range of ports where the admin and other pages were located. Once the firewall was configured and T-Pot was fully installed into the server, I removed the .iso and restarted the server. After the server restart, interacting with the terminal provided the IPs used to access the backend webpages. I logged in and first went to the attack map, which shows real-time attacks against the honeypot from across the globe. The honeypot was also configured to send logs to Kibana/ElasticSearch, where a dashboard breakdown of the attackers is displayed, allowing me to learn more about the origin of the attacks or parse through the logs. Lastly, I conducted some threat intelligence on the top attackers using Cisco Talos Intelligence and found that most of them were known attackers or spammers.

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
Creating the server instance on Vultr part 1<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/b4e28d36-b288-4d8e-adcc-096b00d79412)" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Creating the server on Vultr after uploading and selecting the T-Pot .iso <br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/8bd43332-6502-4c75-bf6b-affb04867073" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Creating a firewall group to only allow my IP to access the specified port range for Vultr severs while allowing all other traffic on all ports<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/b0ba5d27-2a52-4d03-aaec-3e520cb1cc40" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Launching the server and configuring T-Pot<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/fb9a268f-a3f8-4b8f-91c4-7416453fa0a9" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
After the server launched and I configured T-Pot I removed the .iso from the server<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/f7178354-2eb5-4bc0-9d88-339b944e02c8" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
After the server launched, interacting with the terminal would provide me with the information to access the server webpage (hxxps[://]149[.]28[.]208[.]132:64297) <br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/0de92319-a75f-4ba0-9610-5ac571269ad2" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Logging into the honeypot webserver, I first went to the attack map where I could see attacks against the server in real-time<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/ae7c8728-3436-4d22-8f17-34279efad144" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Showing the logs generated from the honeypot populate a kibana dashboard to allow futher investigation into the attacks<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/0032748d-b8d4-491f-a4a0-39f9c52f96ef" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Lists the IPs of the top attackers to the sever in a table<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/d37f619a-4ce9-4a15-b816-b8b7023f1110" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
Conducted threat intelligence on the top attackers with Talos Intelligence showing the standings of the IPs<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/36d86f3c-4da5-4869-b0bc-471f4682b2a1" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />
In Kibana practiced sorting and parsing logs with the ingested logs from the honeypot<br/>
<img src="https://github.com/KirkDJohnson/Honey-Pot-Lab/assets/164972007/bb627c34-5a5c-4606-bb7d-fab80eed26bc" height="80%" width="80%" alt="Honey Pot Lab"/>
<br />
<br />


<h2>Thoughts</h2>
This lab was incredibly enjoyable to set up and run. It was rewarding to gain familiarity with configuring a cloud instance, and I was pleasantly surprised by how straightforward the process was. Fortunately, I utilized a referral code with Vultr, which provided me with $100 credit, making the completion of the lab entirely cost-free. One of the highlights was observing the attack map in real-time. I was genuinely astonished to find that the United States emerged as the top attacking country. I had expected it to be Russia or China. This lab not only expanded my understanding of setting up a honeypot instance but also provided hands-on experience with Kibana. I was able to sort and filter the logs collected from the honeypot, and create tables using various parameters such as source IP and destination port. These skills would undoubtedly be invaluable in a live environment.
<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>

