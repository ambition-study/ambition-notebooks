# ambition-notebooks

Various Jupyter notebooks


We use `--notebook` in `django-extensions` `shell_plus` to start up the jupyter notebook server.

To use any of the notebooks you need a functional `ambition` setup that points to the LIVE database.

Then run any of the notebooks by starting the jupyter server from the console:

    $ python manage.py shell_plus --notebook
    
Your browser should open. Navigate to the desired notebook. 

If you create a new notebook be sure to select `Django Shell-Plus` kernel. 
