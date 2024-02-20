^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^
Changelog for package cob_fiducials
^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^^

0.1.1 (2024-02-20)
------------------
* Merge pull request `#8 <https://github.com/4am-robotics/cob_fiducials/issues/8>`_ from fmessmer/ci/gha
  migrate ci to gha
* migrate ci to gha
* remove kinetic jobs
* Merge pull request `#7 <https://github.com/4am-robotics/cob_fiducials/issues/7>`_ from Deleh/feature/diagnostics
  Add Heartbeat Diagnostics
* add heartbeat diagnostics
* clean spacing
* Merge pull request `#6 <https://github.com/4am-robotics/cob_fiducials/issues/6>`_ from fmessmer/fix_boost_deprecation
  fix boost deprecation
* fix boost deprecation
* Merge pull request `#5 <https://github.com/4am-robotics/cob_fiducials/issues/5>`_ from fmessmer/kevin_ipa
  debug log output
* debug log output
* update travis config
* Merge pull request `#3 <https://github.com/4am-robotics/cob_fiducials/issues/3>`_ from fmessmer/test_noetic
  test noetic
* fix opencv enums round 2
* removes deprecated dynamic exception specifications
* fixes opencv enum and constants
* Revert "fix opencv issues"
  This reverts commit bb4391c04f607eb5f1a71536dfd7632ff7a55385.
* fix opencv issues
* fix cv enums
* default pylint version check only
* Bump CMake version to avoid CMP0048 warning
* remove melodic job
* add noetic job
* remove upstream workspace
* Merge pull request `#1 <https://github.com/4am-robotics/cob_fiducials/issues/1>`_ from fmessmer/add_travis
  add travis
* fix pylint issues
* fix catkin_lint issues
* remove dependency pcl
* include cob_vision_utils/StdAfx only in non __LINUX\_\_
* add README
* add overlay for cob_vision_utils
* add .travis.yml
* add .gitignore
* Merge branch 'indigo_dev' of https://github.com/ipa-rmb/cob_object_perception into indigo_dev
* bugfix for faster reply on service call
* Merge branch 'indigo_dev' of github.com:ipa320/cob_object_perception into indigo_dev
* bugfixes for fiducials with sensor info msg and tf publishing
* Merge branch 'indigo_dev' of github.com:ipa320/cob_object_perception into indigo_dev
* bugfixes for fiducials (removed synchronizer for camera info, tf output for all detected tags)
* update to use non deprecated pluginlib macro
* cmake_modules and eigen cleanup
* updated opencv includes for kinetic
* Merge branch 'indigo_dev' of github.com:ipa320/cob_object_perception into indigo_dev
* buildbot required these changes to compile the cob_fiducials package
* added id of each marker to tf broadcasts
* Merge remote-tracking branch 'origin-rmb/indigo_dev' into merge_with_rmb
  Conflicts:
  cob_fiducials/package.xml
  cob_marker/package.xml
  cob_object_categorization/package.xml
  cob_object_detection_fake/package.xml
  cob_object_perception/package.xml
  cob_object_recording/package.xml
  cob_read_text/CMakeLists.txt
  cob_read_text/package.xml
  cob_surface_classification/CMakeLists.txt
  cob_surface_classification/package.xml
  cob_texture_categorization/package.xml
  libvlfeat/package.xml
  libzxing/package.xml
