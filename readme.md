Python 2.7.6

may require sudo privileges

pip install pycrypto
pip install paramiko
pip install pysftp
pip install path.py

setup:

$ cd bin
$ chmod +x doitall

if /usr/local/bin does not exist, create it

Make a symbolic link to program:
$ ln -s /home/james/dev/git/CarBundle/PyFTPer/ftper /usr/local/bin

Note: above command needs full path to source file or won't make the
symbolic link and won't complain. If you already have a symbolic link
to the same command from a different source path, remove (rm) old link
from /usr/local/bin

test setup:

$ ftper -h

help should display
