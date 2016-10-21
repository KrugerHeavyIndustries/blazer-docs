DownloadFileByNameRequest Class
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

.. dn:class:: DownloadFileByNameRequest

   Downloads one file when provided with a bucket name and a filename.

   .. dn:method:: DownloadFileByNameRequest(BlazerClient client, string bucketName, string remoteFileName, Stream fs)

      :param client: The configured Blazer client 
      :param bucketName: The name of the B2 bucket to download file from
      :param remoteFileName: The name of the file to download
      :param fs: The filestream to where downloaded file is written
