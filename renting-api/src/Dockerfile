FROM ruby:2.6.3
WORKDIR /usr/src/app
COPY Gemfile Gemfile.lock ./
RUN bundle install 
COPY . .
CMD ["bundle","exec","rails","server","-p","5004","-b","0.0.0.0"]