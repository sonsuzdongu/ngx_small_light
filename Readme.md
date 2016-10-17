# Nedir
[Nginx Small light](https://github.com/cubicdaiya/ngx_small_light) kullanarak WebP kullanımını anlatan basit örnek

## Kurmak için

Dizin içinde

```docker build -t sonsuzdongu/ngx_small_light .```


## Çalıştırmak için

```bash
docker run \
    --rm \
    -it \
    --name ngx \
    -p 80:80 \
    -p 8080:8080 \
    -p 8090:8090 \
    -v `pwd`/html:/opt/nginx/html/ \
    sonsuzdongu/ngx_small_light
```

## Kullanım

[http://localhost](http://localhost)
