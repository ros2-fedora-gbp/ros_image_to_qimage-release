^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package ros_image_to_qimage
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.4.1 (2022-09-29)
------------------
* Change #include cv_bridge.h to cv_bridge.hpp in ros_image_to_qimage.hpp (`#27 <https://github.com/ros-sports/ros_image_to_qimage/issues/27>`_, `#28 <https://github.com/ros-sports/ros_image_to_qimage/issues/28>`_)
* Change python_qt_binding from exec_depend to depend, because it is being used in CMakeLists.txt. (`#25 <https://github.com/ros-sports/ros_image_to_qimage/issues/25>`_)
* Contributors: Kenji Brameld

0.4.0 (2022-09-26)
------------------
* Ensure bgr8 gets converted to rgb8 (`#21 <https://github.com/ros-sports/ros_image_to_qimage/issues/21>`_)
* Add functionality to convert mono colors too (`#18 <https://github.com/ros-sports/ros_image_to_qimage/issues/18>`_)
* Add tests for cpp (`#13 <https://github.com/ros-sports/ros_image_to_qimage/issues/13>`_)
* Add python API (`#5 <https://github.com/ros-sports/ros_image_to_qimage/issues/5>`_)
* Fix README.md (`#4 <https://github.com/ros-sports/ros_image_to_qimage/issues/4>`_)
* Contributors: Kenji Brameld

0.3.0 (2022-06-15)
------------------
* update readme
* update ci
* Contributors: Kenji Brameld

0.0.2 (2022-01-07)
------------------
* fill package.xml with correct description and license tag
* Contributors: ijnek

0.0.1 (2022-01-06)
------------------
* implemented ros_image_to_qimage package
* Contributors: Kenji Brameld, ijnek
