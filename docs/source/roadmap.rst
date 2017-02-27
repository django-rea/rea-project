========
Road map
========

Refactoring into separate applications
--------------------------------------

One of the main concerns at the moment is the code base is getting huge and it's difficult to newcomers to navigate
and make changes as it is. So we are following the next steps in order to produce better artifacts on which to work on:

* Refactor models into multiple files.
* Refactor views into multiple files and make use of Django's generic class views whenever is possible.
* Introduce DDD concepts such as factories and services to alleviate the logic present in views and forms.
* And finally split into Django applications the different parts.


Unify docs under the Sphinx umbrella
------------------------------------

Another important issue to raise is we are using different formats to document the system. This ends up making almost
impossible to produce consumable artifacts by end users and developers.
`Sphinx <http://www.sphinx-doc.org/en/stable/tutorial.html>`_ is a well known documentation tool among the Python
community able to produce html/pdf/epub documents containing formulas, images, diagrams and structured text. Furthermore
we get the ability to publish these documents in `readthedocs.org <http://readthedocs.org>`_ which will be good to
ease diffusion.

Update to last LTS django release
---------------------------------

When we have gotten all this refactoring, we are going to update all code to `1.11 django release <https://docs.djangoproject.com/en/1.11/releases/1.11/>`_, so we can use the new features of this version and keep the project sustainable for a long time.   
