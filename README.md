rmSpaces is a util to help remove spaces from filenames. rmSpaces operates on files
in the current working directory (and/or below).

rmSpaces takes spaces out of filenames while maintaining filename readability.
It removes trailing and leading spaces, removes spaces after or before dots (.),
pluses (+) etc.  It removes a space when subsequent words would result in a
'camel cased' name construct (eg. aaaBbbCcc).  When rmSpaces can not remove a
space, i.e.; readability would suffer, rmSpaces replaces the space with
an underscore (_).
