Hacking
+++++++

Ansible Collection
==================

Be sure to use ansible 2.9 or higher!

To build the collection locally use:

.. code:: bash

   ansible-galaxy collection build

To install it from the local tar ball, set the collections path and
execute:
(You might want to adapt the `ANSIBLE_COLLECTIONS_PATHS` to also
respect collections installed elsewhere.)

.. code:: bash

   export ANSIBLE_COLLECTIONS_PATHS=${PWD}/collections
   ansible-galaxy collection install <path_to_tar> -p ./collections
