.. The contents of this file may be included in multiple topics (using the includes directive).
.. The contents of this file should be modified in a way that preserves its ability to appear in multiple topics.

This resource has the following properties:
   
``easy_install_binary``
   **Ruby Type:** String

   The location of the |python easy_install| binary.
   
``ignore_failure``
   **Ruby Types:** TrueClass, FalseClass

   |ignore_failure| Default value: ``false``.
   
``module_name``
   **Ruby Type:** String

   The name of the module.
   
``notifies``
   **Ruby Type:** Symbol, 'Chef::Resource[String]'

   |notifies|

   .. include:: ../../includes_resources_common/includes_resources_common_notifications_syntax_notifies.rst

   .. include:: ../../includes_resources_common/includes_resources_common_notifications_timers.rst
   
``options``
   **Ruby Type:** String

   |command options|
   
``package_name``
   **Ruby Types:** String, Array

   |name package| |resource_block_default| |see syntax|
   
``provider``
   **Ruby Type:** Chef Class

   Optional. |provider resource_parameter| |see providers|
   
``python_binary``
   **Ruby Type:** String

   The location of the |python| binary.
   
``retries``
   **Ruby Type:** Integer

   |retries| Default value: ``0``.
   
``retry_delay``
   **Ruby Type:** Integer

   |retry_delay| Default value: ``2``.
   
``subscribes``
   **Ruby Type:** Symbol, 'Chef::Resource[String]'

   |subscribes|

   .. include:: ../../includes_resources_common/includes_resources_common_notifications_syntax_subscribes.rst

   |subscribes timers|
   
``source``
   **Ruby Type:** String

   Optional. |source resource package|
   
``timeout``
   **Ruby Types:** String, Integer

   |timeout|
   
``version``
   **Ruby Types:** String, Array

   |version package|
