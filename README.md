<h1 align="center">
  <img src="https://d1q6f0aelx0por.cloudfront.net/product-logos/81630ec2-d253-4eb2-b36c-eb54072cb8d6-golang.png" width="100px"><br>
  Go Server
 </h1>

A barebones Go app, which can easily be deployed to Heroku.


## Running Locally

Make sure you have [Go](http://golang.org/doc/install) version 1.12 or newer and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```bash
git clone https://github.com/alphaolomi/go-server.git
cd go-server
go build -o bin/go-server -v .
heroku local
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```bashsh
heroku create
git push heroku master
heroku open
```
