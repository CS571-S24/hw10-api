build
```bash
docker build . -t ctnelson1997/cs571-s24-hw10-api
docker push ctnelson1997/cs571-s24-hw10-api
```

run
```bash
docker pull ctnelson1997/cs571-s24-hw10-api
docker run --name=cs571_s24_hw10_api -d --restart=always -p 58110:58110 -v /cs571/s24/hw10:/cs571 ctnelson1997/cs571-s24-hw10-api
```

run fa
```bash
docker pull ctnelson1997/cs571-s24-hw10-api
docker run --name=cs571_fa_s24_hw10_api -d --restart=always -p 59110:58110 -v /cs571_fa/s24/hw10:/cs571 ctnelson1997/cs571-s24-hw10-api
```
