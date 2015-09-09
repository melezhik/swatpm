# SYNOPSIS

UI and REST api to [swat](https://github.com/melezhik/swat) engine.

# Features List

    ## UI
    - list of available /installed site swat packages
    - list of local swat packages ( projects )
    - install/update/remove site package
    - show curl call to run swat test for given local/site package
    - run test manually

    ## RESTAPI
    - run swat test ( local/site package ) against a given host and return result in required format:
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
