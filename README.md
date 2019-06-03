# README

Install the corresponding Ruby, Rails and Gem versions:
* Ruby version 2.6.3p62
  If you've never installed Ruby before, you can follow the instructions here: https://www.ruby-lang.org/en/downloads/
    Verify that you have the correct Ruby version installed by running 'ruby -v' in your terminal

* Rails version 5.2.3
  If you've never installed Rails before, you can follow the instructions here: http://www.installrails.com/
    Verify that you have the correct Ruby version installed by running 'rails -v' in your terminal

* Gems added:
  -Devise 4.6.2
    https://github.com/plataformatec/devise#getting-started
  -Simple Form 4.1
    https://github.com/plataformatec/simple_form
  -Haml 5.1

Clone git repository
  `git clone https://github.com/luminousbeam/file_cabinet.git`

Install all dependencies
  `bundle install`
  
Create db and migrate schema
  `rake db:create`
  `rake db:migrate`

Now run your application
  `rails s`
  
Visit url:
http://localhost:3000/records
