.. _classwellfired_peek_generator_platformtools_sceneprocessor:

SceneProcessor
===============

**Namespace:** :ref:`WellFired.Peek.Generator<namespacewellfired_peek_generator>`

**Implements:** :ref:`WellFired.Peek.Generator.PlatformTools.ISceneProcessor<interfacewellfired_peek_generator_platformtools_isceneprocessor>`


Description
------------



Properties
-----------

+---------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+
|List< :ref:`IScene<interfacewellfired_peek_model_assets_iscene>` >   |:ref:`Scenes<classwellfired_peek_generator_platformtools_sceneprocessor_1a5577678471a0119624d1e8b9c349762b>` **{** get; set; **}**   |
+---------------------------------------------------------------------+-------------------------------------------------------------------------------------------------------------------------------------+

Public Methods
---------------

+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|             |:ref:`SceneProcessor<classwellfired_peek_generator_platformtools_sceneprocessor_1a61ee6edb71cf5ac667c4832238a6c0a9>` **(** :ref:`IFileAnalyzer<interfacewellfired_peek_generator_buildreportgeneration_utils_ifileanalyzer>` fileAnalyzer, :ref:`IAssetDatabase<interfacewellfired_peek_generator_platformtools_iassetdatabase>` assetDatabase **)**   |
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|string[]     |:ref:`GetPrefabDependencies<classwellfired_peek_generator_platformtools_sceneprocessor_1a6002d45b155db74d2790578b093f73d1>` **(** string scenePath **)**                                                                                                                                                                                               |
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+
|void         |:ref:`Process<classwellfired_peek_generator_platformtools_sceneprocessor_1a637694e2a644822e88ce387c96bf539b>` **(** string scenePath **)**                                                                                                                                                                                                             |
+-------------+-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------+

Breakdown
----------

.. _classwellfired_peek_generator_platformtools_sceneprocessor_1a5577678471a0119624d1e8b9c349762b:

- List< :ref:`IScene<interfacewellfired_peek_model_assets_iscene>` > **Scenes** **{** get; set; **}**

.. _classwellfired_peek_generator_platformtools_sceneprocessor_1a61ee6edb71cf5ac667c4832238a6c0a9:

-  **SceneProcessor** **(** :ref:`IFileAnalyzer<interfacewellfired_peek_generator_buildreportgeneration_utils_ifileanalyzer>` fileAnalyzer, :ref:`IAssetDatabase<interfacewellfired_peek_generator_platformtools_iassetdatabase>` assetDatabase **)**

.. _classwellfired_peek_generator_platformtools_sceneprocessor_1a6002d45b155db74d2790578b093f73d1:

- string[] **GetPrefabDependencies** **(** string scenePath **)**

.. _classwellfired_peek_generator_platformtools_sceneprocessor_1a637694e2a644822e88ce387c96bf539b:

- void **Process** **(** string scenePath **)**

