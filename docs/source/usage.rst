Usage
=====

.. _installation:

Installation
------------

To use Anix, invite it to your server.

.. code-block:: console

   https://dsc.gg/anix

Setting Anix up for your server
----------------

Anix has a custom prefix command. This can be useful for setting up your own prefix in your server. 
Mention ``@Anix`` in order to get the server's prefix.

.. code-block:: console

   ?setprefix
   
.. note::

   Anix's default prefix is ``?``

The ``kind`` parameter should be either ``"meat"``, ``"fish"``,
or ``"veggies"``. Otherwise, :py:func:`lumache.get_random_ingredients`
will raise an exception.

.. autoexception:: lumache.InvalidKindError

For example:

>>> import lumache
>>> lumache.get_random_ingredients()
['shells', 'gorgonzola', 'parsley']

