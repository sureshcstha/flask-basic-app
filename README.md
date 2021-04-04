Basic App
=========
Install required Python packages
--------------------------------
   pip uninstall Flask-Babel

   pip install Flask-BabelEx
   
   pip install Flask-User
   
   pip install email_validator

Create the basic_app.py file
----------------------------

- Open your favorite editor,
- Copy the example below, and
- Save it as ~/dev/my_app/basic_app.py


- Lines 25-32 configure ``Flask-Mail``. Make sure to use the correct settings or emails
   will not be sent.



Run the Basic App
-----------------
Run the Basic App with the following command::

    cd ~/dev/my_app
    python basic_app.py

And point your browser to ``http://localhost:5000``.


Troubleshooting
---------------

If you receive an EmailError message, or if the Registration form does not respond quickly
then you may have specified incorrect SMTP settings.

If you receive a SQLAlchemy error message, you may be using an old DB schema.
Delete the quickstart_app.sqlite file and restart the app.

If you don't see any translations, you may not have installed ``Flask-BabelEx``,
or you may not have prioritized a supported language in your browser settings.

--------

