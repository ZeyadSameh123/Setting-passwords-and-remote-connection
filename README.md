# Setting-passwords-and-remote-connection

# Description

The project demonstrates practical switch management using CLI, focusing on secure password handling and protecting network configurations. The main objective is to ensure that password are encrypted and not visible in plain text.

# Tools Used
- Cisco Switch
- Laptop
- Console cable
- CLi(Commend Line Interface)

# What I Did

- Set an initial password on the switch using enable secret.
- configuration line VTY Password
- Checked running configuration and noticed password were visible
- Configured VLAN 1 with an IP address
- Tested remote connection via telnet from the laptop
- Activated service password-encryption to hide the password

# Steps

1- Set Password on switch
  - <img width="855" height="839" alt="Screenshot 2026-03-29 221925" src="https://github.com/user-attachments/assets/3167756c-1d45-4934-8775-137dc09f241d" />
  - <img width="873" height="844" alt="Screenshot 2026-03-29 222021" src="https://github.com/user-attachments/assets/58583167-abd5-4298-9f7d-eead75a28c03" />
  - Password was visible

2- Configure IP on VLAN 1
  - <img width="859" height="777" alt="Screenshot 2026-03-29 222209" src="https://github.com/user-attachments/assets/e0b08fe8-0da1-4538-bb55-8565674504a4" />
  - <img width="851" height="781" alt="Screenshot 2026-03-29 222228" src="https://github.com/user-attachments/assets/571921ad-1f36-47ba-bd13-65fbec2668b4" />
  - IP appeared, password still visible

3- Test remote connectipn via telnet
  - <img width="849" height="449" alt="Screenshot 2026-03-29 235111" src="https://github.com/user-attachments/assets/6a36a8a9-bbb1-4a8e-b9d6-d642a46b18fe" />
  - Connection timeout, remote host not responding

4- Encrypt Password
  - <img width="850" height="776" alt="Screenshot 2026-03-29 222425" src="https://github.com/user-attachments/assets/b6cd730e-7f08-4957-86b7-27c7c826cc16" />
  - <img width="853" height="783" alt="Screenshot 2026-03-29 222446" src="https://github.com/user-attachments/assets/90c6dd35-8a4b-45c2-b250-e5717922252d" />
  - Password is now hidden and displayed as symbols

# Result  

- Successfully hod the passwoed using service password-encryption
- Ip configuration works,but password are now secure and not visile text
- Screenshot of encrypted password 

