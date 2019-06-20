As a blogger, I want my own blog, so that I can share my thoughts and ideas on my own site without having ads or paying fees to hosting companies.

Set up your Ruby on Rails environment with the following:
- ruby version 2.2.2 or later
- sqlite3
- rails version 5.2.1 or later
- [rspec-rails 3.8 or later](https://github.com/rspec/rspec-rails)
- capybara-rails 3.16.2 or later

Generate a new rails application called "blog"

Scenario 1
1. Given a command line
2. When I type `ruby -v`
3. Then I see a response with version "ruby 2.2.2~" or greater

Scenario 2
1. Given a command line
2. When I type `sqlite3 --version`
3. Then I see a response with a sqlite version number

Scenario 3
1. Given a command line
2. When I type `rails -v`
3. Then I see a response with version "Rails 5.2.1" or greater

Scenario 4
1. Given a command line
2. When I type `rspec -v`
3. Then I see a response with version "RSpec 3.8" or greater

Scenario 5
1. Given a command line in the blog folder
2. When I type `bundle show capybara`
3. Then I see a response which includes "capybara-3.16.2" or greater
