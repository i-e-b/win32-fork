win32-fork
==========

working fork() on windows vista and newer

Behaves like `fork` in Posix systems -- parent process is duplicated, 
the return code of the `fork` call is different between the child and parent:

* Parent receives the child's process ID
* Child receives 0.
