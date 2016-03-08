# Bootstrap Star Wars Site

This is an improved version of the [Simple Star Wars Site][1]. This version was
made using the [Bootsrap CSS and JS framework][2].

## Serving the site locally

Although this site can be viewed by simply opening the `.html` files, you would
get a better user experience by serving it using Python's `SimpleHTTPServer` or
`http.server` modules.

To serve this site locally, execute the following commands in a terminal window:

> For this to work, you will have to install [Python][3] on your machine.

```
$ cd simple-starwars-site
$ python -m SimpleHTTPServer 8080  # If you have Python 2.7 installed
$ python -m http.server 8080       # If you have Python 3 installed
```

After this, you can fire up your favorite web browser and put
[http://localhost:8080][4] in the address bar.

[1]: https://github.com/rukbotto/simple-starwars-site
[2]: http://getbootstrap.com/
[3]: https://www.python.org/downloads/
[4]: http://localhost:8080
