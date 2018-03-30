Computing Resource
================================================================================

Survey
--------------------------------------------------------------------------------

We suggest 50Gb memory and 25 cpu for mecat alignment.

Assembly
--------------------------------------------------------------------------------

The size of memory depends on the genome sizes. Usually the memory size of the SOAPdenovo program is about 100
times the estimated genome sizes.

You can easily change these settings in the config.cfg file.

Storage
--------------------------------------------------------------------------------

For a genome ~850Mb size with 50x illumina shore reads, the storage for each folder is:

.. csv-table::
   :file: tables/storage.tsv
   :delim: tab
   :header-rows: 1
   :widths: 15, 10, 75

To save you storage, you can nohup the shell 'delete_survey.sh' after you finished runpbjelly.

