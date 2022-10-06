Add [jenkins.conf](https://github.com/pushkarlaulkar/jenkins-nginx-proxy/blob/main/jenkins.conf) to /etc/nginx/conf.d

Afterwards restart nginx service

If you encounter Bad Gateway try below command


```
setsebool -P httpd_can_network_connect 1
```
