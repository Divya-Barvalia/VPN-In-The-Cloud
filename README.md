<h1 align="center">🌐 Cloud-Based VPN with AWS & OpenVPN</h1>

<p align="center">
  A practical lab deploying a secure, free VPN server in the cloud using Amazon Web Services and OpenVPN for encrypted traffic tunneling.
</p>

<hr/>

<h2>🚀 Summary</h2>

<p>
  In this lab, I deployed a functional VPN server in the cloud using OpenVPN on an AWS EC2 instance. This allowed for private, secure web browsing by routing all client traffic through the VPN tunnel. The project included server setup, client connection, and testing IP anonymization via cloud infrastructure.
</p>

<hr/>

<h2>🛠️ Deployment Overview</h2>

<ol>
  <li>
    Launched an EC2 instance on AWS and installed the OpenVPN Access Server.<br/>
    <img src="screenshots/step1.png" alt="Launching OpenVPN Server" width="600"/>
  </li>
  <li>
    SSH’d into the server, completed the setup script, and generated an admin login password.<br/>
    <img src="screenshots/step2.png" alt="SSH into EC2 and Configuration" width="600"/>
  </li>
  <li>
    Accessed the OpenVPN web admin portal at <code>https://13.59.177.129:943/admin/</code> using the credentials.<br/>
    <img src="screenshots/step3.png" alt="Admin Web Portal" width="600"/>
  </li>
  <li>
    Configured the server to tunnel all client traffic through the VPN (full tunnel setup).<br/>
    <img src="screenshots/step4.png" alt="Tunnel Configuration" width="600"/>
  </li>
  <li>
    Connected to the client side by visiting the user portal with the same credentials.<br/>
    <img src="screenshots/step5.png" alt="Client Connection" width="600"/>
  </li>
  <li>
    Downloaded and installed the OpenVPN Connect client on my Windows 11 Home Desktop.<br/>
    <img src="screenshots/step6.png" alt="Windows Client Installation" width="600"/>
  </li>
  <li>
    Activated the VPN and verified the connection was active by checking the public IP.<br/>
    <img src="screenshots/step7.png" alt="VPN Status Check" width="600"/>
  </li>
  <li>
    Successfully confirmed that my IP matched the VPN server’s IP, proving encrypted routing was working.<br/>
    <img src="screenshots/step8.png" alt="IP Confirmation" width="600"/>
  </li>
</ol>

<hr/>
