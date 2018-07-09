Creating a SOC with OSS
This Repo is a collection of scripts to install some of the most critical OSS available for Security Operation Centers. I have found through my experience that one of the largest barriers to the implementation of some of these fantastic tools is the challenges that are presented when attempting to install them.

If you think about your SOC ecosystem you need a number of tools to assist with your operations.  

Knowledge Management:
- <a href="https://github.com/MISP/MISP">MISP</a>

Detecting Threats:
- Network Packet Based
  - <a href="https://www.stamus-networks.com/open-source/">SELKS</a>
  - <a href="https://securityonion.net/">Security Onion</a>

- Network Session Based
  - Xplico

- Host Applications
  - <a href="https://www.clamav.net/">ClamAV</a>
  - Syslog (Linux / Mac)
  - <a href="https://nxlog.co/">NXLog (Windows)</a>
  - <a href="https://www.elastic.co/downloads/beats/winlogbeat">WinLogBeat (Windows)</a>

Centralized Alert Storage:
- ELK or SELKS
- <a href="https://www.alienvault.com/products/ossim">OSSIM</a>

Intelligence Report Acquisition:
- <a href="http://www.misp-project.org/">MISP</a> - has a built in TAXII Server 

IOC Enrichment:
- <A href="https://www.paterva.com/web7/">Maltego</a> - I know it's not free; but it's super cheap

Forensics:
- <a href="https://github.com/google/grr">GRR</a> - Allows the ability to acquire live images from remote hosts
- <a href="https://digital-forensics.sans.org/community/downloads">SANS SIFT</a> - Live forensic CD for image acquisition an analysis
  - dd - Forensic image acquisition (linux only and included in SIFT)
- Sleuthkit - Lots of great tools although I use most for timeline analysis
- <a href="https://www.fireeye.com/services/freeware/redline.html">Redline</a> - Analyzing Forensic images. Simple interface; easy for junior members to use
- Volatility - Awesome for analyzing memory

Malware Analysis:
- <a href="https://remnux.org/">REMNux</a>

Malware Repository:
- <a href="https://crits.github.io/">CRITs</a>

Vulnerability Management:
- OpenVAS

Please email me with recommendations on free OSS that I've missed that you feel should be on the list. securesynapse@gmail.com
