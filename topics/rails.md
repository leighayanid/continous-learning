Working with Rails - March 17, 2017
- Today I added a new feature to my simple blogging platform. 
I added a search functionality to able to view all the posts. I used ransack for 
basic searching and I learned how the gem works and was able to use it on my system.

Authorization - April 17, 2017
- Yesterday, April 16, 2017, I started to learn how to authorize a user in a rails app.
I learned about Cancancan gem which is a library that restricts user what resources he is allowed to access, how it is use in the rails app and how to create abilities. I applied the gem on my [Pictogramm](https://github.com/leighayanid/pictogramm) app, and authorize a user to make changes in his own photos and only allow other user to read/view photos. 
- Link to [Cancancan](https://github.com/CanCanCommunity/cancancan) gem

Friendly URL's - May 13-15, 2017
- Learned friendly_id gem which makes a friendly and pretty url instead of the default numeric id's for models. 
- Included this gem on my [Pictogramm](https://github.com/leighayanid/pictogramm) app, implemented on Photo and User model. 
	- How to implement
		- add gem 'friendly_id' then run bundle install
		- extend FriendlyId on models you want to have a pretty url
		- use friendly_id method with :slugged parameter and the model's attribute you want to use display on the URL
		- rails g friendly_id will generate migrations for slug history. 
- Link to  [Friendly_id](https://github.com/norman/friendly_id)