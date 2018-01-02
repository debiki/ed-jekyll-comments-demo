FROM ruby:2.5.0

RUN mkdir /opt/ruby

COPY Gemfile      /opt/ruby/
COPY Gemfile.lock /opt/ruby/

RUN \
  cd /opt/ruby/ && \
  bundle install

EXPOSE 4000

CMD cd /opt/volume/jekyll-site && bundle exec jekyll serve --host 0.0.0.0


