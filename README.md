#Emblem

Emblem is a simple CLI app for manipulating emblems for caja|nautilus.

It treats emblems on a given file as a set, and allows for easy addition/removal/toggling/clearing
of emblems for either a single file or group of files.

It is a wrapper around `gvfs-info` and `gvfs-set-attribute`.
I wrote it to practice some ruby scripting by expanding a simpler bash version, which I had written because I'd found the GUI way of manipulating emblems rather clumsy.

(There's no easy way to set emblems en-masse or to delete only some in the provided GUI.)


