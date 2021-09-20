# Tooling 

## add kali repositories

```
sudo sh -c "echo 'deb https://http.kali.org/kali kali-rolling main non-free contrib' > /etc/apt/sources.list.d/kali.list"
```

```
wget 'https://archive.kali.org/archive-key.asc'
sudo apt-key add archive-key.asc
```

```
touch /etc/apt/preferences.d/kali.pref 


add this to the file:

Package: *
Pin: release a=kali-rolling
Pin-Priority: 50
```

```
sudo apt update
```

## Tools

from apt:

```
git
vim
tmux
curl
```

pentest:

```
gobuster
exploitdb
sqlmap
dnsenum
dnsrecon
dnsmap
enum4linux
nikto
nmap
smbmap
smtp-user-enum
wireshark
httptunnel
nishang
powersploit
cewl
crowbar
hash-identifier
hashcat
hydra
john
rainbowcrack
seclists
wordlists
cherrytree
responder
apache-users
davtest
dirb
dirbuster
recon-ng
websploit
wfuzz
binwalk
strings
steghide
windows-binaries


sudo apt-get install gobuster exploitdb sqlmap dnsenum dnsrecon dnsmap enum4linux nikto nmap smbmap smtp-user-enum wireshark httptunnel nishang powersploit cewl crowbar hash-identifier hashcat hydra john rainbowcrack seclists wordlists cherrytree responder apache-users davtest dirb dirbuster recon-ng websploit wfuzz binwalk steghide windows-binaries
```

not from apt:

```
sublime text - webpage
crackmapexec - github
volatility - github
zapproxy - webpage
zsteg - github
burpsuite - website - add certificate
```

weird dependencies (resolve later):

the harvester
wpscan
winexe

metasploit - some wierd shit with ruby