Tutorials
=========

.. toctree::
   :maxdepth: 5
   :hidden:

   The Data Commons Data Model <data_model>
   Analyzing Employment in California Counties <https://colab.research.google.com/drive/1ZNXTHu3J0W3vo9Mg3kNUpk0hnD6Ce1u6>

We have a number of tutorials that will help acclimate you to how data is
represented in the Data Commons graph and how to use the Python Client API
to access that data.

+-------------------------------------------------+------------------------------------------------------------------------+
| Tutorial                                        | Description                                                            |
+=================================================+========================================================================+
| `The Data Commons Data Model`_                  | This tutorial introduces the Data Commons data model and defines       |
|                                                 | terms that are used throughout the API such as “dcid”,                 |
|                                                 | “triples”, “property label”, “property value” and more.                |
+-------------------------------------------------+------------------------------------------------------------------------+
| `Analyzing Employment in California Counties`_  | This Colab notebook demonstrates how to use Data Commons to access     |
|                                                 | employment statistics provided by the `Bureau of Labor Statistics`_    |
|                                                 | and store them in a :code:`pandas.DataFrame`. The end goal of this     |
|                                                 | tutorial will be to generate a bar chart visualizing the total         |
|                                                 | number of employed persons across all California counties.             |
+-------------------------------------------------+------------------------------------------------------------------------+

.. _`The Data Commons Data Model`: data_model.html
.. _`Analyzing Employment in California Counties`: https://colab.research.google.com/drive/1ZNXTHu3J0W3vo9Mg3kNUpk0hnD6Ce1u6
.. _`Bureau of Labor Statistics`: https://www.bls.gov/
