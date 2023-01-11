Conda recipe for QDOAS
======================

This is the Conda recipe for `QDOAS <https://github.com/UV-VIS-BIRA-IASB/QDOAS>`_.

The build scripts support ``linux-64`` and ``osx-64``.

The generated packages can be found on `Anaconda Cloud <https://anaconda.org/stcorp-forge/qdoas>`_.

.. code-block:: bash

    $ conda install -c stcorp-forge -c conda-forge qdoas


Mac specific build instructions
-------------------------------

Download the 10.9 SDK from e.g. https://github.com/phracker/MacOSX-SDKs and put this in /opt.
Then set the SDKROOT environment variable to SDKROOT=/opt/MacOSX10.9.sdk before building the QDOAS conda package.
