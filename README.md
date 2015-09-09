# SYNOPSIS

UI and REST api to [swat](https://github.com/melezhik/swat) engine.

# Features List

    ## UI
    - list of available / installed swat packages
    - list of local packages
    - install/update/remove site package
    - run test manually

    ## RESTAPI
    - run swat test ( local/swat package ) against a given host and return result in required format:
        - TAP
        - nagios
        - sensu

# INSTALL

    perl Makefile.PL
    make
    make test
    make install

# USAGE

    # run swatapi server

    $ swatapi -d

# HOME PAGE

https://github.com/melezhik/swatapi

# COPYRIGHT

Copyright 2015 Alexey Melezhik.

This program is free software; you can redistribute it and/or modify it under the same terms as Perl itself.

# AUTHOR

Alexey Melezhik
