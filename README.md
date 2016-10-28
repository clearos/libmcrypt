# libmcrypt

Forked version of clamav with ClearOS changes applied

* git clone git+ssh://git@github.com/clearos/libmcrypt.git
* cd libmcrypt
* git checkout epel7
* git remote add upstream git://pkgs.fedoraproject.org/libmcrypt.git
* git pull upstream epel7
* git checkout clear7
* git merge --no-commit epel7
* git commit
