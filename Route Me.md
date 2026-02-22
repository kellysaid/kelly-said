This is a Privilege Escalation challenge

Go to R2
Access the CLI interface
Enter supplied USERNAME/PASSWORD: Smith/DawaYk
This USERNAME/PASSWORD grants us access to Privileged Exec mode, but we want Global Configuration mode. 
Let's see what R2's configuration settings are.
Type show-running-config to find the HOSTNAME/PASSWORD: Router/7 080A4D42003B041B1B
The password is a Type 7, which is insecure, meaning we can decrypt by going online to Cisco Password Decoder Tool
Enter the 080A4D42003B041B1B password online to see the decrypted password, which is: KaliBali
In R2's CLI interface, type enable to access Global Configuration mode
Enter the decoded password: KaliBali
Now we can configure the interface by entering: interface gigabitEthernet 0/1
Activate the network interface by entering: no shutdown
Now, go to the Web Browser in tabdb-backup and enter the URL for websrv-internal 192.168.1.5 to Capture the Flag
See Route Me.pdf for details with screenshots

