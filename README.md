Rails 4, Apress
10/28/2018, Sun

#database
psql -d herokublog
tom:tom

#Steps
1. modified config/database.yml
2. rails db:schema:dump
3. copy Procfile (heroku command) from another project.
4. create app in heroku dashboard: herokublograils4
4. heroku ps:scale web=1


