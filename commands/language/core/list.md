# wp language core list

List all available languages.

[\--field=&lt;field&gt;]
: Display the value of a single field

[\--&lt;field&gt;=&lt;value&gt;]
: Filter results by key=value pairs.

[\--fields=&lt;fields&gt;]
: Limit the output to specific fields.

[\--format=&lt;format&gt;]
: Accepted values: table, csv, json. Default: table

### AVAILABLE FIELDS

These fields will be displayed by default for each translation:

* language
* english_name
* native_name
* status
* update
* updated

These fields are optionally available:

* version
* package

### EXAMPLES

    # List language,english_name,status fields of available languages.
    $ wp core language list --fields=language,english_name,status
    +----------------+-------------------------+-------------+
    | language       | english_name            | status      |
    +----------------+-------------------------+-------------+
    | ar             | Arabic                  | uninstalled |
    | ary            | Moroccan Arabic         | uninstalled |
    | az             | Azerbaijani             | uninstalled |


