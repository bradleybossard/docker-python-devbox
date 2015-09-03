The purpose of this Dockerfile is for me to try out pyenv and pyvenv without screwing up my machine.

Traditionally, I've just used either python (for Python 2) or python3 (for 3), with virtualenvwrapper
for managing virutal environments.  The two drawbacks to this approach are remembering the different
commands for invoking python, and that virtualenvwrapper "clouds up" the environmnet namespace with
a ton of verbs like workon, mkvirtualenv, setproject etc.  I like the way pyenv and pyvenv solve both
these problems and will most likely use this approach for all my Python dev in the future.
