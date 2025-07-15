# DUCA-2025-T2-W3
Challenge repo for DUCA CTF event in Week 3 T2 2025

s we level up the scale of DUCA CTF, we need a more pipeline approach to develop challenge. I suggest developers prepare their challenge in this format and commit to a working github repo. Not every challenge has handout and source file, but all of them must have a solve.

- ***Sample challenge folder***
    
    [README template](https://www.notion.so/Challenge-README-template-2319d9519fee80aebf40e5e98e6d61cc?pvs=21) 
    
    - **publish**
        
        These are the **lightweight** resource that we upload to the CTFd instance and serve as handout files. 
        
        Example: image for geoguessing OSINT challenge, source code/binary file for RE challenge.
        
    - solve
        
        Challenge solution written in markdown format. 
        
        If the solve can be automated, put the source code here too.
        
    - src
        
        Put dockerfile, binary, web app source code, etc here.
        
        Pwn, RE, web challenges often require a running service. Put whatever we need to run it on a docker here.
