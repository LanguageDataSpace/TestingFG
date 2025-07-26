This folder contains a set of **sample files** for assets, policies and offers that are compliant with the LanguageDCAT-AP model v0.9.1 and can serve as templates for testing import of batch metadata.

**IMPORTANT NOTES**

- To be valid, the files for assets and offers contain the property "dcat:downloadURL" with a fake location. None of these datasets can be negotiated and transferred. 
- The LDS connector does not accept duplicate metadata files. If you want to test the import properties, please copy the files, change the title (dct:title),  identifier (adms:identifier) and, in the case of policies, the link to the legal text (cc:legalcode) before attempting to import them.
