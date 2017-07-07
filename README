Metlstorm's SSH-'Jacker
Presented at Blackhat USA 05 and Defcon 0x0d, July 2005

Given ptrace access to a running SSH client process (ie, root or same user) it w
ill give you a shell at the other end.

Requires:
        - python (tested with 2.2, 2.3)
        - GDB

The current list of SSH versions/builds it's known to jack is in a comment near
the top of the script. The current scheme by which it generates the code to inje
ct is not as leet as it should be; perhaps I've improved it by now.

If you're reading this from the Blackhat con CD, then go to blackhat.com and get the newer one, because this one has some known deficiencies, namely:
        - Doesn't work on SCP or remote execution SSH sessions
        - SIGWINCH wakeup technique is only applicable when the client has a tty
, which isn't always the case

These are supposed to be fixed in time for BH/Defcon, but the CD deadline looms.
..

PDF of the presentation also included.

Flames, abuse, job offers, and propositions of iniquitious behavior to metlstorm@storm.net.nz
