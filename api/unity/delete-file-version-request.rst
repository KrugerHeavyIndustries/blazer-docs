DeleteFileVersionRequest Class
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

.. dn:class:: DeleteFileVersionRequest

   A function object that deletes a file version identfied by filename and unique file identifier 
   
   .. dn:method:: DeleteFileVersionRequest(BlazerClient client, string fileName, string fileId)

      :param client: The configured Blazer client
      :param fileName: The name of the file to delete
      :param fileId: The unique identifier of the file version to delete

