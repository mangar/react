

# Tech

```
touch /root/.config/configstore/insight-yo.json; yo fountain-webapp
npm install
bower install
jspm install
```

```
npm run serve
```


- - - 



__New way__
```
docker-compose up
```

<http://localhost:3000>





__Old way__

Start server:
```
docker run -d -p 8081:80 -v `pwd`:/app --name mangar-react  mangar/fountainjs:1.5
```

Login into:
```
docker exec -u 0 -it mangar-react bash
```
