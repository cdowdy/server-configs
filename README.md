# server-configs  

# NginX server setup

uses:  
[Nginx 1.6.3 - extras package](http://nginx.org/)  

Built With  
~~[NGX_PageSpeed 1.9.32.1](https://developers.google.com/speed/pagespeed/module/build_ngx_pagespeed_from_source)~~  
~~[Naxsi](https://github.com/nbs-system/naxsi)~~  
~~The rest of the modules buit in can be found here: [Nginx Build Template](https://github.com/cdowdy/corydowdy.com-site/blob/33f37850e2f7991d572a12c61ffa0c86742e20b6/server-configs/nginx-version-modules-TEMPLATE.md)~~  

Originally this had all that above but that sucked to rebuild if an update came along... sooooo I came across [Compiling Third-Party Modules Into Nginx](https://serversforhackers.com/compiling-third-party-modules-into-nginx) and that made it much easier. It now has Mod Security in place of Naxsi (still dont' know if its worth the hassel its not like it was for apache which is fairly simple for me to use)  

References to __h5bp__ are from [h5bp/server-configs-nginx](https://github.com/h5bp/server-configs-nginx)


Other useful links to go along with the headers being set in the various configs are:  
[Security Headers](https://securityheaders.com)  
[Content Security Policy Cheat Sheet](https://www.owasp.org/index.php/Content_Security_Policy_Cheat_Sheet)  
[CSP is Awesome](http://cspisawesome.com/)  
[OWASP Useful Headers](https://www.owasp.org/index.php/List_of_useful_HTTP_headers)  
[OWASP Click Jacking](https://www.owasp.org/index.php/Clickjacking_Defense_Cheat_Sheet)  

