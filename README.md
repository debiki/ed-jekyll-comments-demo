

Start the Docker Ruby container like so:

```
sudo docker-compose run --rm ruby bash
```



root@500819b22597:/opt/volume/jekyll-site# history
    1  cd /opt/volume/
    2  bundle exec jekyll _3.3.0_ new
    3  cat Gemfile 
    4  bundle install
    5  bundle exec jekyll _3.3.0_ new
    6  bundle exec jekyll _3.6.2_ new
    7  cat Gemfile 
    8  gem install jekyll bundler
    9  jekyll new jekyll-site
   10  cd jekyll-site/
   11  ls
   12  bundle exec jekyll serve
   13  history


root@a93cb8f79711:/opt/volume# cd jekyll-site/
root@a93cb8f79711:/opt/volume/jekyll-site# bundle exec jekyll serve


