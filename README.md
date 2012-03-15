# SpreeCasts Episode #4: Using Static Content Extension

Setup sample store: 

```
gem install rails -v=3.1.4
gem install spree
rails _3.1.4_ new episode-4
cd episode-4
spree install --auto-accept
```

## Install the 1-0-stable branch of spree_static_content

Add to the bottom of Gemfile:

```
gem 'spree_static_content', :git => "git://github.com/spree/spree_static_content.git", :branch => "1-0-stable"
```

Install the extension and run the migrations:

```
bundle install
bundle exec rails g spree_static_content:install
```
