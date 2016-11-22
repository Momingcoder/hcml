hcml
===========

.. image:: https://travis-ci.org/Momingcoder/hcml.svg?branch=master
    :target: https://travis-ci.org/Momingcoder/hcml

A plugin for Hachi_ to detect meaningless sentences.

.. _Hachi: https://github.com/guokr/Hachi

Usage
------

::

    > m = Meaningless()
    > m.predict(message)

Configuration
------------------

::

    > ('hcml', 'Meaningless()', 'meaningless')

Dependence
------------

* jieba

Attention
-----------

You need to provide English Words in ``./data/`` .

Of course you can simply copy from this package.
