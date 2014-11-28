prwd
----

Pseudo-random password generator

How to
------

Give command, recieve password :
::

   $ prwd
   g=h^9[L\

Ask for help, get help :
::
   $ prwd -h
   usage: prwd [-h] [-A] [-D] [-S] [-n N]

   Pseudo-random password generator

   optional arguments:
     -h, --help  show this help message and exit
     -A          Password will contain ascii characters (default : yes)
     -D          Password will contain digital characters (default : yes)
     -S          Password will contain special characters (default : yes)
     -n N        Password size (default : 8)

Need special password, get special password :
::

   $ prwd -S -D -n 30
   |[4]0/4_6]0~##'2=~%/+[~/*]//|#
