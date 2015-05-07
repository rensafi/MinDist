DATA
====

advertisedprefixes.json
-----------------------

This file contains prefixes advertised by ASNs within the countries listed in me_cos.txt.
It is generated from the (ip2country)[http://github.com/willscott/ip2country] database,
which takes the routebricks originas file and merges that list of advertised BGP prefixes
with the aut-nums list of country registratiosn to determine the country of registration
of each ASN.
The format is a JSON object, where keys are a CIDR format of 'unsigned-int-of-IP/netmask',
and value is the 2 letter country code.

me_cos.txt
----------

Countries of interest in the middle east.
