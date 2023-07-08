# Fullstack for Frontend Engineers notes
https://frontendmasters.com/courses/fullstack-v3/

## Vim
Vim has 3 modes: insert (i), normal mode (ESC) and command mode (:).

## connect to server via ssh
ssh -i ~/.ssh/<fsfe || ssh private key name> root@<server IP>

## DNS Records
A record: maps name to IP address
CNAME: maps name to name. boogle.com <=> google.com for example.

## Network commands
`nslookup <url>`
`dig <url>`
`ping <url>`


## Test ssh connection
```bash
  ssh -Tv <remote url>
```

## Read the auth log
```bash
sudo cat /var/log/auth.log
```

## Chmod permissions cheatsheet
https://quickref.me/chmod

## Check open ports
```bash
 sudo apt install nmap
 nmap <ip address>
```


## Cron job creation tool
https://crontab.guru

## Find vs grep
find is where, grep is looking inside

## Free https certificate
https://certbot.eff.org/