ListFileVersionsRequest Class
=============================

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

.. dn:class:: ListFileVersionsRequest

   Lists all the versions of all the files contained within a bucket.

    .. dn:method:: ListFileVersionsRequest(BlazerClient client, string bucketName, string startFileName, int maxFileCount)

       :param client: The configured Blazer client
       :param bucketName: The name of the bucket to list
       :param startFileName: The starting file name
       :param maxFileCount: The maximum number of files to list
