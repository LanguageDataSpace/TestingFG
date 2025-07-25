This folder contains sample metadata files compliant the LanguageDCAT-AP metadata model v0.9.1.
The files can be used as an inspiration for testing the import feature of the LDS Connector.

Please keep in mind the following:
- To be valid, the files for assets and offers contain the property "dcat:downloadURL" with a fake location. None of these datasets can be negotiated and transferred.
- The LDS connector does not accept duplicate files. If you want to test the import functionality, please copy the files, change the names and/or identifiers before attempting to import them.
