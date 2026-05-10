README.txt
==========

This README file provides an overview of the directory structure and instructions on how to compile and use the MetricCombVis plugin for MeshLab.

Directory Structure:
--------------------
The project directory contains the following subdirectories:

1. release/ - Contains the compiled release version of the plugin.
2. debug/ - Contains the compiled debug version of the plugin.
3. mesh_objects/ - Contains selected mesh files for testing the plugin.
4. source code/ - Contains the source code, CMake file, and a detailed README on how to compile the plugin from source.

Subdirectory: release/
----------------------
This directory contains the compiled release version of the plugin.

Files:
- metricCombVis.dll  - The compiled release version of the plugin binary.

Usage:
- To load this plugin into MeshLab, you can use the Plugin Info dialog or copy the plugin file to the MeshLab plugins directory.



Subdirectory: debug/
--------------------
This directory contains the compiled debug version of the  plugin.

Files:
- metricCombVis.dll  - The compiled debug version of the plugin binary.

Usage:
- This plugin is intended for use with debug versions of MeshLab when MeshLab is built from source.
- To load this plugin into MeshLab, you can use the Plugin Info dialog.



Subdirectory: mesh_objects/
---------------------------
This directory contains selected mesh files for testing the MetricCombVis plugin.

Usage:
- Use these sample files to test the functionality of the MetricCombVis plugin in MeshLab.




Subdirectory: filter_metricCombVis - source code/
-----------------------------------
This directory contains the source code, CMake configuration file, and detailed instructions on how to compile the MetricCombVis plugin from source.

Files:
- plugin.cpp - Source code file containing the implementation of the plugin.
- plugin.h - Header file containing declarations for the plugin.
- CMakeLists.txt - CMake configuration file used to build the plugin.
- README.txt - Instructions on how to compile the plugin from source.





Loading and Using the Plugin:
-----------------------------
You can load the MetricCombVis plugin into MeshLab using one of the following methods:

### Using the Plugin Info Dialog
1. Open MeshLab.
2. Navigate to `Help` -> `Plugin Info`.
3. In the Plugin Info dialog, click on the `Load Plugin` button.
4. Browse to the location of the compiled plugin file and select it.
5. The plugin should now be loaded into MeshLab, and you can start using it.

### Copying to the Plugins Directory
1. Locate the MeshLab plugins directory. This is typically located in the installation directory of MeshLab:
   - Windows: `C:\Program Files\MeshLab\plugins`
2. Copy the compiled plugin file to the plugins directory.
3. Restart MeshLab.
4. The plugin should now be available in the MeshLab interface, and you can start using it.



Using the MetricCombVis Plugin:
---------------------------------------
The MetricCombVis plugin adds new functionalities under the "Filters" -> "Quality Measurement" menu.

- To use the visualization feature:
     1. Load a 3D model file by navigating to `File` -> `Import Mesh` and selecting one of the provided sample files (e.g., `bunny-original.ply`).
     2. Go to `Filters` -> `Quality Measurement` -> `Master's Thesis: Vertex quality visualization`.
     3. The plugin will process the loaded 3D model and display the desire visualization.


