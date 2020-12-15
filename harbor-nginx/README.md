# harbor

用于配合 Harbor 实现域名代理


```bash
docker run -d --restart always \
            -p 80:80 -p 443:443  \
            --name harbor-nginx  \
        chenmins/harbor-nginx
```
