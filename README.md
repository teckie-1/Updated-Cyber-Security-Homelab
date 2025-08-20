*Updated August 20, 2025*

*<h1>Homeserver_2025 | The most recent iteration</h1>*  

 
  I would say that i started my home lab journey a little over a year ago, and i have to be completely honest.. it is extremely addicting! My home "cyberlab" started out on my labtop for learning cyber security and linux. I started it on a 2023 MacBook Pro. After a month or so, I remember watching tons of YouTube videos on home labs and decided that I wanted to try to expand my lab by integrating another computer into it. After a lot more YouTube videos I was able to place my gaming laptop into the setup. It is a 2023 Razer Blade 16.

## Brief timeline

  Fast forward a few months and I decided to buy a Lenovo thinkpad t480 and sell the Mac so that I could really dive deep into Linux and the world of cyber security. I guess I could of made it easier on myself but chose not to, I dove head first into Arch Linux. (I Use Arch BTW) 

  Getting in the time machine again and here we are. I am working on a Bachelors degree in Cybersecurity and Information Assurance at WGU, transferring from my local community college where i was studying Computer Science. I run Arch with SwayFX as my daily driver and I Have a new "cyberlab"

## Bigger and better

  My cyberlab consists of a desktop server with a X99 motherboard, i7 CPU, rtx GPU (I don't remember the exact name right now, sorry), 3TB HDD, and 512GB SSD. I know I know, I have only one hard drive but I just got bought it from a friend without any prior warning so, Ill get more storage for it later on. 

  I am running TrueNAS Scale on it, instead of Proxmox like my previous setup. I think I actually like this it better this way. I was having a lot of problems on Proxmox with getting things like Home Assistant setup correctly. 

  So far I am hosting Home Assistant, Ollama, Tailscale, and Nextcloud (I'm making a cloud for my family). I am also looking into making a VLAN to rebuild the cyberlab for cybersecurity testing. I have been focused more on the red teaming side of things with, practicing on CTF's (not to good at it yet), a few Hackthebox machines and overthewire wargames. 

## Whats next 

  Besides all of that I would still like to know the defensive side of cybersecurity as well, so I plan on doing some research on how to get a SIEM set up correctly. I have been debating on weather I should also create a VM on the server just for learning or continue to run a kali VM on my daily driver and ssh into the lab. With so much going on with the server I kind of feel like it would make things a little less complicated if I went with the server lab. But at the same time, I should also keep kali on my thinkpad for when I am practicing the pentest process. 

More to come...
  
  *prime* 


---

<h1>Cyber-Security-Homelab</h1>

Building My Updated Cybersecurity Home Lab
Overview

As I continue developing my cybersecurity skills, I’ve upgraded my home lab to create a secure and controlled testing environment. My goal is to simulate real-world attack scenarios while maintaining an isolated network for safe practice.
How I Built the Lab

To correctly set up my lab, I learned from YouTube tutorials and applied what I watched through hands-on experimentation. This helped me understand:

    Setting up QEMU/KVM to run Kali Linux on Arch Linux.
    Using VMware Workstation Pro to host vulnerable machines on a separate Windows 11 laptop.
    Configuring networking to allow VMs to communicate securely.
    Writing Bash scripts to switch between an isolated bridged network and NAT for internet access.

While I was able to set up the lab successfully, I know there’s still so much to explore. Cybersecurity is a vast field, and I approach each new challenge as an opportunity to improve my skills.
Lab Setup
Attack Machine:

    ThinkPad T480 (Arch Linux)
    Kali Linux on QEMU/KVM for penetration testing

Target Environment:

    Windows 11 laptop running VMware Workstation Pro
    Hosting various vulnerable machines for testing

Networking Configuration:

    Bridged Network: Allows direct communication between VMs for realistic attack scenarios.
    NAT Network: Used when internet access is required for updates.
    Custom Bash Scripts:
        One script switches from bridged (isolated) to NAT (internet access).
        Another script restores the bridged network for safe testing.

Lessons Learned & Next Steps

This project reinforced my skills in virtualization, networking, and automation. Through troubleshooting and refining my setup, I improved my understanding of:

    Configuring virtualized environments for cybersecurity testing.
    Managing network isolation for security and controlled testing.
    Automating tasks with Bash scripting.

I still have plenty to learn, but building hands-on projects like this has been the best way to grow my skills. My next steps include:

    Adding more Windows and Linux vulnerable machines for testing.
    Automating additional lab setup and maintenance tasks.
    Exploring Capture-the-Flag (CTF) challenges to apply my skills in real-world scenarios.
