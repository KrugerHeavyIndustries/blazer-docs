ListFileNamesRequest Class
==========================

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

.. dn:class:: ListFileNamesRequest

   Lists the names of all files in a bucket, optionally starting at a given name.

   This function object returns at most 1000 files name, but it can be used repeatedly to scan through all the file names in a bucket. Each time you call, it returns a "nextFileName" that can be used as a startingi point for the next call.

   .. dn:property:: Files

      :rtype: `List<File>`

   .. dn:method::: ListFileNameRequest(BlazerClient client, string bucketName, string startFileName, int maxFileCount)

      :param client: The configured Blazer client
      :param bucketName: The name of the bucket to list
      :param startFileName: The starting file name
      :param maxFileCount: The maximum number of files to list
