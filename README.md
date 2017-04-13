# heroku-buildpack-nginx

Installs nginx which proxies to port 8080

Add the buildpack 
```bash
heroku buildpacks:add https://github.com/pallavkothari/heroku-buildpack-nginx 
```

Then in your app's Procfile: 

```bash
web: ./nginx-start.sh && <whatever you would normally do> 
```