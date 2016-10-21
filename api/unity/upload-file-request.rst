UploadFileRequest Class
=======================

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

.. dn:class:: UploadFileRequest

   Uploads one file to B2, returning its unique file identifier. Files smaller than 200MB are done in one piece. Files larger than 200MB are split into 100MB parts and uploaded separately.

   .. dn:method:: UploadFileRequest(BlazerClient client, string bucketName, string localFilePath, string remoteFileName, string contentType)

      :param client: The configured Blazer client 
      :param bucketName: The name of the bucket to upload to
      :param localFilePath: The path to upload file
      :param remoteFilePath: The name the file will receive in target bucket
      :param contentType: The mime type of the file

