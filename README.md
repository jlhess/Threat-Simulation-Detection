<h1>Threat Simulation and Detection</h1>


<h2>Description</h2>
This project demonstrates a comprehensive hands-on lab focused on simulating real-world cyber threats and engineering effective detection and response mechanisms. The primary goal of this project was to gain practical experience in adversary simulation, endpoint detection and response (EDR), and detection engineering while leveraging industry-standard tools and techniques.
<br />
<br />
Credit to <a href="https://blog.ecapuano.com/p/so-you-want-to-be-a-soc-analyst-intro">Eric Capuano</a> for writing the original guide! I had a lot of fun with this and particularly enjoyed the payload name sliver generated. 😂
<br />


<h2>Languages and Utilities Used</h2>

- <b>PowerShell</b> 
- <b>Bash</b>
- <b>Sysmon</b>
- <b>LimaCharlie</b>
- <b>Sliver</b>
- <b>YARA</b>

<h2>Environments Used </h2>

- <b>Windows 10</b>
- <b>Ubuntu Server 22.04</b>

<h2>Proof of Concept:</h2>

<p align="center">
 <b>Generate and dowload C2 payload:</b> <br/>
<img src="https://imgur.com/nvUwjzK.png" height="80%" width="80%" alt="C2 Generation"/>
<br />
<br />
<img src="https://imgur.com/P0DzN5G.png" height="80%" width="80%" alt="C2 Download"/>
<br />
<br />
<img src="https://imgur.com/n1mwAft.png" height="80%" width="80%" alt="Established"/>
<br />
<br />
<br />
 <b>Observe EDR telemetry:</b>  <br/>
<img src="https://imgur.com/Uwh02y4.png" height="80%" width="80%" alt="Processes"/>
<br />
<br />
<img src="https://imgur.com/S2GrFRX.png" height="80%" width="80%" alt="Network"/>
<br />
<br />
<img src="https://imgur.com/uPN4kGY.png" height="80%" width="80%" alt="Timeline"/>
<br />
<br />
<br />
 <b>Process dump:</b>  <br/>
<img src="https://imgur.com/DceIvVD.png" height="80%" width="80%" alt="procdump"/>
<br />
<br />
 <b>Create detection and response rule:</b>  <br/>
<img src="https://imgur.com/JeBSzSb.png" height="80%" width="80%" alt="Detection"/>
<br />
<br />
<img src="https://imgur.com/BZ98UP4.png" height="80%" width="80%" alt="Rule"/>
<br />
<br />
<img src="https://imgur.com/igzeg4X.png" height="80%" width="80%" alt="Alert"/>
<br />
<br />
<br />
 <b>Deletion of volume shadow copies command to generate detection:</b>  <br/>
<img src="https://imgur.com/5Srduwn.png" height="80%" width="80%" alt="vssadmin delete shadows /all"/>
<br />
<br />
<br />
 <b>D&R rule creation to block deletion:</b>  <br/>
<img src="https://imgur.com/pivvmlc.png" height="80%" width="80%" alt="Rule creation"/>
<br />
<br />
<br />
 <b>Attempt blocked!:</b>  <br/>
<img src="https://imgur.com/e0LZBWz.png" height="80%" width="80%" alt="Blocked"/>
<br />
<br />
<br />
 <b>YARA Sliver signature rules:</b>  <br/>
<img src="https://imgur.com/l6k69nm.png" height="80%" width="80%" alt="YARA"/>
<br />
<br />
<br />
 <b>YARA detection rules:</b>  <br/>
<img src="https://imgur.com/F21EGC3.png" height="80%" width="80%" alt="YARA detection"/>
<br />
<br />
<br />
 <b>Alert generation:</b>  <br/>
<img src="https://imgur.com/FzcjJyJ.png" height="80%" width="80%" alt="Changing path to generate alert"/>
<br />
<br />
<img src="https://imgur.com/8xQQU6S.png" height="80%" width="80%" alt="Detected"/>
<br />
<br />
<br />

</p>
