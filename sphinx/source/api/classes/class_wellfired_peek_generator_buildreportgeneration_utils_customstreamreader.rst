.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader:

CustomStreamReader
===================

**Namespace:** :ref:`WellFired.Peek.Generator.BuildReportGeneration<namespacewellfired_peek_generator_buildreportgeneration>`

Description
------------



public-static-attrib
---------------------

+-----------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------+
|new readonly :ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader>`   |:ref:`Null<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1aaacfa4e283280906523d31021122417c>`    |
+-----------------------------------------------------------------------------------------------------------------------+--------------------------------------------------------------------------------------------------------------------------------+

package-attrib
---------------

+-------------+---------------------------------------------------------------------------------------------------------------------------------------------+
|const int    |:ref:`DefaultBufferSize<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a26f1d16eaee311baa520c706243f09bc>`    |
+-------------+---------------------------------------------------------------------------------------------------------------------------------------------+

Properties
-----------

+-------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
|int          |:ref:`LineLength<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ab74d1873fb07a877a10e790a3aa4f834>` **{** get; set; **}**        |
+-------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
|int          |:ref:`BytesRead<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a4dfc12cca16bf4db41c28f59862c2f98>` **{** get; set; **}**         |
+-------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
|Encoding     |:ref:`CurrentEncoding<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1af1a51884a13ea19b60443a5bfd3c6172>` **{** get; set; **}**   |
+-------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+
|Stream       |:ref:`BaseStream<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a6b2ef25279a0caeb38436df7010da962>` **{** get; set; **}**        |
+-------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------+

package-func
-------------

+-------------+----------------------------------------------------------------------------------------------------------------------------------------------------------+
|             |:ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ae6135013f55cb1e41fe036c6b696ee88>` **(**  **)**   |
+-------------+----------------------------------------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|                  |:ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ad6680c3cbb3799629c494880a0e8391a>` **(** String path, Encoding encoding, bool detectEncodingFromByteOrderMarks, int bufferSize **)**                                |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|                  |:ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a6c870c16ea5794bd966a7fab1556b5ec>` **(** Stream stream **)**                                                                                                        |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|                  |:ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ad202746a1601cb161f32e4c342ba7006>` **(** Stream stream, Encoding encoding, bool detectEncodingFromByteOrderMarks = true, int bufferSize = DefaultBufferSize **)**   |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|                  |:ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1af62a66a6c56f507aa5771971b108e2e6>` **(** String path **)**                                                                                                          |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|                  |:ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a2aa3308b9cd950ed6aa33882dfefa466>` **(** String path, bool detectEncodingFromByteOrderMarks **)**                                                                   |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|                  |:ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1aad5a89fe12951285b2b1c9cd02fb1b0e>` **(** String path, Encoding encoding **)**                                                                                       |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|                  |:ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a6c6dacd079ea82f84e81c4a8160df2d1>` **(** String path, Encoding encoding, bool detectEncodingFromByteOrderMarks **)**                                                |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|                  |:ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1aef8f6990bc523367f167f44ecaaa77e0>` **(** Stream stream, bool detectEncodingFromByteOrderMarks **)**                                                                 |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|override void     |:ref:`Close<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ae761d98c22dcadbb7262d0544073c507>` **(**  **)**                                                                                                                                  |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|void              |:ref:`DiscardBufferedData<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a4bac451ba04c2552d9a6c4e93308c88b>` **(**  **)**                                                                                                                    |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|override int      |:ref:`Peek<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ae3861d4074cad3d07ee0b7ee6edea925>` **(**  **)**                                                                                                                                   |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|override int      |:ref:`Read<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1adc90aa57609aa24efb638aa2e2c50775>` **(**  **)**                                                                                                                                   |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|override int      |:ref:`Read<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a82d6c75c62eb748d2edc3aefdc73e0ab>` **(** char[] buffer, int index, int count **)**                                                                                                |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|override String   |:ref:`ReadToEnd<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ab2cb2c06260c1dda2a323ceaabf6ed4f>` **(**  **)**                                                                                                                              |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|override String   |:ref:`ReadLine<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a08f3367c531cb509929fc2e0e7b84e17>` **(**  **)**                                                                                                                               |
+------------------+----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

protected-func
---------------

+----------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+
|override void   |:ref:`Dispose<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a4d8914edf73c69e2290f0134ada6af60>` **(** bool disposing **)**   |
+----------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1aaacfa4e283280906523d31021122417c:

- new readonly :ref:`CustomStreamReader<classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader>` **Null** 

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a26f1d16eaee311baa520c706243f09bc:

- const int **DefaultBufferSize** 

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ab74d1873fb07a877a10e790a3aa4f834:

- int **LineLength** **{** get; set; **}**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a4dfc12cca16bf4db41c28f59862c2f98:

- int **BytesRead** **{** get; set; **}**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1af1a51884a13ea19b60443a5bfd3c6172:

- Encoding **CurrentEncoding** **{** get; set; **}**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a6b2ef25279a0caeb38436df7010da962:

- Stream **BaseStream** **{** get; set; **}**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ae6135013f55cb1e41fe036c6b696ee88:

-  **CustomStreamReader** **(**  **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1aef8f6990bc523367f167f44ecaaa77e0:

-  **CustomStreamReader** **(** Stream stream, bool detectEncodingFromByteOrderMarks **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ad6680c3cbb3799629c494880a0e8391a:

-  **CustomStreamReader** **(** String path, Encoding encoding, bool detectEncodingFromByteOrderMarks, int bufferSize **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ad202746a1601cb161f32e4c342ba7006:

-  **CustomStreamReader** **(** Stream stream, Encoding encoding, bool detectEncodingFromByteOrderMarks = true, int bufferSize = DefaultBufferSize **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1af62a66a6c56f507aa5771971b108e2e6:

-  **CustomStreamReader** **(** String path **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a2aa3308b9cd950ed6aa33882dfefa466:

-  **CustomStreamReader** **(** String path, bool detectEncodingFromByteOrderMarks **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1aad5a89fe12951285b2b1c9cd02fb1b0e:

-  **CustomStreamReader** **(** String path, Encoding encoding **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a6c6dacd079ea82f84e81c4a8160df2d1:

-  **CustomStreamReader** **(** String path, Encoding encoding, bool detectEncodingFromByteOrderMarks **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a6c870c16ea5794bd966a7fab1556b5ec:

-  **CustomStreamReader** **(** Stream stream **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ae761d98c22dcadbb7262d0544073c507:

- override void **Close** **(**  **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a4bac451ba04c2552d9a6c4e93308c88b:

- void **DiscardBufferedData** **(**  **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ae3861d4074cad3d07ee0b7ee6edea925:

- override int **Peek** **(**  **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1adc90aa57609aa24efb638aa2e2c50775:

- override int **Read** **(**  **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a82d6c75c62eb748d2edc3aefdc73e0ab:

- override int **Read** **(** char[] buffer, int index, int count **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1ab2cb2c06260c1dda2a323ceaabf6ed4f:

- override String **ReadToEnd** **(**  **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a08f3367c531cb509929fc2e0e7b84e17:

- override String **ReadLine** **(**  **)**

.. _classwellfired_peek_generator_buildreportgeneration_utils_customstreamreader_1a4d8914edf73c69e2290f0134ada6af60:

- override void **Dispose** **(** bool disposing **)**

