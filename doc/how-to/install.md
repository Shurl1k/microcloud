.. _howto-install:

How to install MicroCloud
=========================

To install MicroCloud, install all required :ref:`snaps` on all machines that you want to include in your cluster.

To do so, enter the following commands on all machines::

  sudo snap install lxd --channel=5.21/stable --cohort="+"
  sudo snap install microceph --channel=quincy/stable --cohort="+"
  sudo snap install microovn --channel=22.03/stable --cohort="+"
  sudo snap install microcloud --channel=latest/stable --cohort="+"

.. note::
   Make sure to install the same version of the snaps on all machines.
   See :ref:`howto-snap` for more information.

   If you don't want to use MicroCloud's full functionality, you can install only some of the snaps.
   However, this is not recommended.
