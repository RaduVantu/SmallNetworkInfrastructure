<h2> Network design and troubleshooting </h2>

<h3> Description </h3>

<p>The scope of this project was to design and implement (lab) a network infrastructure for a small company named Gogol.co.uk which consists of three departments: HR/Finance, Sales and Admin. </p>
<p>Each department should not be able to access any other departments and the network should also include four servers, namely Web, Email, DNS, and Common File servers, shared by all departments. The servers require additional monitoring tools in IoT form, such as server room temperature monitor and a door access solution .</p>

<p>Department workstation distribution is as follows:</P>
<ul>
  <li>Finance/HR	-	6 Computer & Printer</li>
  <li>Sales	-	52 Computers & Printer</li>
  <li>Admin	-	30 Computers & printer</li>
  <li>Wireless access	-	should be sufficient for all staff, and should not be able to communicate to any department, but should have access the web, email    and dns servers.</li>
  <li>DNS/Web/Email & File server - 4 Servers</li>
</ul>

<p>The network will be using a private IP address 71.81.91.0/24 for the company LAN and the 10.11.0.0/16 IP address for the wireless network, and should be designed with availability, scalability and inter-department security, in mind.</p>

<h3> Technology used </h3>
	- <a href="https://www.netacad.com/courses/packet-tracer">Cisco Packet Tracer</a>

<h3> Images </h3>
<br/>
<br/>
<p align="center"> 
	Subnetting table <br/>
	<a href="https://imgur.com/B0HKlbx"><img src="https://i.imgur.com/B0HKlbx.jpg" title="source: imgur.com" /></a>
	<br/>
	<br/>
	Network topology <br/>
	<a href="https://imgur.com/DikTTlZ"><img src="https://i.imgur.com/DikTTlZ.jpg" title="source: imgur.com" /></a>
	<br/>
	<br/>
	Router DHCP settings <br/>
	<a href="https://imgur.com/Vyc4xIc"><img src="https://i.imgur.com/Vyc4xIc.jpg" title="source: imgur.com" /></a>
	<br/>
	<br/>
	Distribuution layer Switch1 trunking <br/>
	<a href="https://imgur.com/XWtVcNN"><img src="https://i.imgur.com/XWtVcNN.jpg" title="source: imgur.com" /></a>
	<br/>
	<br/>
	Host can communicate intra-department, but not inter-departments <br/>
	<a href="https://imgur.com/5ZNrBrd"><img src="https://i.imgur.com/5ZNrBrd.jpg" title="source: imgur.com" /></a>	
</p>
