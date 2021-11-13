# lan-scan
A script for scanning local area networks for clients and services/open ports

## Download
`curl -LO miloszkusz.pl/lan-scan` 

or just download it from here

## Usage
`chmod +x lan-scan`

```
./lan-scan [OPTIONS]

options:
 -i, --interface	Specify which network interface to use
 -s, --speed		Scan speed [0-5]
 -d, --depth		Scan depth [0-2]
			 0 host only	
			 1 xxx.xxx.xxx.*
			 2 xxx.xxx.*.*	
 -p, --ports		Specify how many ports to scan with the service scan
 -C, --clients	Perform a client scan
 -S, --services	Perform a service scan
 -h, --help		Display the help message and exit

```

## Dependencies
- nmap
- ip
- GNU coreutils (ls, awk, touch, cat, wc)
