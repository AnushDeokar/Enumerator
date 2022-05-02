## The Enumerator
This tool is build for the finding those subdomains which are waste i.e. the cname of these subdomains no longer exists. This is important since these subdomains may led to various types of attacks such as subdomains takeover, phishing attacks etc.

## Running this tool
In order to run this tool write all those subdomains which you want to test in list.txt file. For eg. facebook.com, google.com etc. 
Now execute the following command -
```
./find.sh
```

It is recommended that you use linux because it has all the dependeciencies present otherwise you might need to insert httpx and massdns in your system.

Please Note this tool uses Massdns for finding the CNAME records as it is more reliable and fast.