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

Fedora 32 packages
==================

https://www.rpmfind.net/linux/fedora/linux/updates/32/Everything/x86_64/Packages/i/iputils-20190515-7.fc32.x86_64.rpm
https://www.rpmfind.net/linux/fedora/linux/updates/32/Everything/x86_64/Packages/s/strace-5.7.0.6.7ab6-1.fc32.x86_64.rpm
https://www.rpmfind.net/linux/fedora/linux/updates/32/Everything/x86_64/Packages/i/iproute-5.6.0-1.fc32.x86_64.rpm
https://www.rpmfind.net/linux/fedora/linux/releases/32/Everything/x86_64/os/Packages/p/psmisc-23.3-3.fc32.x86_64.rpm
https://www.rpmfind.net/linux/fedora/linux/updates/32/Everything/x86_64/Packages/b/bind-utils-9.11.20-1.fc32.x86_64.rpm
https://www.rpmfind.net/linux/fedora/linux/releases/32/Everything/x86_64/os/Packages/s/socat-1.7.3.4-2.fc32.x86_64.rpm
