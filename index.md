---
layout: default
---


After downloading the installer file from the Nessus website, I checked the file hashes against the hashes provided by the vendor.

![1](1.png)

![2](2.png)


I then double-clicked on the installer and followed the instructions as prompted.

![3](3.png) | ![4](4.png)

![5](5.png) | ![6](6.png)

![7](7.png) | ![9](9.png)


The installer prompted the web application where I configured & registered for Nessus Essential.

![10](10.png) | ![11](11.png)

![12](12.png) | ![13](13.png)

![14](14.png) | ![15](15.png)


Then I waited about 10 mins for the plugin to be compiled after which I manually updated the plugins.

![16](16.png)

![17](17.png)


To get started, I was prompted to launch a host discovery scan to identify my laptop.

![18](18.png)


Then I started basic network scan that I named the “Maccy Mac Scan” with the target being my laptop. Under the “Assessment” tab, I changed the Scan Type to “Scan for all web vulnerabilities (quick)” before saving and starting the vulnerability scan.

![19](19.png) | ![20](20.png)

![21](21.png) | ![22](22.png)

![23](23.png) | ![24](24.png)

![25](25.png)


The scan was ready after 16 mins.

![26](26.png)


Vulnerability Scan Result
*  Multiple vulnerabilities in the Adobe Photoshop application installed on the target
*  SSL Medium Strength Cipher Suites Supported in Nessus configuration

![27](27.png) | ![28](28.png)


Remediation 1
*  Install Adobe Photoshop patch provided by the vendor

![29](29.png) | ![30](30.png)


Remediation 2
Changed the Nessus configuration of the SSL Cipher List to only allow “NIAP Approved Ciphers”

![31](31.png) | ![32](32.png)

![33](33.png)


Then I started another basic network scan that I named the “Maccy Mac Validation Scan” with the target being my laptop. Under the “Assessment” tab, I changed the Scan Type to “Scan for all web vulnerabilities (quick)” before saving and starting the vulnerability scan.

![34](34.png) | ![35](35.png)

![36](36.png) | ![37](37.png)

![38](38.png)


The scan was ready after 7 mins and the vulnerabilities were remediated.

![39](39.png) | ![40](40.png)
