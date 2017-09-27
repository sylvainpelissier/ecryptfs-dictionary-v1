# eCryptfs v1 hash dictionary
In previous versions of eCryptfs-utils, the signature of the wrapping key consisted of 65337 iterations of SHA-512 of the user password with the default 0x0011223344556677. This behaviour leads to precomputed dictionary and rainbow table attacks on the user password of systems using eCryptfs for home folder encryption. I provide a precomputed dictionary of the rockyou password list.

The file is also available [here](https://mega.nz/#!kxMjQCpI!H4V1XsKe4DOmv6g_NQP-Jx2GhO_-Yv8A0ALxxGCkvxw).

# Reference
[CVE-2014-9687](http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2014-9687)
# License
Copyright (c) 2015 Nagravision SA

Under CC0 license <http://creativecommons.org/publicdomain/zero/1.0/>
