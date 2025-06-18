# Task 1 

Objective- Perform a network scan to identify open ports and services using nmap. 



                     
Port     Protocol      State       Service          Significance

53        TCP/UDP      open        domain           Domain name resolution. if misconfigured, may be   
                                                     Used for DNS amplification attacks.  

80         TCP         open         HTTP            Hosts a web server. May expose vulnerabilities if 
                                                    Software is outdated or misconfigured.

443        TCP         open         HTTPS           Secure web communication. Ensure TLS is configured
                                                    Correctly to prevent MITM Attacks.          
