 
 rails generate migration User 
 rails generate migration User user_name email:string password:string description:text first_name:string last_name:string boolean is_admin
 
 rails g Movie id:integer   title:string   synopsis:text   director:string  original_soundtrack:string   release_date:date
 
 
  bundle install

rails g devise:install
Dans config/environments/developpement.rb, j'add cette ligne =>
config.action_mailer.default_url_options = { host: 'localhost', port: 3000 } 


rails db:create
rails g devise User



*****
bac a une migration

git reset .
git clean -df
git checkout -- .