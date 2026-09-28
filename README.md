# networkingpractice

The first step was to get hardware on a budget.
I found an old Dell Optiplex on Marketplace for $60. It had an old 8th gen i5 processor and 8 gigs of DDR3 ram. I figured "why not?"
I had some hard drives lying around, so I took apart the computer, cleaned everything, put new thermal paste on, and put it all back together with my drives.
I chose a 500gb SSD for the OS, which I eventually landed on Ubuntu Server.
After downloading the ISO, booting up the Dell, and installing Ubuntu Server, I found that I couldn't get the SSD to boot. This turned out to be a simple problem in the BIOS with Legacy and UEFI booting. After turning Legacy off, it booted right into the server.
I installed Docker and CasaOS to have a front end to work a little easier from. However, the only drive detected was the 500gb SSD.
For this, I ran a few simple commands to find the drives and reconfigured them so CasaOS could see them properly. I now had several terabytes of storage available.
I downloaded and ran Immich for a photo backup on the server, which I connected to my phone as a test. I ran into a few small issues, but nothing serious enough to prevent fixing immediately.
At that point, I realized that my ip address had changed for the server, so I went into the router settings and gave the server a static IP address, reserving the address by altering the DHCP settings.
I then installed NextCloud and Tailscale. Tailscale allowed me to access the server via VPN from anywhere without having to open any ports on the server itself.
I installed a switch between the router and the server due to the server's location, which allowed me to connect various security cameras to the network as well.
At this point, I am working on setting up a Minecraft server for my son and his friends to play on more privately.
I have plans to upgrade this server and put a UPS system before making it available to my whole family for photo and video backups.
I also plan on experimenting with website hosting, likely via Apache in the near future.
I am also working on various VPN setups and experimenting daily with different configurations and will be testing different server operating systems.
