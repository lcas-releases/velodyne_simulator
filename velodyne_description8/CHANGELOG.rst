^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package velodyne_description
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

* Forked in LCAS to build a gazebo8-compatible binary. Package names had to be changed to prevent colisions



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
