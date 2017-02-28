============
Introduction
============

The `django-rea <https://github.com/django-rea>`_ organization is created in aim to create a set of building blocks on
which other Django apps can build upon to create network resource planning systems - NRP, as opposed to the more
restricted common patterns we encounter in enterprise resource planning systems - ERP.

The project starts from the `valuenetwork <https://github.com/valnet/valuenetwork>`_ project, centered around
`Open Value Networks <http://valuenetwork.referata.com/wiki/Main_Page>`_.
This evolved into a NRP gravitating towards openness and transparency. NRP was co-designed and is in daily use by `Sensorica <http://www.sensorica.co/>`_.

The NRP software was then adopted, `forked <https://github.com/FreedomCoop/valuenetwork/>`_ , and changed, by Freedom Coop for their Open Collaborative Platform (OCP). They upgraded from Django 1.4 to Django 1.8, added the ability to handle the digital currency FairCoins, added a new app called work, with some separation, protections, and permissions between different organizations using the same system, added a membership procedure, and improved the menus and look-and-feel. OCP is in daily use.

The Freedom Coop fork was then `forked again <https://github.com/gopacifia/DEEP/>`_ by GoPacifia for their Democratic Emancipatory Economy Platform (DEEP), which is still under development.

And the Matrioshka project, a spinoff from Sensorica, also wants to use the same code base, and is starting by using OCP.

The goal of this django-rea project is to unify all of those forks and modularize the code base, so all of those organizations can work on the same core software, and separate out all of the features that not everybody wants to use into optional modules.  A secondary goal is to be able to be able to support future apps that could be even more limited than these groups need. 

As we understand somebody's needs might be different than those we have been using it for thus this project.
Which is born to create a set of modular apps on which to develop business apps. In a sense it's another framework in
your toolbox.

In **django-rea** we are going a step forward generalizing and modularizing the previous projects since we think and
understand `REA modelling <https://msu.edu/~mccarth4/>`_ provides an invaluable asset in business model driven
applications.

We encourage everyone to participate.
