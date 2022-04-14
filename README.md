# SecureOS - OUTDATED

![](https://cdn.discordapp.com/attachments/825669056719355908/836550783066701824/SecureOS_Black.png)

#### Intro
SecureOS is an open-source Linux Distribution based on Debian.
It works on any Raspberry Pi.
SecureOS is a modifed version of the Raspberry OS Lite (no gui)

I did it because many users did not set any security precautions. SecureOS comes with pre-installed software that protects the system from Hackers and 3rd-party persons that want to abuse the system

#### Features
SecureOS comes with various pre-installed security programs that help to secure the system.

- Changed Login data (Login data at the end)
- Fail2Ban (After 3 times entered bad password the IP will be blocked)
- Uncomplicated Firewall (Default: opened SSH)
- Unattended Upgrades (automatical updates)

#### Installation
1. Download the Image file
2. Flash the image on a microSD card using Balena Etcher (or something else)
3. Put the microSD Card into your Pi
4. Boot
5. Type in `sudo apt-get update -y && sudo apt-get upgrade -y`
6. Change password using `passwd`. Type in your new password.
7. After you changed the password you are ready to go!

#### More Security tips
1. Dont open any ports without knowing what you are doing!
2. Do updates regularly
3. [Tips for a strong password](https://its.lafayette.edu/policies/strongpasswords/ "Tips for a strong password")

#### Login Data
User: `secureuser`
Password: `AcUB#6N%U9AJT6ks` (change after boot!!!)
[Tips for a strong password](https://its.lafayette.edu/policies/strongpasswords/ "Tips for a strong password")

#### Contact me
If something isnt working or you need help you can write me a message on following platforms:

- Discord: Renax#6191
- Instagram: [@renax187](https://www.instagram.com/renax187/ "@renax187")
