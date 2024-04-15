<p align="center">
  <img src="https://i.imgur.com/YKJcysc.jpeg" alt="MeduzaResearch Logo" width="300">
</p>

# Meduza Research

[![License](https://img.shields.io/badge/License-GPL%203.0%20with%20AGPL%203.0-blue.svg)](LICENSE)
[![GitHub Stars](https://img.shields.io/github/stars/Th3Tr1ckst3r/MeduzaResearch)](https://github.com/Th3Tr1ckst3r/MeduzaResearch/stargazers)
[![GitHub Forks](https://img.shields.io/github/forks/Th3Tr1ckst3r/MeduzaResearch)](https://github.com/Th3Tr1ckst3r/MeduzaResearch/network/members)
[![GitHub Issues](https://img.shields.io/github/issues/Th3Tr1ckst3r/MeduzaResearch)](https://github.com/Th3Tr1ckst3r/MeduzaResearch/issues)

This repository is dedicated to the threat intelligence research around the nefarious "Meduza Stealer", &amp; surrounding malware families being actively used, &amp; deployed in the wild.

# Introduction
If you have been monitoring the open source threat intelligence communities the past year, you might have heard of this malware already, & probably need no introduction.

However, its just as important for those that are not familiar, to be aware of this emerging threat that has been resurfacing mostly from the Russian Federation, & China.

Recent research has came to light, that this malware has been around much longer than other researchers have anticipated. More importantly, that the Meduza malware shows
strong indicators of being a reiteration of the "Aurora Stealer". A separate, but slightly older malware family. If you would like to read further into this new research,
you may find that information [here](https://russianpanda.com/2023/06/28/Meduza-Stealer-or-The-Return-of-The-Infamous-Aurora-Stealer/).

That being said, the threat intelligence open-source communities have been very proactive as to identify, classify, & share their information with others to help defend
against this malware strain. You would think that would be the end of it, but no. Other recent cyber attacks on a slightly larger scale have occured, that gives us new insights
into this very unique malware strain being shared on the dark web as a service. A great example of this can be found [here](https://otx.alienvault.com/pulse/65f12070a078f83266ee3fd4).

Where Pikabot, a different, but popular malware strain that may need no introduction was used to infect the target with the "Meduza Stealer". This technique was very uncommon,
which definitely raised some eyebrows, but I digress.

# Solutions

Many of us researchers have our own solutions, but for those that don't I have provided some blocklists in this repository. I've used the standard plaintext format
for the first set of blocklists, & for the second set of blocklists I used an organized JSON format so that its easier to read, & work with. I've also provided in the same
formats a list of various hashes to look for when it comes to these strains of malware.

# Conclusion

Recently, as many as(75+ servers), were taken offline which were either being used to distribute the "Meduza Stealer", or being used as command, & control(C2) servers. 
Further research suggests that the threat actors are still trying to maintain a certain level of persistence with other servers, & clients by leaving a select few C2's online, & operational. 

I was able to verify this first hand, & have provided in this repository a significant amount of IoC's, along with some screenshots, & other threat intelligence that may be of some use.

# Resourceful Links

https://otx.alienvault.com/pulse/65a788556fef4497cb69ff1c

https://otx.alienvault.com/pulse/65f12070a078f83266ee3fd4

https://otx.alienvault.com/pulse/6598f38a2951caa01b450571

https://otx.alienvault.com/pulse/659ed8289f0b1a1f89b3effc

https://otx.alienvault.com/pulse/657305ad0314d85c5150b8ce

https://otx.alienvault.com/pulse/65940ee7962bfb1bbf9f386b

https://russianpanda.com/2023/06/28/Meduza-Stealer-or-The-Return-of-The-Infamous-Aurora-Stealer/

https://gbhackers.com/new-medusa-stealer/

https://www.resecurity.com/blog/article/new-version-of-medusa-stealer-released-in-dark-web

https://research.nccgroup.com/2023/11/13/dont-throw-a-hissy-fit-defend-against-medusa/

