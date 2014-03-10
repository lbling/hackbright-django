Albedith Diaz and Andrea Kramm
======================================================

Things that worked well
----------------------------------
We are both new to Web Development and Django.
For us what worked well was:

* Pair Programming : It was easy to learn together and research any doubts
* Mentors were very helpful
* The intro app functionality was very simple and easy to understand

Things that I had questions about
----------------------------------
Overall the complete tutorial was lacking information about tools that were used during the development.
For example:

* SQLITE3:  How to install it if you have a windows computer
* How to interact with the dababase.
* How to retrieve a table entry and edit it.
* How do regular expressions work... what is ?p exactly doing?
* Where all those methods are coming from (.choise_set(), order_by()...)
* Where to find a complete list of all the methods available.
* How do the generic.ListView and generic.DetailsView methods work. What is this magic all about?

Also, each step in the tutorial instructed the user to type all the code and later on it explained only certain parts 
of what was going on. It would be more helpful if it explained what we were going to do and later on show examples on 
how it was going to be done.

More comments on the sample code would have been helpful. For example comments indicating what each variable was doing and 
any new changes.

An indication saying in what file we were going to write certain code would have been helpful.

A diagram indicating the expected final result Models --> Views --> Template

Section 5 in which we got to test the web app, talked too much about the importance about testing.
Maybe this could have been a separated document that the user can be redirected to if they wanted to learn more about test.

Additional Questions that we had were:

* What does the __unicode__ method do
* How does the was_published_recently.boolean = True displays the check mark.
* How to access the specific entry from a table.... python manage.py shell... poll.object.all()... How do I get a specific object
* Where is the base_site.html... unclear directions on where to find it.
* What are kwargs and how to use them
* How does Django knows which template to retrieve since we didnt specified it in settings.py...TEMPLATE_DIRS
* Where is the TEMPLATE_LOADERS setting?
* What does pk stands for?
* In section 4, Ammend Views: Got an error when accessing the template after changing poll_id to pk. The error was because we were not instructed to update the variable from poll_id to pk in the views.py for the vote view.


