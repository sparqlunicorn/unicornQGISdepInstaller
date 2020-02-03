# unicornQGISdepInstaller
Dependency Installers for SPARQL Unicorn QGIS Plugin

This repository contains Windows installers which install Python dependencies for the SPARQL Unicorn QGIS Plugin.
Dependencies need to be installed in the following filepath:
C:\$PROGRAMS\ $QGISFOLDER\apps\ $PYTHONFOLDER\Lib\site-packages\
whereas 
* $PROGRAMS points to the Program Files folder in Windows
* $QGISFOLDER points to the folder in which QGIS is installed e.g. QGIS 3.10
* $PYTHONFOLDER points to the folder of the Python instance delivered with QGIS e.g. Python37

We provide installers for different versions of QGIS beginning with QGIS 3.10

The following Python dependencies need to be installed:

* [https://rdflib.github.io/sparqlwrapper/](SPARQLWrapper)
* [https://github.com/RDFLib/rdflib](rdflib) (modified version provided by us)
* [https://github.com/gweis/isodate](isodate)

To install dependencies on Linux refer to the following steps:

Install the SPARQLWrapper dependency using pip: 
* pip install SPARQLWrapper



