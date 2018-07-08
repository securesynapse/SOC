Creating a SOC with OSS
This Repo is a collection of scripts to install some of the most critical OSS available for Security Operation Centers. I have found through my experience that one of the largest barriers to the implementation of some of these fantastic tools is the challenges that are presented when attempting to install them.

If you think about your SOC ecosystem you need a number of tools to assist with your operations.  

Knowledge Management:
- <a href="https://github.com/MISP/MISP">MISP</a>

Detecting Threats:
- Network Packet Based
  - SELKS
  - Security Onion

- Network Session Based
  - Xplico

- Host Applications
  - ClamAV
  - Syslog (Linux / Mac)
  - NXLog (Windows)
  - WinLogBeat (Windows)

Centralized Alert Storage:
- ELK or SELKS
- OSSIM

Intelligence Report Acquisition:
- MISP - has a built in TAXII Server 

IOC Enrichment:
- Maltego - I know it's not free; but it's super cheap

Forensics:
- GRR - Allows the ability to acquire live images from remote hosts
- SANS SIFT - Live forensic CD for image acquisition an analysis
  - dd - Forensic image acquisition (linux only and included in SIFT)
- Sleuthkit - Lots of great tools although I use most for timeline analysis
- Redline - Analyzing Forensic images. Simple interface; easy for junior members to use
- Volatility - Awesome for analyzing memory

Malware Analysis:
- REMNux

Malware Repository:
- CRITs

Vulnerability Management:
- OpenVAS

Please email me with recommendations on free OSS that I've missed that you feel should be on the list. securesynapse@gmail.com
