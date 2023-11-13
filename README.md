# NAME

bandana - run PSGI application

# SYNOPSIS

    To run PSGI application use:

        `perl bandana.pl [options] application-name`

    C<bandana.pl> runs PSGI application

    Options:
        --host|h    - Host to listen on. Default is `localhost`
        --port|p    - Port to listen on. Default is `8000`
        --workers|w - Number of workers to spawn. Default is `1`
    
    application-name must be a script with .psgi extension

    Examples:
        perl bandana.pl -h localhost -p 8000 -w 1 app.psgi

# DESCRIPTION

C<bandana.pl> runs any valid PSGI applications

# AUTHORS

backslash001 <troth@cpan.org>

# COPYRIGHT

This library is free software, you can redistribute it and/or modify it under the same terms as Perl itself.

