..
    Warning: Do not edit this file. It is automatically generated from the
    software project's code and your changes will be overwritten.

    The tool to generate this file lives in openstack-doc-tools repository.

    Please make any changes needed in the code, then run the
    autogenerate-config-doc tool from the openstack-doc-tools repository, or
    ask for help on the documentation mailing list, IRC channel or meeting.

.. _nova-matchmaker_redis:

.. list-table:: Description of matchmaker_redis configuration options
   :header-rows: 1
   :class: config-ref-table

   * - Configuration option = Default value
     - Description

   * - ``host`` = ``127.0.0.1``

     - (String) Host to locate redis.

       - **Deprecated**

         Replaced by [DEFAULT]/transport_url

   * - ``port`` = ``6379``

     - (Port number) Use this port to connect to redis host.

       - **Deprecated**

         Replaced by [DEFAULT]/transport_url

   * - ``password`` =

     - (String) Password for Redis server (optional).

       - **Deprecated**

         Replaced by [DEFAULT]/transport_url

   * - ``sentinel_hosts`` =

     - (List) List of Redis Sentinel hosts (fault tolerance mode), e.g., [host:port, host1:port ... ]

       - **Deprecated**

         Replaced by [DEFAULT]/transport_url

   * - ``sentinel_group_name`` = ``oslo-messaging-zeromq``

     - (String) Redis replica set name.

   * - ``wait_timeout`` = ``2000``

     - (Integer) Time in ms to wait between connection attempts.

   * - ``check_timeout`` = ``20000``

     - (Integer) Time in ms to wait before the transaction is killed.

   * - ``socket_timeout`` = ``10000``

     - (Integer) Timeout in ms on blocking socket operations.
