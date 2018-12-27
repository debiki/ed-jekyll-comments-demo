FROM ruby:2.5.0

RUN mkdir /opt/ruby


COPY Gemfile      /opt/ruby/
COPY Gemfile.lock /opt/ruby/

RUN \
  cd /opt/ruby/ && \
  bundle install

RUN apt-get update && \
		apt-get -y install vim

EXPOSE 4000
EXPOSE 4002

CMD cd /opt/volume/jekyll-site && bundle exec jekyll serve --host 0.0.0.0 --port 4002


