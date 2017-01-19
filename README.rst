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
    
Running
-------

.. code:: shell

    bin/instance fg|start

