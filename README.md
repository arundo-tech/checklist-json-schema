# checklist-json-schema

The public JSON schema to write your own checklist.

This repo containes the JSON schema describing a checkclist.

The checklist is the central piece in the process of verifying a PDF document
(especially the signed ones).

This schema describes :

* the owner of the schema
* the check trigger method (signature certificate, email, ...)
* the steps of the check process
* some styling elements to apply (logo, colors, ...)

For each step the schema describes :

* a description
* a module type
* the modules arguments

This repo contains :

* the schema in JSON format
* the schema in YAML format
* some examples
* a simple tool to edit/verify checklists based on this schema
* a static documentation
    * VS code / codium helper
    * fields description
    * sample Python code
    
This project source code is not yet published.
We will do so as soon as we fully review it.


