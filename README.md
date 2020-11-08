# Request Header Parser Microservice

<a href="https://brendobrien-request-header.herokuapp.com/api/whoami">https://brendobrien-request-header.herokuapp.com/api/whoami</a>

## Upgrading to heroku 18

https://devcenter.heroku.com/articles/upgrading-to-the-latest-stack#upgrading-an-app

```
heroku stack:set heroku-18 -a brendobrien-request-header
heroku git:remote -a brendobrien-request-header
git commit --allow-empty -m "Upgrading to heroku-18" && git push heroku master
```
