<h1>Updated-Cyber-Security-Homelab</h1>

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
