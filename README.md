# django-rest-framework-example
To get this example working, follow the steps below:

##step1##
####Clone this repository:####
  ```bash
git clone https://github.com/sudouser2010/django-rest-framework-example.git
  ```
  
##step2##
####Set environment variable####
This is useful for this example
  ```bash
export repo=`pwd`/django-rest-framework-example/
  ```
  
##step3##
####Create and activate virtual environment####
  ```bash
virtualenv $repo/env
source $repo/env/bin/activate
  ```

##step4##
####Install Python requirements####
  ```bash
pip install -r $repo/requirements.txt
  ```
  
##step5##
####Sync sqlite database####
  ```bash
python ${repo}tutorial/manage.py migrate
  ```    
  
##step6##
####Create a superuser####
  ```bash
python ${repo}tutorial/manage.py createsuperuser
  ```  
  
##step7##
####Start Django develop application server####
This serves the Django project on port 9000
  ```bash
python ${repo}tutorial/manage.py runserver 0.0.0.0:9000
  ```  
  
##step8##
####Login to Django Rest Framework as a superuser####
Navigate to this url in the browser <br/>
http://127.0.0.1:9000/api-auth/login/

##step9##
####View API's####
Navigate to urls in the browser <br/>
http://127.0.0.1:9000/<br/>
http://127.0.0.1:9000/users/</br>
http://127.0.0.1:9000/groups/
