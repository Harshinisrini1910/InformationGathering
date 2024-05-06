# InformationGathering
Information Gathering Techiques

# To perform information gathering techniques

# AIM:

To perform information gathering techniques using kali linux 

## STEPS:

### Step 1:

Install kali linux either in partition or virtual box or in live mode

### Step 2:

Investigate on the various categories of tools as follows:

### Step 3:
Open terminal/browser and try execute necessary commands/use url to perform information gathering


## OUTPUT:

![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/4d07c2db-4e81-400d-9d02-6b556d9f2cae)
## finding ip address
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
```
ping saveetha.ac.in
```
## output
![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/24aa6989-1df6-4d28-9ed8-4cd36d5f358d)

## finding hosting company
get further detail by using ip2location.com website.
## output
![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/c13e4225-da47-485b-8942-5ffa4a8cda4f)

## History of the website:
## output
![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/fb7fe667-df0c-4030-bd28-1d61d294b44a)

## netcat
```
nc 172.17.52.118 80
```
## output
![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/98da49bd-3910-428c-bc48-f537f7051ba9)
## Nmap:
```
nmap -p 21 -sV --script=banner ftp.vim.org
```
## output
![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/644c5089-dca4-4d2f-8d4f-52dbb6e298a6)

## whatweb
```
whatweb infosys.com
```
```
whatweb zoho.com
```
```
whatweb -v -a 3 172.17.52.201
````
## output
![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/3d88348b-d32f-4b9b-a540-f28397324423)


## httprint:
```
httprint -h 172.17.52.201 -s /usr/share/httprint/signatures.txt -P0 |more
```
## output
![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/a762b8fa-2fc3-4bc6-b704-0ee7d77adcbd)

## Tracing the location:
## TCP Traceroute:
```
sudo traceroute -T www.saveetha.ac.in
```
## output
![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/b793cb56-1845-4019-a166-7e43ff6fbed9)
## UDP Traceroute:
```
 sudo traceroute -U www.saveetha.ac.in
```
## output
![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/52a98324-8223-4511-841e-5ee3d3f6434b)
## ICMP Traceroute:
```
sudo traceroute  www.saveetha.ac.in
```
## output
![image](https://github.com/Harshinisrini1910/InformationGathering/assets/161415847/faa36292-2a1b-4717-b4c2-b0a17cfd96f7)


## RESULT:
The information gathering techniques tools/procedure were  identified successfully
