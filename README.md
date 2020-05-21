This is a static website which is powered by jekyll, and jekyll is developed based on Ruby. There are couple reason why I'd like to use static site over dynamic site:
* No database
* More secure
* Less maintenance
* Less cost
* Faster 
* Free host in Github

So, in order to run this site, 1) You either can put the whole file in the Github, or 2)you need to have Ruby installed in your local system. 
You would need the following code to run:

``` ruby
gem install jekyll
bundle update
bundle install
bundle exec jekyll serve
# Note: you can use jekyll serve, which means run it without generating the Gemfile.lock
```

