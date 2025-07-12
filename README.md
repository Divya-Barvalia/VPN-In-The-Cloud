<h1 align="center">🌐 Cloud-Based VPN with AWS & OpenVPN</h1>

<p align="center">
  A practical lab deploying a secure, free VPN server in the cloud using Amazon Web Services and OpenVPN for encrypted traffic tunneling.
</p>

<hr/>

<h2>🚀 Summary</h2>

<p>
  In this lab, I deployed a functional VPN server in the cloud using OpenVPN on an AWS EC2 instance. This allowed for private, secure web browsing by routing all client traffic through the VPN tunnel. The project included server setup, client connection, and testing IP anonymization via cloud infrastructure.
</p>

<h2><p align="center">🗂️ Project Architecture</h2><p>
</p>
<p align="center"><img src="Screenshots/project-architecture.png" alt="VPN Architecture Diagram" width="300"/><p>
<hr/>

<h2>🛠️ Deployment Overview</h2>

<ol>
  <li>
    Launched an EC2 instance on AWS and installed the OpenVPN Access Server.<br/>
    <img src="Screenshots/OpenVPN-Instance.png" width="1000"/>
  </li>
  <li>
    SSH’d into the server, completed the setup script, and generated an admin login password.<br/>
    <img src="Screenshots/VPNPass.png" width="800"/>
  </li>
  <li>
    Accessed the OpenVPN web admin portal at <code>https://13.59.177.129:943/admin/</code> and logged in using the credentials.<br/>
    <img src="Screenshots/Admin-Login.png"  width="600"/>
  </li>
  <li>
    Configured the server to tunnel all client traffic through the VPN (full tunnel setup).<br/>
    <img src="Screenshots/VPN-Overview.png" width="700"/> <img src="Screenshots/VPN-Config.png" width="900"/>
  </li>
  <li>
    Connected to the client side by visiting the user portal with the same credentials.<br/>
    <img src="Screenshots/User-Login.png" width="600"/>
  </li>
  <li>
    Downloaded and installed the OpenVPN Connect client on my Windows 11 Home Desktop.<br/>
    <img src="Screenshots/VPNClient-Download.png" width="300"/>
  </li>
  <li>
    Activated the VPN and verified the connection was active by checking the public IP.<br/>
    <img src="Screenshots/VPN-Profile.png" width="300"/>  <img src="Screenshots/Running-VPN.png" width="200"/>
  </li>
  <li>
    Successfully confirmed that my IP matched the VPN server’s IP, proving encrypted routing was working.<br/>
    <img src="Screenshots/VPN-Result.png" width="700"/>
  </li>
</ol>

<hr/>
