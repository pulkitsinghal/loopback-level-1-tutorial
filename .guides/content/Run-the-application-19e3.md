* Run as you would any Node application.

```
$ node .
Browse your REST API at http://0.0.0.0:3000/explorer
Web server listening at: http://0.0.0.0:3000/
```

* The url for your box can be found by going to the menu at `Project > Box Info`. Focus on the url that starts with `http` under the `WEB: Static Content` section. It should be something like: `http://<box-name>.codio.io`

* Open a browser window at your public URL:
`<public URL>:3000/explorer`
or
`http://<box-name>.codio.io:3000/explorer`

# Extra credit: Try Arc
StrongLoop Arc will use a different port number each time you run it. You can provide a specific port number via the environment variable PORT, for example: `PORT=4000 slc arc`
