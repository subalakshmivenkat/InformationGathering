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
![image](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/53ef2271-ad92-4b0d-8d17-b9e6639866ba)

## FINDING THE IP ADDRESS:
ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
![265585635-68d7d69e-41bc-43f0-8bd0-1a3a10fa94d5](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/9a57fb48-e16f-4343-801c-b172205b480a)


ping saveetha.ac.inFINDING THE IP ADDRESS:![265585931-1e2d2720-cb2d-40dd-b033-be5424e75c0f](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/d52a4133-7d7d-4db8-b232-ea0d118db76b)

ping command is available on Windows as well as on Linux OS. Following is the example to find out the IP address of saveetha.ac.in.
## FINDING THE HOSTING COMPANY :

https://www.ip2location.com/demo/13.33.146.98
![265585931-1e2d2720-cb2d-40dd-b033-be5424e75c0f](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/80f2c9c2-c431-43b0-aea1-1026b3d5ffe5)

## WEB ARCHIVE (HISTORY OF THE WEBSITE) :

https://web.archive.org/details/freshworks.com
![265586189-cae7ad50-0db0-4ff6-a4e9-d876a16f3310](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/38b59584-a52d-4b6b-ad3e-e22836dda527)

## NMAP :

nmap -p 21 -sV --script=banner 13.33.146.98
![265586381-47765673-7930-46f7-9933-dbfd6ae94c33](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/ac8d551d-370a-4787-a2ba-da1fc332df62)

## WHATWEB :

whatweb freshworks.com
![265586635-1ff75b90-6bf3-40cf-902d-f7527d2ae275](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/a9fa9e35-8965-410e-83ea-100b8a5134e5)

whatweb -v freshworks.com
![265586770-97ed7f82-705d-4ab7-85e9-44eafc697a29](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/1385f1b4-1bd3-4ab8-a4d9-ee8682450420)

## HTTPRINT :

httprint -h 13.33.146.98 -s /usr/share/httprint/signatures.txt -P0 |more
![265587106-a0999212-12b5-4eac-9ed0-fa454a4465fd](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/cc9a7202-4118-45e0-9d35-9e1b626e9905)

## TRACEOUT :
## TCP TRACEOUT :

 sudo traceroute -T www.freshworks.com
 ![265587370-da148908-aac3-44fa-9180-e4545e7e63c6](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/ae77c954-bcb1-4763-a65b-eb53d1a1a5a4)

 ## UDP TRACEOUT :

 sudo traceroute -U www.freshworks.com
![265587532-f0c8d421-8cac-45ff-9ec3-a2a23465b88d](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/162ec958-6d7b-43f4-9b9c-a4c030e0059c)

## ICMP TRACEOUT :

 sudo traceroute  www.freshworks.com
 ![265587791-28665b8c-4679-497a-9a55-3167c3fada32](https://github.com/Bakkiyalakshmi29/InformationGathering/assets/119406233/a6db44a2-ff9d-47c3-806c-ae5265085c81)















```
ping saveetha.ac.in
```
## RESULT:
The information gathering techniques tools/procedure were  identified successfully
