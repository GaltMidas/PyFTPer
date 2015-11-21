Python 2.7.6

may require sudo privileges

pip install pycrypto <br />
pip install paramiko <br />
pip install pysftp <br />
pip install path.py

test installs:

$ python <br />
>>> import Crypto <br />
>>> import paramiko <br />
>>> import pysftp

troubleshoot installs:

if can't pip install try this first, <br />
$ apt-get install python-dev

setup:

$ cd bin <br />
$ chmod +x ftper

if /usr/local/bin does not exist, create it

Make a symbolic link to program:
$ ln -s /home/james/dev/git/CarBundle/PyFTPer/ftper /usr/local/bin

Note: above command needs full path to source file or won't make the
symbolic link and won't complain. If you already have a symbolic link
to the same command from a different source path, remove (rm) old link
from /usr/local/bin

test setup:

$ ftper -h

should display the help
