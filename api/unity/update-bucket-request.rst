UpdateBucketRequest Class
=========================

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

.. dn:class:: UpdateBucketRequest

   Update an existing bucket. More specifically modifies the bucketType of an existing bucket. Can be used to allow everyone to download the contents of the bucket without providing any authorization, or to prevent anyone from downloading the contents of the bucket without a known authorization.

   .. dn:method:: UpdateBucketRequest(BlazerClient client, string bucketName, BucketType bucketType)

      :param client: The configured Blazer client 
      :param bucketName: The name of the bucket to update
      :param bucketType: The flag you want to assign to the bucket 
