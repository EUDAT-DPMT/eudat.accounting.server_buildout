EUDAT Accounting Server
=======================

Installation
------------

.. code:: shell

    git clone git@github.com:EUDAT-DPMT/eudat.accounting.server_buildout.git
    cd eudat.accounting.server_buildout.git
    python -m venv .
    bin/pip install -r requirements.txt
    bin/buildout


Running
-------

.. code:: shell

    bin/instance fg|start
