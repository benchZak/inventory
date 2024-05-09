#Usefull commands

# Set environment and execution
$ python3 -m venv /path/to/new/environment  <br />
$ source /path/to/new/environment/bin/activate  <br />
$ pip install django  
$ pip install crispy-bootstrap5  
$ pip install django-crispy-forms

# Inside Project Folder
$ python3 manage.py startapp inventory  <br />
$ python3 manage.py migrate  <br />
$ python3 manage.py createsuperuser  <br />
$ python3 manage.py runserver 0.0.0.0:8000 

#db read only  <br />
sudo chown -R user:user inventory

# Firewall 
$ sudo iptables -A INPUT -p tcp --dport 8000 -j ACCEPT
