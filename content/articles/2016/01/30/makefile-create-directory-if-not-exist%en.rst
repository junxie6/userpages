[Makefile] Create Directory If Not Exist
########################################

:date: 2016-01-30T02:02+08:00
:tags: Bash, Makefile, Commandline, Existence Detection
:category: Bash
:summary: Makefile - Create a directory if it does not exist. Otherwise do
          nothing.
:adsu: yes


Write a command line in Makefile: Create a directory if it does not exist.
Otherwise do nothing.

.. code-block:: bash

  MYDIR=/home/myaccount/dev
  [ -d $(MYDIR) ] || mkdir -p $(MYDIR)


Tested on ``Ubuntu Linux 15.10``.

----

References:

.. [1] `[Golang] Create Directory If Not Exist <{filename}../../../2017/03/28/go-create-directory-if-not-exist%en.rst>`_
.. [2] `Package write provides a way to atomically create or replace a file or symbolic link. : golang <https://old.reddit.com/r/golang/comments/9sq6x1/package_write_provides_a_way_to_atomically_create/>`_

.. adsu:: 2
