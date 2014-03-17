opps-blog-sample
=====================

Opps 0.2.2 on Django 1.6.2

## Running the opps blog sample
    
    git clone git@github.com:lerrua/opps_blog_sample.git
    cd opps_blog_sample
    pip install -r requirements.txt
    python manage.py collectstatic --noinput
    python manage.py runserver

### Admin access
    user: root
    password: 1234

### Roadmap
* Authentication.
* Publish texts feature. 
* Tags and categories.
* Content:
 - Title.
 - Author.
 - Date/time published.
 - Tags.
* Search (by title/author).
