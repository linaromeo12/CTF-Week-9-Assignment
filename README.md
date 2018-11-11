# CTF-Week-9-Assignment

- Which Honeypot(s) you deployed

dionaea honeypot using the MHN application

- Any issues you encountered

The link to the repo in milestone 2 is incorrect, as a result the installation was unsuccesful until I changed the link in the install_hpfeeds.sh file from:
pip install -e git+https://github.com/HurricaneLabs/pyev.git#egg=pyev
to 
pip install -e git+https://github.com/couozu/pyev.git#egg=pyev

All the other instructions were straighforward and easy to follow. 

- A summary of the data collected: number of attacks, number of malware samples, etc.

It is interesting because in the span of 24 hours there was 6,195 attacks

TOP 5 Attacker IPs:
  199.111.226.189 (2,902 attacks)
  61.176.223.98 (333 attacks)
  61.176.222.170 (251 attacks)
  80.211.113.76 (178 attacks)
  80.211.25.178 (112 attacks)

TOP 5 Attacked ports:
  8088 (1,488 times)
  8080 (621 times)
  23 (180 times)
  5060 (146 times)
  3306 (86 times)

- Any unresolved questions raised by the data collected

I found the data quite interesting because I didn't think I would get that many attacks in just 24 hours. 
