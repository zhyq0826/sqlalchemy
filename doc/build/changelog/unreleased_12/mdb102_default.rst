.. change::
    :tags: bug, mysql

    Fixed issue where a default of CURRENT_TIMESTAMP would not
    properly reflect when using MariaDB 10.2, as a parenthesis
    is now added to the expression that wasn't being matched.
