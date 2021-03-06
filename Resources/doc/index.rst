Getting Started With FOSRestBundle
=====================================

Installation
------------

Installation is a quick (I promise!) one-step process:

1. :doc:`Setting up the bundle <1-setting_up_the_bundle>`_

Bundle usage
------------

Before you start using the bundle it is advised you run a quick look over the
six sections listed below. This bundle contains many features that are loosely
coupled so you may or may not need to use all of them. This bundle is just a
tool to help you in the job of creating a REST API with Symfony2.

FOSRestBundle provides several tools to assist in building REST applications:

- :doc:`The view layer <2-the-view-layer>`_
- :doc:`Listener support <3-listener-support>`_
- :doc:`ExceptionController support <4-exception-controller-support>`_
- :doc:`Automatic route generation: single RESTful controller <5-automatic-route-generation_single-restful-controller>`_ (for simple resources)
- :doc:`Automatic route generation: multiple RESTful controllers <6-automatic-route-generation_multiple-restful-controllers>`_ (for resources with child/subresources)
- :doc:`Manual definition of routes <7-manual-route-definition>`_

Config reference
----------------

- :doc:`Configuration reference <configuration-reference>`_ for a reference on
  the available configuration options
- :doc:`Annotations reference <annotations-reference>`_ for a reference on
  the available configurations through annotations

Example applications
--------------------

The following bundles/applications use the FOSRestBundle and can be used as a
guideline:

- The `LiipHelloBundle`_ provides several examples for the RestBundle.

- There is also `a fork of the Symfony2 Standard Edition`_ that is configured to
  show the LiipHelloBundle examples.

- The `FOSCommentBundle`_ uses FOSRestBundle for its API.

- The `Symfony2 Rest Edition`_ provides a complete example of how to build a
  controller that works for both HTML as well as JSON/XML.

.. _`LiipHelloBundle`: https://github.com/liip/LiipHelloBundle
.. _`a fork of the Symfony2 Standard Edition`: https://github.com/liip-forks/symfony-standard/tree/techtalk
.. _`FOSCommentBundle`: https://github.com/FriendsOfSymfony/FOSCommentBundle
.. _`Symfony2 Rest Edition`: https://github.com/gimler/symfony-rest-edition
