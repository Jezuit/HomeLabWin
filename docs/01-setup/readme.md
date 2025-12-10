# Installation

1. I downloaded **Microsoft Windows Server 2022** from official page
2. I downloaded **Oracle VirtualBox** as my Virtual Machine to get second operating system
3. I added a new operating system without choosing ISO image because of Microsoft Software License Terms issue and I did excatly like in [this video](https://www.youtube.com/watch?v=fjQ-9UBzk6k)
4. I gave 4GB RAM, 3D acceleration with 128MB Video Memory, 60GB Virtual Siza
5. I opened Windows to check if everything is working fine
6. Then I create a Admin acc with stong password
7. I turned off machine


---
# Network Configuration

1. For my HomeLab the best solution for network is to set two network cards as NAT adapter (for windows uptades only) and Only-Host Adapter
2. First I had to check if vitual "cabel" exists, so I checked it (virtualbox -> file -> tool -> network) and I see there that "VirtualBox Host-Only Ethernet Adapter" exists
3. I disabled DHCP because I want Windows Server to be DHCP server I not want vitualbox to encumber
4. Now I opened WinServer settings to configure hardware
5. (settings -> network -> Adapter 1) [*] Enable Network Adapter | Attached to: **NAT**
6. (settings -> network -> Adapter 2) [*] Enable Network Adapter | Attached to: **Host-Only Adapter** | Name: **VirtualBox Host-Only Ethernet Adapter** (Same as in step 2)
7. 
