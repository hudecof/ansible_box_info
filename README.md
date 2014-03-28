box_info
========

This roles enable the server production state indentifiaction on the command prompt.

Requirements
------------
This role requires Ansible 1.4 or higher, and platform requirements are listed
in the metadata file. It should work also with lower version, but I have never tested it.

Role Variables
--------------
Please readme the descriptions in the

    defautls/main.yml

The most important variable is `box_info_type`. This variable adds the colored server production state prefix.

Possible values are

- `prod`: prefix is RED `P`
- `test`: prefix is YELLOW `T`
- `dev`: prefix is GREEN `D`
- `unknown`: prefix is WHITE `U`, this is default

There is also user `ROLE` identification

- `root`: red prompt
- `others`: green prompt

Dependencies
------------

None 

License
-------

BSD

Author Information
------------------

Peter Hudec
