Blazer Unity API
================

While most of the Blazer functionality is implemented within the Blazer Base API the Blazer Unity API provides functionality more idiomatic of Unity.

General Pattern of Use
----------------------

The important operations of the Blazer Unity API are implemented as Yieldable classes. The classes listed below are intended to be used by Unity co-routines. As such the typical pattern follows construction of a class, passing in relevent arguments to the constructor then yielding the object instance within a Unity co-routine and then a yield. After yield any expected results should be available on properties of the yielded instance.

.. sourcecode:: csharp

    BlazerClient client = new BlazerClient('<ACCOUNT_ID>', '<APPLICATION_KEY>');

    IEnumerator MyUnityCoroutine() {
       var request = new ListBucketsRequest(client);
       yield return request;
       var buckets = request.Buckets;
    }

Namespace
    :dn:ns:`Blazer.Unity`
Assembly
    * Blazer.Unity 

Classes
-------
.. toctree::
    blazer-request.rst
    create-bucket-request.rst
    delete-bucket-request.rst
    delete-file-version-request.rst
    download-file-by-id-request.rst
    download-file-by-name-request.rst
    get-file-info-request.rst
    hide-file-request.rst
    list-buckets-request.rst
    list-file-names-request.rst
    list-file-versions-request.rst
    update-bucket-request.rst
    upload-file-request.rst
