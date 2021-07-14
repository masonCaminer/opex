.. _topics-supervisor说明:

====================
supervisor说明
====================

.. note::

    用于多进程形式启动服务，放在生产上用，也可以本地用

| 说明

.. code-block:: shell

    supervisord -c supervisor_local.conf //本地
    supervisord -c supervisor.conf //生产
