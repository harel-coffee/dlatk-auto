.. _fwflag_bert_model:
============
--bert_model
============
Switch
======

--add_bert

Description
===========

Adds a BERT feature table.

Argument and Default Value
==========================

Details
=======

Other Switches
==============

Required Switches:

* :doc:`fwflag_d`, :doc:`fwflag_t` , :doc:`fwflag_c`

Optional Switches:

* :doc:`fwflag_bert_model`
* :doc:`fwflag_bert_layers`
* :doc:`fwflag_bert_msg_aggregation`
* :doc:`fwflag_bert_layer_aggregation` 

Example Commands
================

Creates a default BERT feature table.

.. code-block:: bash

	dlatkInterface.py -d dla_tutorial -t msgs -c user_id --add_bert
