Rails 4, Apress
11/24/2018, Sat

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
13. rails g model Article (skipped)   
14. rails db:migrate, p34 (skipped) 
15. rails generate controller articles (skipped)
16. rails generate scaffold Article title:string body:text published_at:datetime --skip-migration --force, pg39
17. 
18.



