# box_info

This roles enable the server production state identification on the command prompt.

## Requirements

This role requires Ansible 2.1 or higher, and platform requirements are listed
in the meta data file. It should work also with lower version, but I have never tested it.

## Role Variables

Please readme the descriptions in the

    defautls/main.yml

The most important variable is `box_info_type`. This variable adds the colored server production state prefix.

Possible values are

- `prod`: prefix is RED `PROD`
- `test`: prefix is YELLOW `TEST`
- `dev`: prefix is GREEN `DEV`
- `qa`: prefix is GREEN `QA`
- `unknown`: prefix is WHITE `UNDEF`, this is default

There is also user `ROLE` identification

- `root`: red prompt
- `others`: green prompt

## Dependencies

None 

## License

BSD

## Author Information

Peter Hudec
