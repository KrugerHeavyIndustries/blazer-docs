HideFileRequest Class
=====================

Namespace
   :dn:ns:`Blazer.Unity`
Assembly
   * Blazer.Unity

----

.. contents::
    :local:

Inheritance Hierarchy
---------------------

* :dn:class:`Blazer.Unity.BlazerRequest`

Constructor
-----------

.. dn:class:: HideFileRequest

   Hides a file so that downloading the file by name will not find the file, but the previous versions of the file are still stored.

   .. dn:method:: HideFileRequest(BlazerClient client, string bucketName, string fileName)

      :param client: The configured Blazer client
      :param bucketName: The name of the bucket the target file resides
      :param fileName: The name of the file to hide
