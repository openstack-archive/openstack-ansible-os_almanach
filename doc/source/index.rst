=================
Table of Contents
=================

.. toctree::
   :maxdepth: 2

   configure-ceilometer.rst

Default variables
~~~~~~~~~~~~~~~~~

.. literalinclude:: ../../defaults/main.yml
   :language: yaml
   :start-after: under the License.

Example playbook
~~~~~~~~~~~~~~~~

.. literalinclude:: ../../examples/playbook.yml
   :language: yaml

Tags
~~~~

This role supports two tags: ``ceilometer-install`` and
``ceilometer-config``. The ``ceilometer-install`` tag can be used to install
and upgrade. The ``ceilometer-config`` tag can be used to maintain the
configuration of the service.
