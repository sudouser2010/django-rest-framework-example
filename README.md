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
pip install -r requirements.txt
  ```
  
##step5##
####Create a superuser####
  ```bash
./manage.py createsuperuser
  ```  
  
##step6##
####Start Django develop application server####
This runs the site on port 9000
  ```bash
./manage.py runserver 0.0.0.0:9000
  ```  
  
