# honeypotreport

* Which Honeypot(s) you deployed
    I deployed these 4 honeypots:
      1. mhn-honeypot-1-dionaea : Ubuntu - Dionaea with HTTP
      2. mhn-honeypot-2-elastichoney : Ubuntu - ElasticHoney
      3. mhn-honeypot-3-wordpot : Ubuntu - Wordpot
      4. mhn-honeypot-4-dionaea : Ubuntu 14.04/Centos 7 - Dionaea
* Any issues you encountered
      1. I had trouble opening the MHN admin portal because tcp:80 was not added to firewall rule in GCP when following the instruction.
* A summary of the data collected: number of attacks, number of malware samples, etc.
    * Number of attacks from 15 NOV to 02 DEC : 17 days  
      1. mhn-honeypot-1-dionaea : Ubuntu - Dionaea with HTTP : 105,968
      2. mhn-honeypot-2-elastichoney : Ubuntu - ElasticHoney : 34
      3. mhn-honeypot-3-wordpot : Ubuntu - Wordpot : 0
      4. mhn-honeypot-4-dionaea : Ubuntu 14.04/Centos 7 - Dionaea : 103,876
    * For past 24 hrs: 
        * Attacks in the last 24 hours: 12,427:
        * TOP 5 Attacked ports:
            1. 5060 (3,073 times)
            2. 8088 (2,449 times)
            3. 5061 (1,607 times)
            4. 23 (587 times)
            5. 445 (313 times)
        * TOP 5 Honey Pots:
            1. dionaea (12,424 attacks)
            2. elastichoney (3 attacks)
                
* Any unresolved questions raised by the data collected
    1. which countries sent out the most attacks
    2. which countries are getting most of the attacks
    
