# Secure kibana dashboards using keycloak

### How it works
The mode of operation is summed up in 3 simple steps:
![](/content/images/2018/02/Presentation1.jpg)

1. External traffic is directed to the keycloak proxy. The proxy decides based on it configuration if the destination needs authentication.
2. The keycloak Proxy work together with Keycloak and redirects the user to the authentication server so the user can login.
3. After a successful login the proxy forwards the user to kibana instance. 

For more details check out this blog: https://aboullaite.me/secure-kibana-keycloak/

![](https://media.giphy.com/media/ewCXHXd5lePqywsOq0/giphy.gif)
