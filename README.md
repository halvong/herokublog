Rails 4, Apress
11/16/2018, Fri

#database
sudo systemctl start postgresql
psql -d herokublog
tom:tom

#Steps
1. modified config/database.yml
2. rails db:schema:dump
3. rails g controller saluation
4. updates app/controller/saluation_controller.rb
5. creates app/views/saluation/hello.html.erb
6. copy Procfile (heroku command) from another project.
7. create app in heroku dashboard: herokublograils4
8. heroku git:remote -a <app name>
9. git push heroku master
10. heroku open
11. heroku ps:scale web=1
12. rails db:migrate
    heroku run rails db:migrate
13. rails g model Article   
14. rails db:migrate, p34 
15. rails generate controller articles
16. rails generate scaffold Article title:string body:text published_at:datetime --skip-migration --force



