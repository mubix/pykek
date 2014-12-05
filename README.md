Python Kerberos Exploitation Kit
===

PyKEK (Python Kerberos Exploitation Kit), a python library to manipulate KRB5-related data. (Still in development)
For now, only a few functionalities have been implemented (in a quite Quick'n'Dirty way) to exploit  MS14-068 (CVE-2014-6324) .
More is coming...

# Library content
* kek.krb5: Kerberos V5 ([RFC 4120](https://tools.ietf.org/html/rfc4120)) ASN.1 structures and basic protocol functions
* kek.ccache: Credential Cache Binary Format ([cchache](http://www.gnu.org/software/shishi/manual/html_node/The-Credential-Cache-Binary-File-Format.html)
* kek.pac: Microsoft Privilege Attribute Certificate Data Structure ([MS-PAC](http://msdn.microsoft.com/en-us/library/cc237917.aspx))
* kek.crypto: Kerberos and MS specific cryptographic functions

# Exploits
## ms14-068.py
To exploit MS14-068, you need :
 - A (one-way) trust relationship between a domain A and a domain B

