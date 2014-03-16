opps-blog-sample
=====================

Opps 0.2.3-dev on Django 1.6.2


## Install Opps

    git clone git@github.com:opps/opps.git
    cd opps
    python setup.py develop
    
## Running the opps blog sample
    
    git clone git@github.com:lerrua/opps_blog_sample.git
    cd opps_blog_sample
    pip install -r requirements.txt
    python manage.py collectstatic --noinput
    python manage.py runserver


### Roadmap
* Authentication.
* Publish texts feature. 
* Tags and categories.
* Content
 - Title
 - Author
 - Date/time published
 - Tags
* Search (by title/author)
