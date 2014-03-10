Wendy Dherin
============

MY SKILL LEVEL: BEGINNER
------------------------
I'm relatively new to programming. I started learning Python about six months ago. I've got the 
fundamentals of Python down now (I'm at the end of the Learn Python the Hard Way tutorial), 
and I'm just at the point where I'm starting to learn to make a web app and learning about frameworks. 
So this Hackbright Hack & Learn Django weekend was perfect timing.

MY PACE: ~12 HOURS
----------------------------------------
* Day 1, parts 1-4
* Day 2, parts 5-6

* It took me a day and a half to complete the tutorial. But I don't feel got a very deep understanding
of what I was doing. I worked on my own through the tutorial, asking mentors when I ran into roadblocks.
* The "testing" part (part 5) was the easiest for me to grok, because it seemed to be the most basic-programming-oriented,
if that makes sense.
* Part 6 was also pretty easy for me to understand, since it was really about CSS.
Parts 1-4 were mostly a haze for me: I could make it work, but I didn't really know why.

GENERAL FEEDBACK
----------------
* In general, the tutorial was easy to follow, but didn't excel and teaching the concepts employed. It seemed to go 
into too much detail at some times and not enough detail at other times.

 * As someone totally green w/r/t frameworks, I think I would have benefited from an initial more-detailed overview of
what a framework is. I read https://docs.djangoproject.com/en/dev/intro/overview/ but didn't understand it. Something 
like "Frameworks 101" would be great! And the overview (linked above) probably went into too much detail unnecessarily
in some parts and not enough detail in others. 
* I'm sorry I can't be more specific than that about this, but for
what it's worth, once I have a deeper understanding, I'd be happy to help revamp the documentation (I'm a 
developmental editor/writer); feel free to contact me at wendydherin@gmail.com to pull me in to such a project.

* Also, hover-over, alt-text definitions for terms would have been great for me too.

* Consider having each part start with a summary list of "What Will Be Covered" and end with a list 
of "What You Should Take Away." This way, a user will know if they groked the core teaching of the part or not. 
Right now, the sections end with statements "Once you feel comfortable with this, go to the next section." Those
kind of statements are hard to measure. What does "comfortable" really mean. So, better would be something like
"Here's what you should understand: a, b, c. If you don't understand a, go over section x again. Etc.

SPECIFIC FEEDBACK
-----------------

Part 1.
------
* under CREATING MODELS:
"Each model is represented by a class that subclasses django.db.models.Model."
QUESTION: For clarity, can "that subclasses" be replaced with "that is a subclass of"?

* under ACTIVATING MODELS:
"Now Django knows to include the polls app. Let’s run another command:
$ python manage.py sql polls"
COMMENT: You should remind the user which directory to be in before running the command

* also under ACTIVATING MODELS:
COMMENT: It would be good to explain the difference between a primary key and an ID, and 
to contrast primary keys with foreign keys.

PART 2.

* under CUSTOMIZING YOUR PROJECT'S TEMPLATES:
QUESTION: Why is "project's" italicized in this header?

* also under CUSTOMIZING YOUR PROJECT'S TEMPLATES:
"Now create a directory called admin inside templates, and copy the template admin/base_site.html 
from within the default Django admin template directory in the source code of Django itself 
(django/contrib/admin/templates) into that directory."
COMMENT: The above paragraph is hard to understand and should be rewritten for clarity.

* also under CUSTOMIZING YOUR PROJECT'S TEMPLATES:
"Then, just edit the file and replace the generic Django text with your own site’s name as you see fit."
COMMENT: In this sentence, it would be good to specify which exactly which text should be replaced.

PART 3.

* under WRITE YOUR FIRST VIEW:
"Let’s write the first view. Open the file polls/views.py and put the following Python code in it:"
QUESTION: Should "put the following" in the above say "add the following"? I ask because I already 
have "from django.shortcuts import render" in the file...

* also under WRITE YOUR FIRST VIEW:
"The next step is to point the root URLconf at the polls.urls module. In mysite/urls.py insert an 
include(), leaving you with:"
COMMENT: For clarity, the above should state more explicitly that the user should change to the 
inner mysite directory and open the urls.py file (NOT the urls.py file that we created in the 
previous step.)


PART 4.

No feedback.

PART 5.

* under IMPROVING OUR VIEW:
"The list of polls shows polls that aren’t published yet (i.e. those that have a pub_date in the future)."
COMMENT: In the code that precedes this statement, the poll that is created is a pub_date of "now," not a 
future date. Therefore, this statement is confusing. It would be clearer if the poll created in the preceding code
actually had a future pub_date.

* also under IMPROVING OUR VIEW:
"response.context_data['latest_question_list'] extracts the data this view places into the context."
COMMENT: In the code that precedes this statement, the "_data" is missing. For clarity, this should be made consistent.







