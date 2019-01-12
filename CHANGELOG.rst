
Changelog
---------

All notable changes to this project will be documented in this file.

The format is based on `Keep a Changelog`_.

  **Types of changes:**

  - **Added**: for new features.
  - **Changed**: for changes in existing functionality.
  - **Deprecated**: for soon-to-be removed features.
  - **Removed**: for now removed features.
  - **Fixed**: for any bug fixes.
  - **Security**: in case of vulnerabilities.


`UNRELEASED`_
^^^^^^^^^^^^^


Added
"""""

- The connector ``get_job()`` methods accepts two new parameters for including
  and excluding specific fields from the response. (#6)

Changed
"""""""

- The IBMQ Provider has been moved to an individual package outside the
  Qiskit Terra package.
- The exception hierarchy has been revised: the package base exception is
  ``IBMQError``, and they have been grouped in ``.exception`` modules. (#5)



.. _UNRELEASED: https://github.com/Qiskit/qiskit-ibmq-provider/compare/104d524...HEAD

.. _Keep a Changelog: http://keepachangelog.com/en/1.0.0/