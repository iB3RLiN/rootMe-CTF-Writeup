# rootMe-CTF-Writeup
root me CTF  Writeup



Task2 - Reconnaissance
       Q1 Scan the machine, how many ports are open?,
       Q2 What version of Apache is running?
       Q3 What service is running on port 22?
just use nmap 😉

![nmap](https://user-images.githubusercontent.com/73380139/181879063-cafeeff5-de6e-42d1-ae8f-0763d408b8b6.png)

       Q5 What is the hidden directory?
       
![dirb](https://user-images.githubusercontent.com/73380139/181879168-eed8f65c-629c-4d27-a9c3-df847bcc48ee.png)

Task3 - Getting a shell
      Q1 Find a form to upload and get a reverse shell, and find the flag.
          go to hiden dir,
          we can uplode file!
    
![panel](https://user-images.githubusercontent.com/73380139/181879345-5a3da54c-ce70-48c6-8fdb-b083cb274c22.png)

now go to google.com and serch about reverse shell

![searchShellPhp](https://user-images.githubusercontent.com/73380139/181879458-7981affa-e64a-4c98-a884-57d6cfaab423.png)

uplode our shell after replecmnt defult shell data with your IP, port and target IP

![runShell](https://user-images.githubusercontent.com/73380139/181880381-ff44f826-7132-4ccc-af42-87a88c5483dc.png)

use net cat and run php shell

![runShell](https://user-images.githubusercontent.com/73380139/181880423-9fb49225-55bd-4b88-a4c8-f0ef22abf747.png)

![netCat](https://user-images.githubusercontent.com/73380139/181880432-c1e2df93-1299-4305-96db-953620f8bf97.png)

search user.txt flag by command 

![findUserText](https://user-images.githubusercontent.com/73380139/181880495-17a776bc-da1c-4113-ab60-11efbae35f75.png)

now we got user flag

![catUser](https://user-images.githubusercontent.com/73380139/181880510-4bddb337-a7a0-4e62-924b-069bc31da406.png)

Task4 - Privilege escalation
        Q1 Search for files with SUID permission, which file is weird?
        
        ![PrevPy](https://user-images.githubusercontent.com/73380139/181881517-298d51d6-a3eb-4ca9-a8d3-837a6948d3cc.png)
        
        Q3 root.txt
        
        ![rootFlag](https://user-images.githubusercontent.com/73380139/181881998-a035a505-059f-4092-9424-e435523f7bdd.png)








