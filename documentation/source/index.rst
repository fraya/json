json
====

.. current-library: json
   
.. toctree::
   :maxdepth: 2
   :hidden:

   reference

This library provides essential functionality for working with JSON
data. JSON (JavaScript Object Notation) is a lightweight data
interchange format that is easy for humans to read and write, and easy
for machines to parse and generate.

The json library offers two primary methods to facilitate the
conversion between JSON strings and Dylan data structures, making it
straightforward to integrate JSON data handling into your Open Dylan
applications. This methods are:

:gf:`parse-json`
    This method takes a JSON-formatted string and converts it into an
    Open Dylan table. This function is useful when you need to process
    JSON data received from external sources, such as web APIs or
    configuration files.

:gf:`print-json`
    The ``print-json`` function takes an Open Dylan table and converts
    it into a formatted JSON string. This is useful for serializing
    Open Dylan data structures into JSON format for storage,
    transmission, or display purposes.


Indices and tables
==================

* :ref:`genindex`
