# CTF-Week-9-Assignment

hours spent: 

- Which Honeypot(s) you deployed
dionaea honeypot using the MHN application

- Any issues you encountered
The link to the repo in milestone 2 is incorrect, as a result the installation was unsuccesful until I changed the link in the install_hpfeeds.sh file from:
pip install -e git+https://github.com/HurricaneLabs/pyev.git#egg=pyev
to 
pip install -e git+https://github.com/couozu/pyev.git#egg=pyev

- A summary of the data collected: number of attacks, number of malware samples, etc.
It is interesting because in the span of 24 hours there was 6,195 attacks
Top 5 Attacker Ips:

1. united states (2,902 attacks)
2. china (333 attacks)
3. china (251 attacks)
4. Italy (178 attacks)
5. Italy (112 attacks)

- Any unresolved questions raised by the data collected
I guess I never thought I would get attacks from Italy. 
