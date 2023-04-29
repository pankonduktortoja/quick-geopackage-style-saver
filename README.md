# quick-geopackage-style-saver
This is a plugin used to improve quality of work while handling geopackages in QGIS.
It will automatically save your layer's style into existing geopackage with just one click on the docked widget.
There is also an option to save styles for all the layers opened in the project, assuming that they are vector ones.
The script will work with multiple geopackages used within a single project, and also has no issues while geopackage gets disconnected from the database browser. The script is made in a way it tracks back path to the layer origin, so there is no need to have the geopackage connected.

The purpose of plugin is to avoid unnecessary manual work, especially while working with large databases.
The code is pretty plain and simple, but if you encounter any issues please let me know via github.