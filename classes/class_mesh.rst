.. Generated automatically by doc/tools/makerst.py in Godot's source tree.
.. DO NOT EDIT THIS FILE, but the doc/base/classes.xml source instead.

.. _class_Mesh:

Mesh
====

**Inherits:** :ref:`Resource<class_resource>` **<** :ref:`Reference<class_reference>` **<** :ref:`Object<class_object>`

**Inherited By:** :ref:`ArrayMesh<class_arraymesh>`, :ref:`PrimitiveMesh<class_primitivemesh>`

**Category:** Core

Brief Description
-----------------

A :ref:`Resource<class_resource>` that contains vertex-array based geometry.

Member Functions
----------------

+--------------------------------------------------+-------------------------------------------------------------------------------------------------------+
| :ref:`Shape<class_shape>`                        | :ref:`create_convex_shape<class_Mesh_create_convex_shape>`  **(** **)** const                         |
+--------------------------------------------------+-------------------------------------------------------------------------------------------------------+
| :ref:`ArrayMesh<class_arraymesh>`                | :ref:`create_outline<class_Mesh_create_outline>`  **(** :ref:`float<class_float>` margin  **)** const |
+--------------------------------------------------+-------------------------------------------------------------------------------------------------------+
| :ref:`Shape<class_shape>`                        | :ref:`create_trimesh_shape<class_Mesh_create_trimesh_shape>`  **(** **)** const                       |
+--------------------------------------------------+-------------------------------------------------------------------------------------------------------+
| :ref:`TriangleMesh<class_trianglemesh>`          | :ref:`generate_triangle_mesh<class_Mesh_generate_triangle_mesh>`  **(** **)** const                   |
+--------------------------------------------------+-------------------------------------------------------------------------------------------------------+
| :ref:`PoolVector3Array<class_poolvector3array>`  | :ref:`get_faces<class_Mesh_get_faces>`  **(** **)** const                                             |
+--------------------------------------------------+-------------------------------------------------------------------------------------------------------+

Description
-----------

Mesh is a type of :ref:`Resource<class_resource>` that contains vertex-array based geometry, divided in *surfaces*. Each surface contains a completely separate array and a material used to draw it. Design wise, a mesh with multiple surfaces is preferred to a single surface, because objects created in 3D editing software commonly contain multiple materials.

Member Function Description
---------------------------

.. _class_Mesh_create_convex_shape:

- :ref:`Shape<class_shape>`  **create_convex_shape**  **(** **)** const

.. _class_Mesh_create_outline:

- :ref:`ArrayMesh<class_arraymesh>`  **create_outline**  **(** :ref:`float<class_float>` margin  **)** const

.. _class_Mesh_create_trimesh_shape:

- :ref:`Shape<class_shape>`  **create_trimesh_shape**  **(** **)** const

.. _class_Mesh_generate_triangle_mesh:

- :ref:`TriangleMesh<class_trianglemesh>`  **generate_triangle_mesh**  **(** **)** const

.. _class_Mesh_get_faces:

- :ref:`PoolVector3Array<class_poolvector3array>`  **get_faces**  **(** **)** const


