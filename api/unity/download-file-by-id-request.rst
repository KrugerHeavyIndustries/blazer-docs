DownloadFileByIdRequest Class
==============================

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

.. dn:class:: DownloadFileByIdRequest

   A function object which downloads one file from B2.

   .. dn:method:: DownloadFileByIdRequest(BlazerClient client, string fileId, Stream stream)

      :param client: The configured Blazer client
      :param fileId: The unique identifier of the file version to download 
      :param stream: The file stream where the download will be written
