API Support
===========

Supported S3 API commands for Zenko are detailed here.

.. tabularcolumns:: X{0.40\textwidth}X{0.20\textwidth}X{0.20\textwidth}
.. table::
 
   +-----------------------------------+-------------------+------------+
   | Operation Name                    | Operation Type    | Available? |
   +===================================+===================+============+
   | GET Service                       | Bucket            | —          |
   +-----------------------------------+-------------------+------------+
   | :ref:`DELETE Bucket`              | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Bucket Versioning`      | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Bucket Location`        | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Bucket (List Objects)`  | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Bucket Object Versions` | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`Head Bucket`                | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Bucket`                 | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Bucket Versioning`      | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Bucket ACL`             | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Bucket ACL`             | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`List Multipart Uploads`     | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Bucket Website`         | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Bucket Website`         | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`DELETE Bucket Website`      | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Bucket CORS`            | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Bucket CORS`            | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`DELETE Bucket CORS`         | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`DELETE Bucket Lifecycle`    | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`DELETE Bucket Replication`  | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`DELETE Bucket Policy`       | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | DELETE Bucket Tagging             | Bucket            | —          |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Bucket Lifecycle`       | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Bucket Replication`     | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Bucket Policy`          | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | GET Bucket Logging                | Bucket            | —          |
   +-----------------------------------+-------------------+------------+
   | GET Bucket Notification           | Bucket            | —          |
   +-----------------------------------+-------------------+------------+
   | GET Bucket Tagging                | Bucket            | —          |
   +-----------------------------------+-------------------+------------+
   | GET Bucket RequestPayment         | Bucket            | —          |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Bucket Lifecycle`       | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Bucket Replication`     | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Bucket Policy`          | Bucket            | Yes        |
   +-----------------------------------+-------------------+------------+
   | PUT Bucket Logging                | Bucket            | —          |
   +-----------------------------------+-------------------+------------+
   | PUT Bucket Notification           | Bucket            | —          |
   +-----------------------------------+-------------------+------------+
   | PUT Bucket Tagging                | Bucket            | —          |
   +-----------------------------------+-------------------+------------+
   | PUT Bucket RequestPayment         | Bucket            | —          |
   +-----------------------------------+-------------------+------------+
   | :ref:`DELETE Object`              | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`DELETE Object Tagging`      | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`Multi-Object Delete`        | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Object`                 | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Object Tagging`         | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`GET Object ACL`             | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`HEAD Object`                | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | GET Object Torrent                | Object            | —          |
   +-----------------------------------+-------------------+------------+
   | OPTIONS Object                    | Object            | —          |
   +-----------------------------------+-------------------+------------+
   | POST Object                       | Object            | —          |
   +-----------------------------------+-------------------+------------+
   | POST Object Restore               | Object            | —          |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Object`                 | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Object Tagging`         | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Object ACL`             | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`PUT Object - Copy`          | Object            | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`Initiate Multipart Upload`  | Multipart Upload  | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`Upload Part`                | Multipart Upload  | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`Upload Part - copy`         | Multipart Upload  | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`Complete Multipart Upload`  | Multipart Upload  | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`Abort Multipart Upload`     | Multipart Upload  | Yes        |
   +-----------------------------------+-------------------+------------+
   | :ref:`List Parts`                 | Multipart Upload  | Yes        |
   +-----------------------------------+-------------------+------------+
   | **Special Notes**                                                  |
   +-----------------------------------+-------------------+------------+
   | Transfer-stream-encoding for      |                   | Yes        |
   | object PUT with v4 AUTH           |                   |            |
   +-----------------------------------+-------------------+------------+
