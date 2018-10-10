^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package velodyne_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* Forked in LCAS to build a gazebo8-compatible binary. Package names had to be changed to prevent colisions



1.1.5 (2018-10-10)
------------------
* Merge pull request `#4 <https://github.com/LCAS/velodyne_simulator/issues/4>`_ from gpdas/gazebo8
  some file still linked to velodyne_description instead of *8
* Some file links to velodyne_description replaced with corresponding ones in velodyne_description8
* Contributors: Marc Hanheide, gpdas

1.1.4 (2018-09-24)
------------------
* corrected offset
* Contributors: ILIAD user

1.1.3 (2018-09-22)
------------------

1.1.2 (2018-09-22)
------------------
* Merge pull request `#3 <https://github.com/LCAS/velodyne_simulator/issues/3>`_ from LCAS/gazebo-split
  Separated gazebo plugins in xacro model.
* Separated gazebo plugins in xacro model.
  tf names changed to conform to iliad.
* Revert "Update VLP-16.urdf.xacro"
  This reverts commit 0b4af58490a6220e6c22721441b0dfc31d99b201.
* Update VLP-16.urdf.xacro
  Changed declaration to match other branch's one. Now should be possible to use both indistinctively.
* Contributors: Manuel Fernandez-Carmona, Marc Hanheide, mfernandezcarmona@lincoln.ac.uk

1.1.1 (2018-07-17)
------------------
* Merge branch 'gazebo8' of https://github.com/LCAS/velodyne_simulator into gazebo8
* Contributors: mfernandezcarmona@lincoln.ac.uk

1.0.8 (2018-07-17)
------------------
* Maintainer email changed
* Package dependencies corrected
* Renamed files to avoid collisions with the original repos
* Contributors: mfernandezcarmona@lincoln.ac.uk

1.0.7 (2018-07-03)
------------------
* Added GPU support
* Updated inertia tensors for VLP-16 and HDL-32E to realistic values
* Removed unnecessary file extraction code in cmake
* Contributors: Kevin Hallenbeck, Max Schwarz

1.0.6 (2017-10-17)
------------------
* Use robotNamespace as prefix for PointCloud2 topic frame_id by default
* Contributors: Micho Radovnikovich

1.0.5 (2017-09-05)
------------------
* Increased minimum collision range to prevent self-clipping when in motion
* Added many URDF parameters, and set example sample count to reasonable values
* Launch rviz with gazebo
* Contributors: Kevin Hallenbeck

1.0.4 (2017-04-24)
------------------
* Updated package.xml format to version 2
* Contributors: Kevin Hallenbeck

1.0.3 (2016-08-13)
------------------
* Contributors: Kevin Hallenbeck

1.0.2 (2016-02-03)
------------------
* Moved M_PI property out of macro to support multiple instances
* Materials caused problems with more than one sensors. Removed.
* Added example urdf and gazebo
* Changed to DAE meshes
* Added meshes. Added HDL-32E.
* Start from block laser
* Contributors: Kevin Hallenbeck
