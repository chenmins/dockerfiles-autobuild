# harbor

用于配合 Harbor 实现域名代理


```bash
docker run -d --restart always \
            -e SNIPROXY=${SNIPROXY} \
            -p 80:80 -p 443:443  \
            --name dnsmasq  \
        chenmins/harbor-nginx
```
