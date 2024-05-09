#Usefull commands

# Set environment and execution
$ python3 -m venv /path/to/new/environment
$ source /path/to/new/environment/bin/activate
$ pip install django  
$ pip install crispy-bootstrap5  
$ pip install django-crispy-forms

# Inside Project Folder
$ python3 manage.py startapp inventory
$ python3 manage.py migrate
$ python3 manage.py createsuperuser
$ python3 manage.py runserver 0.0.0.0:8000

#db read  only
sudo chown -R user:user inventory

# Firewall 
$ sudo iptables -A INPUT -p tcp --dport 8000 -j ACCEPT
