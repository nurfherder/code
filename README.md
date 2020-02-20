code
====

This script is largely inspired by [ghq][1], a commandline tool written in golang that helps manage sourcecode repositories.

Deploy:
-------

**Prerequisites:**

 * A POSIX shell
 * ~/bin in your path
 * git

**Procedure:**

The deployment assumes you will have ~/bin in your PATH.

Clone repo to your home directory:

    git clone git://github.com/nurfherder/code.git ~/code/github.com/nurfherder/code

Install into ~/bin:

    cd ~/code/bin/slink
    ./slink

[1]: https://github.com/x-motemen/ghq
