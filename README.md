# TWITOR

Twitor (Twit on Rails), previously known as Twito, is an app like Twitter built on top Ruby on Rails for educational purpose. This is a project from Ruby training held by Digital Talent Scholarship, funded by KOMINFO (Ministry of Communication and Information Technology Indonesia) 

![Twitor](twito.png)



## Requirement

- Ruby 2.7.6
- Rails 6.1.6.1
- PostgreSQL
- Hosting (Optional)

## How to use

- clone it
- run `bundle install`
- run `rails db:create`
- run `rails db:migrate`
- run `rails db:seed`
- open `http://localhost:3000/`
- login with username `budi@example.com` and password `123`

## Troubleshooting

### Cross Platform

I have problem during installation this repo that I build on my Mac to Linux environment. So I should run `bundle lock --add-platform x86_64-linux` before cloning this repo to production environment. [source](https://calvin.my/posts/add-platform-to-ruby-application)

### Gem Spring Error

If you face problem with this gem. Just disabling it by `export DISABLE_SPRING=true`. [source](https://til.hashrocket.com/posts/apfwqplcrk-disable-spring-in-rails-with-disablespring) 



