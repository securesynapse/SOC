Creating a SOC with OSS<br>
This Repo is a collection of scripts to install some of the most critical OSS available for Security Operation Centers. Links have also been provided to the tools. I have found through my experience that one of the largest barriers to the implementation of some of these fantastic tools is the challenges that are presented when attempting to install them.

If you think about your SOC ecosystem you need a number of tools to assist with your operations.  

Knowledge Management:
- <a href="https://github.com/MISP/MISP">MISP</a>

Detecting Threats:
- Network Packet Based
  - <a href="https://www.stamus-networks.com/open-source/">SELKS</a>
  - <a href="https://securityonion.net/">Security Onion</a>

- Network Session Based
  - <A href="https://www.xplico.org/">Xplico</a>

- Host Applications
  - <a href="https://www.clamav.net/">ClamAV</a>
  - Syslog (Linux / Mac)
  - <a href="https://nxlog.co/">NXLog (Windows)</a>
  - <a href="https://www.elastic.co/downloads/beats/winlogbeat">WinLogBeat (Windows)</a>

Centralized Alert Storage:
- <a href="https://www.elastic.co/products/kibana">Kibana</a> or <a href="https://www.stamus-networks.com/open-source/">SELKS</a>
- <a href="https://www.alienvault.com/products/ossim">OSSIM</a>

Intelligence Report Acquisition:
- <a href="http://www.misp-project.org/">MISP</a> - has a built in TAXII Server 
- <a href="https://www.anomali.com/platform/staxx">STAXX</a>

IOC Enrichment:
- <A href="https://www.paterva.com/web7/">Maltego</a> - I know it's not free; but it's super cheap

Forensics:
- <a href="https://github.com/google/grr">GRR</a> - Allows the ability to acquire live images from remote hosts
- <a href="https://digital-forensics.sans.org/community/downloads">SANS SIFT</a> - Live forensic CD for image acquisition an analysis
  - dd - Forensic image acquisition (linux only and included in SIFT)
- <a href="http://www.sleuthkit.org/">Sleuthkit</a> - Lots of great tools although I use most for timeline analysis
- <a href="https://www.fireeye.com/services/freeware/redline.html">Redline</a> - Analyzing Forensic images. Simple interface; easy for junior members to use
- <a href="https://www.volatilityfoundation.org/">Volatility</a> - Awesome for analyzing memory

Threat Hunting
- <a href="https://github.com/Cyb3rWard0g/HELK">HELK</a> - Needs a fairly beefy system for testing 

Malware Analysis:
- Static
  - <a href="https://remnux.org/">REMNux</a>
- Dynamic
  - <a href="https://cuckoosandbox.org/">Cuckoo Sandbox</a>
  
Malware Repository:
- <a href="https://crits.github.io/">CRITs</a>

Security Orchestration:
- <a href="https://github.com/nsacyber/WALKOFF">WalkOFF</a>

Vulnerability Management:
- <a href="http://www.openvas.org/">OpenVAS</a>

Rule Validation - MITRE ATT&CK Framework (Red team activities)
- <a href="https://github.com/uber-common/metta">Metta</a>
- <a href="https://github.com/redcanaryco/atomic-red-team">Atomic Red Team</a>

Software Inventory:
- <a href="https://www.ocsinventory-ng.org/">OCS Inventory-NG</a>

Interesting Projects:
- <a href="https://github.com/activecm/rita">RITA</a> - Real Intelligence Threat Analytics
Please email me with recommendations on free OSS that I've missed that you feel should be on the list. securesynapse@gmail.com
