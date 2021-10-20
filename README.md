# How to make a Botnet Scan List

## Go to [Shodan](https://account.shodan.io/register) and create an account
You need an account to lookup SSH IP's, make sure to make one.
## Seach for SSH in the adress bar

![SearchSSH](/images/SearchSSH.png)
Dont search for 22 search for SSH.

## Click port 22  at the bottem left

![Click22](/images/Click22.png)

If you want to find the most accurate list search for SSH, not Telnet or anything else they are not updated as often. 
## Click an IP adress

![ClickIP](/images/ClickIP.png)
Find a unknown ISP/ASN for better lists (Bigger companies like Digital Ocean & Amazon have to much protection)

## Check for vulns (the more the better)

![CheckVulns](/images/CheckVulns.png)
The more Vulns the better, if you choose a provider with less Vunlns and scan you could get your server banned faster.

## Copy the ASN Number(s)

![ClickASN](/images/ClickASN.png)
The more ASN's you search at a time the bigger list you make, make sure to get al least 3-7 ASN's at a time. If you only use 1 you many only get a few IP's like I did.

## Go to [Hacker Target Lookup](https://hackertarget.com/as-ip-lookup/) paste ASN number and search

![SearchASN](/images/SearchASN.png)


## Copy all of the ip's

![IPList](/images/IPList.png)

## Go to [Online Notepad](https://onlinenotepad.org/notepad) or download [Notepad++](https://notepad-plus-plus.org/downloads/)

## then click find and replace

## Enter  :: into the find and replcace bar, then hit remove all of them (this filters out all of the IPv6'a)


As made to by Github so I dont get banned I have to include this disclaimer 

I am not responsible for anything you do with this tutorial, by following this tutorial you agree to this disclaimer.
