RabbitMQ Autocluster
====================
An RabbitMQ plugin that clusters nodes automatically using `Consul <https://consul.io>`_,
`etcd2 <https://github.com/coreos/etcd>`_, or DNS for service discovery.

.. image:: https://img.shields.io/travis/aweber/rabbitmq-autocluster.svg
    :target: https://travis-ci.org/aweber/rabbitmq-autocluster
.. image:: https://img.shields.io/github/release/aweber/rabbitmq-autocluster.svg
    :target: https://github.com/aweber/rabbitmq-autocluster/releases

Download
--------
Downloads of autocluster can be found on the
`GitHub Releases <https://github.com/aweber/rabbitmq-autocluster/releases>`_ page.
Check for version compatibility in the release notes.

Installation
------------
Place the plugin in the RabbitMQ plugins directory. To enable, run ``rabbitmq-plugins enable autocluster``.

Configuration
-------------
Configuration for the plugin can be set in two places: operating system environment variables
or the ``rabbitmq.config`` file under the ``autocluster`` stanza.

 - `General Settings <https://github.com/AWeber/rabbitmq-autocluster/wiki/General-Settings>`_
 - `Consul <https://github.com/AWeber/rabbitmq-autocluster/wiki/Consul-Configuration>`_
 - `DNS <https://github.com/AWeber/rabbitmq-autocluster/wiki/DNS-Configuration>`_
 - EC2
 - `etcd <https://github.com/AWeber/rabbitmq-autocluster/wiki/etc-Configuration>`_

Building
--------
See `Development Environment <https://github.com/AWeber/rabbitmq-autocluster/wiki/Development-Environment>`_.
