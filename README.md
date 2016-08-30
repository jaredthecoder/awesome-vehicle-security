# Awesome Vehicle Security [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg)](https://github.com/sindresorhus/awesome)


*A curated list of awesome resources, books, hardware, software, applications, people to follow, and more cool stuff about vehicle security, car hacking, and tinkering with the functionality of your car.*

![](assets/car_hacking_jeep.gif)

---

I would love as much help as I can get. [Start contributing!](https://github.com/jaredmichaelsmith/awesome-vehicle-security/blob/master/contributing.md)

Check out my [blog](https://jaredmichaelsmith.com/blog) or follow me on [Twitter](https://twitter.com/jaredthecoder).

---

**Legend**:
- 🌟: MOST AWESOME.
- 💰: Costs money. 😞

---

# Contents

- [Learn](#learn)
    - [Articles](#articles)
    - [Presentations](#presentations)
    - [Books](#books)
    - [Blogs](#blogs)
    - [Websites](#websites)
    - [Newsletters](#newsletters)
    - [Who to Follow](#who-to-follow)
    - [Podcasts and Episodes](#podcasts-and-episodes)
        - [Podcasts](#podcasts)
        - [Episodes](#episodes)
- [Hardware](#hardware)
- [Software](#software)
  - [Applications](#applications)
  - [Libraries and Tools](#libraries-and-tools)
    - [C](#c)
    - [Python](#python)
    - [Go](#go)
    - [JavaScript](#javascript)
- [Companies and Jobs](#companies-and-jobs)
- [Other Awesome Lists](#other-awesome-lists)
- [Contributing](#contributing)

# Learn

## Articles

- 🌟 [Stopping a Jeep Cherokee on the Highway Remotely](https://www.wired.com/2015/07/hackers-remotely-kill-jeep-highway/) - Chris Valasek's and Charlie Miller's pivotal research on hacking into Jeep's presented at DEFCON in 2015.
- [Troy Hunt on Controlling Nissans](https://www.troyhunt.com/controlling-vehicle-features-of-nissan/) - Troy Hunt goes into controlling Nissan vehicles.
- [Tesla hackers explain how they did it at Defcon](http://www.cnet.com/roadshow/news/tesla-hackers-explain-how-they-did-it-at-def-con-23/) - Overview of DEFCON 23 presentation on hacking into Tesla cars.
- [Anatomy of the Rolljam Wireless Car Hack](http://makezine.com/2015/08/11/anatomy-of-the-rolljam-wireless-car-hack/) - Overview of the RollJam rolling code exploitation device.
- [IOActive's Tools and Data](http://blog.ioactive.com/2013/08/car-hacking-content.html) - Chris Valasek and Charlie Miller release some of their tools and data for hacking into vehicles in an effort to get more people into vehicle security research.

## Presentations

- ["Hopping on the CAN Bus" from BlackHat Asia 2015](https://www.blackhat.com/asia-15/briefings.html#hopping-on-the-can-bus) - A talk from BlackHat Asia 2015 that by the end the audience should "gain an understanding of automotive systems, but will also have the tools to attack them".
- ["Drive It Like You Hacked It" from DEFCON 23](https://samy.pl/defcon2015/) - A talk and slides from Samy Kamkar's DEFCON 23/2015 talk that includes hacking garages, exploiting automotive mobile apps, and breaking rolling codes to unlock any vehicle with low cost tools.
- [Samy Kamkar on Hacking Vehicles with OnStar](https://www.youtube.com/watch?v=3olXUbS-prU&feature=youtu.be) - Samy Kamkar, the prolific hacker behind the Samy worm on MySpace, explores hacking into vehicles with OnStar systems.
- [Remote Exploitation of an Unaltered Passenger Vehicle](https://www.youtube.com/watch?v=OobLb1McxnI) - DEFCON 23 talk by Chris Valasek and Charlie Miller give their now famous talk on hacking into a Jeep remotely and stopping it dead in its tracks.
- [Adventures in Automotive Networks and Control Units](https://www.youtube.com/watch?v=n70hIu9lcYo) - DEFCON 21 talk by Chris Valasek and Charlie Miller on automotive networks.

## Books

- 🌟 [2014 Car Hacker's Handbook](http://opengarages.org/handbook/) - Free guide to hacking vehicles from 2014. You can also buy the book on Amazon [here](https://www.amazon.com/Car-Hackers-Manual-Craig-Smith/dp/0990490106?ie=UTF8&keywords=2014%20car%20hacker%27s%20manual&qid=1405445024&ref_=sr_1_1&sr=8-1).
- 🌟💰 [2016 Car Hacker's Handbook](https://www.amazon.com/Car-Hackers-Handbook-Penetration-Tester/dp/1593277032) - Latest version of the Car Hacker's handbook with updated information to hack your own vehicle and learning vehicle security.
- 💰 [A Comprehensible Guide to Controller Area Network](https://www.amazon.com/Comprehensible-Guide-Controller-Area-Network/dp/0976511606/ref=pd_sim_14_1?ie=UTF8&dpID=41-D9UhlE9L&dpSrc=sims&preST=_AC_UL160_SR124%2C160_&psc=1&refRID=3FH8N10610H0RX8SMB6K) - An older book from 2005, but still a comprehensive guide on CAN busses and networking in vehicles.
- 💰 [Controller Area Network Prototyping with Arduino](https://www.amazon.com/Controller-Area-Network-Prototyping-Arduino/dp/1938581164/ref=pd_sim_14_2?ie=UTF8&dpID=51J27ZEcl9L&dpSrc=sims&preST=_AC_UL160_SR123%2C160_&psc=1&refRID=V42FKNW09QGVGHW7ZFRR) - This book guides you through prototyping CAN applications on Arduinos, which can help when working with CAN on your own car.
- 💰 [Embedded Networking with CAN and CANopen](https://www.amazon.com/Embedded-Networking-CANopen-Olaf-Pfeiffer/dp/0929392787/ref=pd_sim_14_37?ie=UTF8&dpID=41UnLKYFpmL&dpSrc=sims&preST=_AC_UL160_SR122%2C160_&psc=1&refRID=V42FKNW09QGVGHW7ZFRR) - From 2003, this book fills in gaps in CAN literature and will educate you further on CAN networks and working with embedded systems.


## Blogs

[Welcoming contributions](https://github.com/jaredmichaelsmith/awesome-vehicle-security/blob/master/contributing.md)!


## Websites

- 🌟 [OpenGarages](http://opengarages.org/index.php/Main_Page) - Provides public access, documentation and tools necessary to understand today's modern vehicle systems.
- [DEFCON Car Hacking Village](http://www.carhackingvillage.com/) - Car Hacking exercises from DEFCON 24.
- [canbushack: Hack Your Car](http://www.canbushack.com/blog/index.php) - Course on Vehicle Hacking.
- [OWASP Internet of Things Project](https://www.owasp.org/index.php/OWASP_Internet_of_Things_Project#tab=Community) - OWASP's project to secure IoT, from cars to medical devices and beyond.
- [IAmTheCalvary](https://www.iamthecavalry.org/) - Global organization backed by major internet companies pushing standards to secure IoT devices.


## Newsletters

[Welcoming contributions](https://github.com/jaredmichaelsmith/awesome-vehicle-security/blob/master/contributing.md)!


## Who to Follow

- 🌟 Chris Valasek: Security Lead at UberATC.
    - [Twitter](https://twitter.com/nudehaberdasher)
    - [Website](http://chris.illmatics.com/about.html)
- 🌟 Charlie Miller: Hacked the first Apple iPhone, now does car security.
    - [Twitter](https://twitter.com/0xcharlie)
- 🌟 Samy Kamkar: Created MySpace Worm, RollJam, OwnStar.
    - [Twitter](https://twitter.com/samykamkar)
- 🌟 Justin Seitz: Author of Black Hat Python.
    - [Twitter](https://twitter.com/jms_dot_py)
- 🌟 Troy Hunt: Pluralsight author. Microsoft Regional Director and MVP for Developer Security. Creator of [haveibeenpwned](https://haveibeenpwned.com/).
    - [Twitter](https://twitter.com/troyhunt)
    - [Website](https://www.troyhunt.com/)
- OpenGarages: Initiative to created Vehicle Research Labs around the world.
    - [Twitter](https://twitter.com/opengarages)
    - [Website](http://opengarages.org/index.php/Main_Page)
- Hackaday: Collaborative project hosting for hackers - there are frequently car projects on here.
    - [Twitter](https://twitter.com/hackaday)

## Podcasts and Episodes

Podcasts and podcast episodes that either directly focus on vehicle security or have some episodes on it.

### Podcasts
- 🌟 [Security Weekly](http://securityweekly.com/) - Excellent podcast covering all ranges of security, with some episodes focusing portions on vehicle security from cars to drones.
- [TrustedSec Podcast](https://www.trustedsec.com/podcast/) - From the people at TrustedSec, leaders in Social Engineering, their episodes often go into recent vehicle vulnerabilities and exploits.
- [SANS Internet Storm Center](https://isc.sans.edu/) - A regular podcast going into the latest vulnerabilities and security news.
- [Security Ledger](https://soundcloud.com/securityledger) - A podcast focusing on interviewing security experts about topics related to security.

### Episodes
- 🌟 [Car Hacking with Craig Smith](http://softwareengineeringdaily.com/2015/09/02/car-hacking-with-craig-smith/) - Software Engineering Daily did an amazing episode with Craig Smith, author of the Car Hacking Handbook (above), on hacking into vehicles.
- [Big Bugs Podcast Episode 1: Auto Bugs - Critical Vulns found in Cars with Jason Haddix](https://blog.bugcrowd.com/big-bugs-podcast-episode-1) - Jason Haddix explores major vulnerabilities found in cars.
- [Hacking Under the Hood and Into Your Car](http://www.npr.org/2013/08/02/208270026/hacking-under-the-hood-and-into-your-car) - Chris Valasek and Charlie Miller discuss with NPR how they were able to hack into vehicles.
- [Hacking Connected Vehicles with Chris Valasek of IOActive](https://soundcloud.com/securityledger/chris-valasek-of-ioactive) - Chris Valasek talks about hacking into connected vehicles.

# Hardware 💰

Overview of hardware, both open source and proprietary, that you can use when conducting vehicle security research. [This article](http://makezine.com/2016/04/08/car-hacking-tools-trade/) goes through many of the options below.

- 🌟 [Arduino](https://www.arduino.cc/) - Arduino's have a number of shields you can attach to connect to CAN-enabled devices.
    - [CANdiy-Shield](https://github.com/watterott/CANdiy-Shield)
    - [ChuangZhou CAN-Bus Shield](http://www.seeedstudio.com/wiki/CAN-BUS_Shield)
    - [DFRobot CAN-BUS Shield For Arduino](http://www.dfrobot.com/index.php?route=product/product&product_id=1444)
    - [SparkFun CAN-BUS Shield](https://www.sparkfun.com/products/13262)
- [CANtact](http://linklayer.github.io/cantact/) - "The Open Source Car Tool" designed to help you hack your car. You can buy one or make your own following the guide here.
- [Freematics OBD-II Telematics Kit](http://freematics.com/pages/products/arduino-telematics-kit-3/) - Arduino-based OBD-II Bluetooth adapter kit has both an OBD-II device and a data logger, and it comes with GPS, an accelerometer and gyro, and temperature sensors.
- 🌟 [ELM327](https://www.elmelectronics.com/obdic.html) - The de facto chipset that's very cheap and can be used to connect to CAN devices.
- [GoodThopter12](http://goodfet.sourceforge.net/hardware/goodthopter12/) - Crafted by a well-known hardware hacker, this board is a general board that can be used for exploration of automotive networks.
- [USB2CAN](http://www.8devices.com/products/usb2can/) - Cheap USB to CAN connector that will register a device on linux that you can use to get data from a CAN network.
- [Intrepid Tools](http://store.intrepidcs.com/) - Expensive, but extremely versatile tools specifically designed for reversing CAN and other vehicle communication protocols.
- [Red Pitaya](http://redpitaya.com/) - Replaces expensive measurement tools such as oscilloscopes, signal generators, and spectrum analyzers. Red Pitaya has LabView and Matlab interfaces, and you can write your own tools and applications for it. It even supports extensions for things like Arduino shields.
- [ChipWhisperer](http://newae.com/tools/chipwhisperer/) - A system for side-channel attacks, such as power analysis and clock glitching.
- [HackerSDR](https://greatscottgadgets.com/hackrf/) - A Software Defined Radio peripheral capable of transmission or reception of radio signals from 1 MHz to 6 GHz. Designed to enable test and development of modern and next generation radio technologies.


# Software

Overview of software, both open source and proprietary, as well as libraries from various programming languages. [This article](http://makezine.com/2016/04/08/car-hacking-tools-trade/) goes through many of the options below.

## Applications

Software applications that will help you hack your car, investigate it's signals, and general tinkering with it.

- 🌟 [WireShark](https://www.wireshark.org/) - WireShark can be used for reversing CAN communications.
- [Kayak](http://kayak.2codeornot2code.org/) - Java application for CAN bus diagnosis and monitoring.
- [UDSim](https://github.com/zombieCraig/UDSim/) - GUI tool that can monitor a CAN bus and automatically learn the devices attached to it by watching communications.
- [RomRaider](http://www.romraider.com/) - An open source tuning suite for the Subaru engine control unit that lets you view and log data and tune the ECU.
- 💰 [Intrepid Tools](http://store.intrepidcs.com/) - Expensive, but extremely versatile tools specifically designed for reversing CAN and other vehicle communication protocols.
- [O2OO](https://www.vanheusden.com/O2OO/) - Works with the ELM327 to record data to a SQLite database for graphing purposes. It also supports reading GPS data. You can connect this to your car and have it map out using Google Maps KML data where you drive.

## Libraries and Tools

Libraries and tools that don't fall under the larger class of applications above.

### C

- [SocketCAN Utils](https://github.com/linux-can/can-utils) - Userspace utilites for SocketCAN on Linux.

### Python

- 🌟 [CANard](https://github.com/ericevenchick/canard) - A Python framework for Controller Area Network applications.
- [Caring Caribou](https://github.com/CaringCaribou/caringcaribou/) - Intended to be the *nmap of vehicle security*.
- [c0f](https://github.com/zombieCraig/c0f/) - A fingerprinting tool for CAN communications that can be used to find a specific signal on a CAN network when testing interactions with a vehicle.
- [Python-CAN](http://python-can.readthedocs.io/en/latest/index.html) - Python interface to various CAN implementations, including SocketCAN. Allows you to use Python 2.7.x or 3.3.x+ to communicate over CAN networks.

### Go

- [CANNiBUS](https://github.com/Hive13/CANiBUS/) - A Go server that allows a room full of researchers to simultaneously work on the same vehicle, whether for instructional purposes or team reversing sessions.

### JavaScript

- [NodeJS extension to SocketCAN](https://github.com/sebi2k1/node-can) - Allows you to communicate over CAN networks with simple JavaScript functions.

# Companies and Jobs

Companies and jobs working in vehicle security.

- [UberATC](https://www.uberatc.com/) - Uber Advanced Technologies Center - <info@uberatc.com>.
- [Tesla](https://www.tesla.com/careers/search#/filter/?keyword=security&department=1) - Tesla hires security professionals for a variety of roles, particularly securing their vehicles.
- [Intrepid Control Systems](https://www.intrepidcs.com/jobs/) - Embedded security company building tools for reversing vehicles.
- [Rapid7](https://www.rapid7.com/company/careers.jsp) - Rapid7 does work in information, computer, and embedded security.
- [IOActive](http://www.ioactive.com/) - Security consulting firm that does work on pentesting hardware and embedded systems.

# Other Awesome Lists

List of lists.

- Security
  - 🌟 [Application Security](https://github.com/paragonie/awesome-appsec)
  - [Security](https://github.com/sbilly/awesome-security)
  - [Capture the Flag](https://github.com/apsdehal/awesome-ctf)
  - [Malware Analysis](https://github.com/rshipp/awesome-malware-analysis)
  - [Android Security](https://github.com/ashishb/android-security-awesome)
  - [Hacking](https://github.com/carpedm20/awesome-hacking)
  - [Honeypots](https://github.com/paralax/awesome-honeypots)
  - [Incident Response](https://github.com/meirwah/awesome-incident-response)
- Meta
  - 🌟 [awesome](https://github.com/sindresorhus/awesome)
  - [lists](https://github.com/jnv/lists)

# Contributing

Your contributions are always welcome! Please take a look at the [contribution guidelines](https://github.com/jaredmichaelsmith/awesome-vehicle-security/blob/master/contributing.md) first.