* package format 2 and finalize cob_fiducials
* corrected tag_0 pdf
* Merge branch 'indigo_dev' of github.com:ipa-rmb/cob_object_perception into indigo_dev
* added new pdfs for tags
* added passthrough varaint of Ensenso-IDS-Rack
* cleaning and conversion to package format 2
* added some recall/precision table in excel sheet
* little bugfixes
* Adapted precompiled header settings
* catkinizing
* bugfixes for indigo
* merge ipa-rmb groovy - jsf-indigo
* Adapted precompiled header filepath to ROS specs
* Adapted precompled header paths to be expressed relative to the metapackage and not above. Adapted Makefile to include new cpp files. Reduced include headers
* Moved definition of function to separate cpp file in order to reduce header file dependencies. Removed unnecessary headers and updated Visaul Studio project file
* Merge branch 'hydro_dev' of github.com:ipa-jsf/cob_object_perception into hydro_dev
* Tabifying files
* Cleanup of header files
* removed cob_leg_detection and moved it into cob_people_perception (starting with groovy_dev_catkin version, no groovy_version)
* Adapted install tags
* Added missing system dependecies to package.xml
* Added message and service depencies to targets in order to create correct build order
* catkinizing cob_read_text
* improved catkinizing by (a) adding missing tarball (b) reorganized cob_object_detection_fake to ROS python standard layout (c) fixed catkin_lint issues
* catkinizing
* fixed launchfile again
* fixed launchfile
* Removed multiple argument possibilities for cv::sqrt function call by explicit type cast
* merge with 320
* deleted seneka includes
* minor changes
* changed msgs
* added seneka_msgs
* changed header of marker array
* added seneka message for fiducial publisher
* added two triplets of pi tags to the vsd file
* tuning of piTagIni_3.xml compilation for robustness and number of long distance tags
* added 3 tags that are similar to (and therefore replacing) former 67, 69, 73 tags, but the new tags should have better visibility from far
* added new tags with big differences in their cross ratios
* working on pi markers that can be better distinguished -> cross-ratio analysis
* correction of the invalid codes, addition of a excel table to compute valid codes
* merge with 320
* little hack for simulation, deactivated on default
* added new tags to new ini.xml file
* Merge branch 'groovy_dev' of github.com:ipa320/cob_object_perception into 320-groovy_dev
* added more markers in vsd file
* aruco tested and fiducials.launch set to standard values
* changed marker description fpitag
* merge
* Added new pdfs for tags
* set FPITAG to '1'
* small changes
* added fast pitag .launch and .ini file
* modified CMakeLists and manifest
* renamed
* renamed
* cleaned common/files/fiducials/pi
* cleaned common/files/models
* cleaned common/files/models
* cleaned common/files/models
* cleaned common/include/cob_fiducials
* cleaned common/include
* cleaned common/src
* cleaned ros/launch
* fiducials.cpp restored to original
* cleaned src
* added seneka launch file
* updated FiducialModelPi.h
* added markers and ini for seneka project
* added new FiducialModelPi.cpp
* removed files
* removed files
* more deleted stuff
* deleted stuff
* Testing
* cleaned useless files
* Clean UP directory
* merged ipa320 into fast_pitag
* remove ROS_NOBUILD
* cob_fiducials with PITag
* publishing tf for marker (/marker)
* added dep
* fix bad habit
* merge
* Added feture to return only the requested obejct label
* Merge branch 'groovy_dev' of https://github.com/ipa-jsf-hm/cob_object_perception into groovy_dev
* Added bsh yaml file
* Merge branch 'groovy_dev' of https://github.com/ipa320/cob_object_perception into groovy_dev
* Added separate tf frames for each detected marker
* Merge branch 'groovy_dev' of https://github.com/ipa320/cob_object_perception into groovy_dev
* small changes to make it build
* Merge branch 'groovy_dev' of https://github.com/ipa-jsf-hm/cob_object_perception into groovy_dev
* merge
* Merge branch 'groovy_dev' of https://github.com/ipa320/cob_object_perception into groovy_dev
* merge
* New function for setting extrinsics to online switch cameras
* Merge branch 'groovy_dev-320' into groovy_dev
* Added files for 5 cm pi-tag
* Bugfix to enable rezised markers by just modifying the marker size in the xml file
* fixed fiducials unsubscribe bug while using service and subscribe
* Merge branch 'groovy_dev' of https://github.com/ipa320/cob_object_perception into groovy_dev
* BUGFIX. When havin a large resolution image of circles, then the circles create double contours (inner and outer ring). Those contours prevented the recognition of the pattern Problem fixed
* added new pi-tag pdf with sharpness measure
* Merge branch 'groovy_dev' of https://github.com/ipa320/cob_object_perception into groovy_dev
* fixed image namespace in launch file
* added the possibility for easy sharpness calibration
* cleaned up the code, added code comments, and added a ROS parameter for activating/deactivating the sharpness computation together with the marker detection
* calibrated the linear function of pixel_count and sharpness_score -> sharpness measure now working very well
* added code for another sharpness measure and log file recording
* code for sharpness measure finalized but measure not yet good enough
* working on sharpness measure
* added header information to all outgoing messages, fixed some performance bugs (double/triple work)
* added a verbosity_level parameter for screen outputs
* fixed fiducials bug that no headers are set in the outgoing DetectionArray message
* added communication functions
* some groovy adaptations
* added pdf with aruco fiducial
* Fixed solution paramteres
* bugfix
* Aruco and PI up and running
* Merge branch 'groovy_dev' of github.com:ipa320/cob_object_perception into groovy_dev
* Integration of new file structure for pi tag
* JSF: ArUco tag up and running
* JSF: Worked on Aruco marker integration
* Added Aruco pattern maker as Visio file
* JSF: Added implementation of ArUco marker
* fiducial port to groovy
* Merge branch 'electric_dev' of git://github.com/ipa-jsf/cob_object_perception into groovy_dev
* improved stability of marker
* added ROS_NOBUILD for packages not compiling yet under groovy
* Improved false positive rate by checking reprojection error
* Modified nothing
* JSF: Added pdf for single tags
* IPA-JSF: Modified windows files
* Added helper script
* Committed launch files
* Fiducials for ROS up and running
* ROS interface for fiducials up and running
* Worked on linux interface for fiducials
* Implemented ROS interface for fiducial recognition
* Restored linux compliance
* Improved fiducial recognition
* Significantly reduced false detection rate of pi fiducial and fixed some bugs for object modeling
* Worked on tag integration
* JSF: Worked on tag recognition
* Worked on tag integration for object modeling
* Merge branch 'master' of github.com:ipa-jsf/cob_object_perception
* Worked on tag recognition
* Worked on tag recognition for object modeling
* jsf
* Improved fiducial design
* Improved tag design
* Added new tags
* Modified include paths
* Initial commit. ROS wrappers will follow soon
* Added fiducials. They are distinct to cob_markers, as it is not possible to encode an arbitrary string with them
* Contributors: Denis Lehmann, Equanox, Felix Messmer, Hendrik Molter, Jan Fischer, Jiawei Yang, Marc Riedlinger, Richard Bormann, Student of Richard Bormann, Your Name, buildbot-squirrel, fmessmer, ipa-bnm, ipa-cmm-mn, ipa-fxm, ipa-jsf, kevin2@cob4-20, raw3, tsl
