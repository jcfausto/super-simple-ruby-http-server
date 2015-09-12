# The Super Simple Ruby Http Server
A simple ruby WEBrick http server to use for development and test purposes.
## How to use

```sh
$ git clone https://github.com/jcfausto/super-simple-ruby-http-server.git
$ cd super-simple-ruby-http-server
$ ruby server.rb
```
## Root Folder

The ./public folder is where the server will look for resources. Put your files there. 

If you want to change to another folder, just edit server.rb and edit the root attribute:

```ruby
# root directory set do ./puglic by default.
root = File.expand_path './choose-your-root-folder'
```

## It is really super simple

Yes! It is. But, if you want, you could for example respond to ```POST``` requests and return json. Useful to mock api calls for example.  

More info here: http://docs.ruby-lang.org/en/2.0.0/WEBrick/HTTPServer.html

### Contact
Follow [jcfausto](http://twitter.com/jcfausto) on Twitter

My website: [jcfausto.com](http://jcfausto.com)

September, 2015.
