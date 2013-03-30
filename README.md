hgrep
=====

Output header + grep matches

SYNOPSIS
--------

hgrep [grep options]


DESCRIPTION
-----------

Tries to work as much like grep as possible.

Prior to any matches, always output the first line of each input.  Handles
stdin as well a file inputs.

EXAMPLES
--------

ps -efl | hgrep someuser

Outputs the header from ps (no one remembers the order of the fields) and
any lines containing /someuser/.
