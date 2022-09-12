---
layout: page
title: SagaLabs
permalink: /SagaLabs
comments: false
---

![SagaLabs](/assets/images/sagalabs.png "SagaLabs")

SagaLabs er en cloud platform, specelt designet til purple teaming øvelser.

Platformen er bygget i [Terrafrom](https://www.terraform.io/), hvilket gør den ideel til at konfigurere efter behov og samtidig nem at deploye.
Derudover muliggør Terrafrom at der bygges flere platforme paralelt, hviket medfører at vi kan have flere hold der arbejder på samme opgave, uden at sidde i samme lab og dermed kan arbejde på forskellige hold.

Baselabbet består af 2 klienter, en DC, [TheHive](https://github.com/TheHive-Project/TheHive), [Velociraptor](https://github.com/Velocidex/velociraptor), en VPN server, samt en firewall (inkl. DNS) mellem de forskellige subnets.
Derudover er der installeret Elasic på alle endpoints.

Vi har tidligere erfaring i foreningen med at afholde purple teaming events, baseret på "adversary emulation" af blandt andet [Wizard Spider](https://attack.mitre.org/groups/G0102/).


![SagaLabs](/assets/images/sagalabs1.png "SagaLabs")
