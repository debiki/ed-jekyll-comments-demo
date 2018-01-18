
Start the Docker Ruby container like so:

```
sudo docker-compose run --rm ruby bash

# or

sudo docker-compose up -d
sudo docker-compose exec ruby bash
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

Test:
    9  jekyll new jekyll-site
   10  cd jekyll-site/
   11  ls
   12  bundle exec jekyll serve --host 0.0.0.0 --port 4000
   13  history

jekyll serve --host 0.0.0.0 --port 4002




Maybe use?:
https://github.com/daattali/beautiful-jekyll/tree/master/_includes
http://blackrockdigital.github.io/startbootstrap-clean-blog-jekyll/2017/10/29/prophecy.html
https://github.com/camporez/Thinny

https://github.com/camporez/Thinny

https://github.com/johnotander/pixyll ?

