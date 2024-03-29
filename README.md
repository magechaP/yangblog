# Personal-Blog

# Yang Lanti

## User Requirements

+ [x] As a user I would like to view the blog posts submitted
+ [x] As a user I would like to comment on blog posts
+ [x] As a user I would like to view the most recent posts
+ [x] As a user I would like to alerted when a new post is made by joining a subscription.

## Writer Requirements

+ [x] As a writer I would like to sign in to the blog.
+ [x] As a writer I would also like to create blog from the application.
+ [x] As a writer I would like to delete comments that I find insulting or degrading.
+ [x] As a writer I would like to update or delete blogs i have created.


## Specifications

[SPECS.md](https://github.com/MutumaMutuma/Personal-Blog/blob/master/specs.md)

### Requirements
This project was created on a debian linux platform but should work on other unix based[not limited to] sytems.

* Python 3.6

### Cloning the repository

```git clone https://github.com/magechaP/yangblog.git```


### Database migrations

```bash
# first initialize the database if the migrations folder does not exist
python manage.py db init
# create  a migration
python manage.py db migrate -m "initial migration"
# upgrade
python manage.py db upgrade
# insert initial data
python manage.py insert_initial_data
```

### Installing dependencies

```
pip3 install -r requirements
```

### Prepare environmet variables

In start.sh file, in the root folder

```bash
 export MAIL_USERNAME=YOUR EMAIL
 export MAIL_PASSWORD=EMAIL PASSWORD
 export ADMIN_MAIL_USERNAME=ADMIN ACCOUNT EMAIL
```



### Creating a virtual environment

```
python3.6 -m virtualenv virtual-blog
source virtual-blog/bin/activate
```
### Running Tests

```bash
python3.6 manage.py test
```


## Live Demo

The web app can be accessed from the following link.



## Technology used

* [Python3.6](https://www.python.org/)

* [Flask](http://flask.pocoo.org/)

* [Heroku](https://heroku.com)

* [Bootstrap](https://bootstrapcdn.com)

## Contributing

- Git clone [https://github.com/magechaP/yangblog.git] 


## License

MIT License

&copy; Yang Lanti
