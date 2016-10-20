# quepython
Run a python file in the earth0 queue

This script allows you to run a python script on earth0 with the quepython command.

It allows some specifications like qsub does.

Install

Copy and paste the following into a ssh session on earth0.

git clone .......... ;
mkdir ~/bin;
ln -s queuepython.py ~/bin/queuepython;
chmod +x ~/bin/quepython;
source ~/.bashrc;


Then instead of typing python myscripy.py you can now type qpython myscripy.py.

Limitations:
No arguments to python can currently be supplied.
Output to screen is saved as qpython.log
