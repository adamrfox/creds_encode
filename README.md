# creds_encode
A quick and dirty way to obfuscate credentials

This is a quick and ditry way to obfuscate credentials.  It's probably nowhere near the best way and I'll probably replace it
in my projects with something better someday but it's an option.  I use it in several other projects here for now so if you need
it, feel free to grab it.

The idea is that each array has 3 fields, array_type, user, password.  Each project can decide what array_types it wants to use.
Hopefully user and password are self explanatory.

Syntax is simple:

creds_encode.py file

file is the output file where the obfuscated passwords will be written.
