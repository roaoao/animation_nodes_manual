Find Points In Radius
=====================

Description
-----------

This node finds the points that lie inside a sphere with a given center and radius in the input KD Tree.

.. image:: images/find_points_in_radius_node.png
   :width: 160pt

Inputs
------

- **KD Tree** - A KD tree that contain your points.
- **Radius** - The radius of the search sphere.
- **Vector** - A vector that represent the center of the search sphere.

Outputs
-------

- **Vectors** - The locations of the points that lies inside the sphere defined by the input vector and radius.
- **Distances** - The distances between the output points and the input point.
- **Index** - The indices of the nearest points to the input point in the list used to construct the KD tree.

Advanced Node Settings
----------------------

- N/A

Examples of Usage
-----------------

.. image:: gifs/find_points_in_radius_node_example.gif
