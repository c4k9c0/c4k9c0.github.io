---
title: Search
---

## What did you do last week?  

This past week I began to see the light at the end of the tunnel. I started project 5 and have a pretty good understanding of what we need to do. I set
up all of the front end requirements for search which included using [Bootstrap's Modal](https://angular-ui.github.io/bootstrap/) and 
[this](http://www.prepbootstrap.com/bootstrap-template/searchnavbar) navbar template. Bootstrap's modal is pretty slick because it lets you define a controller, template, and variables for
your modal.

## What is blocking you?  

Currently I am pseudo blocked in deciding what is the best way to implement search in python. I have looked into using [Whoosh](https://pythonhosted.org/Flask-WhooshAlchemy/) but have found
there are compatibility errors with Python 3. There is also [SQLAlchemy-Searchable](https://sqlalchemy-searchable.readthedocs.org/en/latest/) but that would require us to switch from MySQL to PostgreSQL. 
Finally I could write my own search functionality but I hope it doesn't come to this.

## What will you do next week? 

Next week I plan to finish project 5. I will make up my mind on what technology to use for search and then implement search. Towards the end of the week I will write documentation and prepare for our
presentation, unless someone else in my group does that first.

## Class Experience 

This week we finally finished SQL. The SQL stuff really helped my quiz average but was pretty dull otherwise. We then started re-factoring which I find to be a much more interesting
topic. It is nice that Dr. Downing is using the same example the book uses so if we need we can look at the book for additional resources.

## Tip of the week  

For this project whenever we need to add a library my group finds a CDN and puts it in our ```index.html``` file. This isn't really maintainable or scalable so instead we should have used
something like [Bower](http://bower.io/). Bower is a package manager that relies on Node. Bower makes package management a lot easier than maintaining a bunch of CDNs. Bower might not be
as quick as using CDNs but in my opinion not having to rely on a CDN is worth it.