<h1>Installing Apache Web Server on AWS EC2 Instance</h1>

<h2>Description</h2>
The process ranges from launching an instance to configuring Apache to serve web pages, including updating system packages, installing Apache, and ensuring the necessary security group rules are in place for HTTP traffic. This video is useful for beginners setting up a basic web server on AWS.
<br />


<h2>Languages and Utilities Used</h2>

- <b> Shell scripting (Bash)</b> 
- <b> apt (for package management), apache2 (webserver), ssh (for secure access), and basic Linux commands.</b> 

<h2>Environments Used </h2>

- </b> Operating System: Ubuntu Linux (running on an AWS EC2 instance)</b>
- </b> Cloud Platform: Amazon Web Services (AWS EC2)</b>
-</b> Network Configuration: Security groups to enable HTTP (port 80) and SSH (port 22) traffic</b>

<h2>Program walk-through:</h2>

<p align="center">
Launch an EC2 Instance/Create a key pair/: <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733561045/Screenshot_2024-12-07_004153_fwaxcj.png"/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733561150/Screenshot_2024-12-07_004310_xuvl5j.png"/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733561362/Screenshot_2024-12-07_004539_jdells.png"/>
<br />
<br />
Configure Security Groups: <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733562501/Screenshot_2024-12-07_011714_m4a8ac.png"/>
<br />
<br />
Access Instance: <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733562687/Screenshot_2024-12-07_004609_euvxhi.png"/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733562810/Screenshot_2024-12-07_041306_thduq9.png"/>
<br />
<br />
Update Packages:  <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733563516/Screenshot_2024-12-07_005613_ceetlr.png"/>
<br />
<br />
Install Apache:  <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733563570/Screenshot_2024-12-07_005706_yuxkvu.png"/>
<br />
<br />
Check Apache:  <br/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733563949/Screenshot_2024-12-07_005941_h3cwz1.png"/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733564252/Screenshot_2024-12-07_005814_p3r94j.png"/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733564408/Screenshot_2024-12-07_014201_rpz83g.png"/>
<img src="https://res.cloudinary.com/dk3bkl3ji/image/upload/v1733564529/Screenshot_2024-12-07_014144_w0psac.png"/>
<br />
<br />

<!--
 ```diff
- text in red
+ text in green
! text in orange
# text in gray
@@ text in purple (and bold)@@
```
--!>
