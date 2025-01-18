# Payload Stored XSS
<img src=x onerror​=alert(origin)>
# Payload LFI
Since we are working in a Java environment, I attempted to read /WEB-INF/web.xml because this file often contains a lot of useful information. By navigating to http://admin.target:8443/admin/download?fileName=/WEB-INF/web.xml, I was able to access some juicy information.!
