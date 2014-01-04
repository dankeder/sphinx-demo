.. this is a comment

Tables
======

Inline ASCII art
----------------

+----------+-------------+--------------+----------------+
| header1  | header2     | header3      | header4        |
+==========+=============+==============+================+
|          | content2    | content3a    | content4       |
| content1 |             | content3b    | content4       |
+----------+-------------+--------------+----------------+
| column span            | col span too                  |
+----------+-------------+--------------+----------------+

Inline Simple table
-------------------

.. table:: some hosts

    ==========  ====== =====  == === ===========
    Hostname       Disk       CPU
    ----------  ------------  ------------------
    ..          size   RPM    #  GHz HyperThread
    ==========  ====== =====  == === ===========
    prod-cmp18  6x600G 15k    12 2.4 Y
    prod-cmp19  6x600G 15k    12 2.4 Y
    prod-cmp20  6x600G 15k    12 2.4 Y
    prod-cmp21  6x600G 15k    12 2.4 Y
    ==========  ====== =====  == === ===========

Include file
------------

.. include:: hosts.txt

Inline CSV
----------

.. csv-table:: some more hosts
   :header: "Treat", "Quantity", "Description"
   :widths: 15, 10, 30

   "Albatross", 2.99, "On a stick!"
   "Crunchy Frog", 1.49, "If we took the bones out, it wouldn't be
   crunchy, now would it?"
   "Gannet Ripple", 1.99, "On a stick!"

Include CSV
-----------

.. csv-table::
   :header-rows: 1
   :file: hosts.csv

