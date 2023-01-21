# HackTheBox Pre-requisites
To play HackTheBox, you have to connect to their servers over a VPN. There are two options: OpenVPN, which is free, and Pwnbox, which is not. Below are instructions for installing OpenVPN and creating a HackTheBox OpenVPN profile.

# Creating a VPN Profile
1. Log into your HackTheBox account at [HackTheBox.com](https://app.hackthebox.com/). If you do not have an account, create one (and verify your email!).
2. Click on the red "*Connect to HTB*" button in the top-right corner.
3. Click on "*Starting Points*".
4. Click on "*OpenVPN*" and configure the following settings: 
- VPN Access: "*US - Starting Point*"
- VPN Server: "*US StartingPoint 1*"
- Protcol: "*TCP 443*"
5. Click "*Download VPN*" to download your OpenVPN profile. The profile will be used by
OpenVPN to connect you to the HackTheBox servers

# Installing and Configuring OpenVPN
1. You can install OpenVPN [here](https://openvpn.net/vpn-client/). The download is blocked on campus wifi, but you can use a VPN
or alternative download:
- [Alternative Windows download](https://drive.proton.me/urls/P7HR61JVW0#vUTeFQhJxnSq) 
- [Alternative Mac Download](https://drive.proton.me/urls/MA7VQZ6FKR#8fiN1b63R92e)
2. Run the installer and open OpenVPN
3. You should be greeted with an "*Import Profile*" tab. Select the "*File*" option at the top and then drag the OpenVPN profile you downloaded from HackTheBox onto the GUI.
4. Click the orange "*Connect*" in the bottom left and you're ready to play some HackTheBox :)
5. To play, visit any HackTheBox challenge and click "*Spawn the machine*". If the button
is grayed out, refresh the page. If the button is still grayed out, make sure you're
connected to the VPN.
