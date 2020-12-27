# SHA-3 Checksum
Print or check SHA-3 checksums.
With no FILE, or when FILE is -, read standard input.

# Usage
sha3sum [OPTION]... [FILE]...

**Options**

***-a*** [*NUM*] choose a SHA-3 algorithm:

* ***224*** SHA3 224-bit (default)

* ***256*** SHA3 256-bit

* ***384*** SHA3 384-bit

* ***512*** SHA3 512-bit
                             
***-c, --check***      read sums from the FILEs and check them

***--tag***            create a BSD-style checksum

***--ignore-missing*** don't fail or report status for missing files

***-q, --quiet***          don't print OK for each successfully verified file

***-s, --status***        don't output anything, status code shows success

***--strict***         exit non-zero for improperly formatted checksum lines

***-w, --warn***       warn about improperly formatted checksum lines

***-h, --help***       display this help and exit

***-v, --version***    output version information and exit

# Requirements
`bash openssl`

**Supported OS**

Guaranteed to work on GNU/Linux like Debian 10, Ubuntu 20.04 or higher
