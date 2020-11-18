This is an explanation of how to use "singular" and "plural" properly in Rails.

For example, "blogs" is specified for parameters when creating a controller, and "blog" is specified for parameters when creating a model. It seems that various variables are automatically created based on that, so I think it makes sense to use "blogs" and "blog" properly, but it is still confusing because there is no description anywhere.  

Even if I try "rake routes", there are "blog" "new_blog" "blogs" and "confirm_blogs" in Prefix. I don't understand why this is happening at all. 

Ruby on Rails (Rails) is good at doing the manual work for you. With one line, Rails can create the model, controller and view files associated with your application. The downside of using rails generate or its shortcut rails g is that small mistakes like typos are amplified. If Rails is expecting user, and you mistakenly typed users it could cause functionality errors. This cheat sheet will help to avoid those conflicts. If you are comfortable working with Rails, Model–view–controller (MVC) architecture rails generate, this post is for you.

Noun| Singular?| Plural?| Example
------------ | -------------|----------| ----------|
Controller | No | Yes | users_controller products_controller
Model | Yes | No | user.rb product.rb
View | No| Yes | /users /products
Routes | No | Yes | resources :users, :products
Migrations / Table Name | No | Yes | 001_create_users.rb
Seed Data | No | Yes | Seed.rb