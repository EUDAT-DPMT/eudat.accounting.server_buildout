EUDAT Accounting Server
=======================

Installation
------------

.. code:: shell

    git clone git@github.com:EUDAT-DPMT/eudat.accounting.server_buildout.git
    cd eudat.accounting.server_buildout.git
    virtualenv-2.7 .
    bin/pip install zc.buildout
    bin/buildout bootstrap
    bin/buildout

Or as an alternative (depending on the Linux distribution and their version)

.. code:: shell

    git clone git@github.com:EUDAT-DPMT/eudat.accounting.server_buildout.git
    cd eudat.accounting.server_buildout.git
    virtualenv-2.7 .
    bin/python bootstrap-buildout.py
    bin/buildout

    
Running
-------

.. code:: shell

    bin/instance fg|start

