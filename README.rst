..
  This file is part of the k8s-gluster-heketi-ansible project,
  an ansible collection to install glusterfs and heketi into
  kubernetes to provide dynamic persistent volumes.

  (c) 2020 Andreas Florath, Deutsche Telekom AG

  By default all files of this project are licensed under the Apache-2.0
  license. For details see the file 'LICENSE' in the top directory.
  https://opensource.org/licenses/Apache-2.0

  SPDX-License-Identifier: Apache-2.0

k8s-gluster-heketi-ansible
++++++++++++++++++++++++++

Introduction
============

Installs glusterfs and heketi into kubernetes for dynamic persistent
volume handling.

Status
======

In development.

gluster role is ready to use.
heketi role is under heavy development and can not yet be used.

References
==========

* glusterfs: https://github.com/gluster/glusterfs
* heketi: https://github.com/heketi/heketi

Similar Projects
================

Some ideas and even source code it used from the following projects.
All the projects are also licensed under Apache 2.0 license.  When
source code is used it is marked as such.

* ansible-role-k8s-heketi-gluster
  https://github.com/manics/ansible-role-k8s-heketi-gluster
  This project followed a very similar approach as
  k8s-gluster-heketi-ansible. The problem is, that this is not longer
  maintained and does not support up to date heketi versions.
* gluster-kubernetes
  https://github.com/gluster/gluster-kubernetes
  This project provides (mostly) a shell script to install and
  configure heketi.
  The project is archived (read-only) and there is no active
  developemnt done.  The result is, that it does not work with current
  kubernetes versions.  Also IMHO the bash script needs some
  refactoring.


License
=======

By default all program files (source code + configuration) of this
project are licensed under the Apache-2.0 license. For details see the
file 'LICENSE' in the top directory.
https://opensource.org/licenses/Apache-2.0

