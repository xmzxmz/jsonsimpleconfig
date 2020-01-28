![Logo JSC](logo/logo-128.png)

JSON Simple Config [JSC]
========================

The JSC file format is an informal standard for configuration files.

JSC paradigms
-------------

1. Any JSON file can be converted to JSC format.
2. Any error at the config file is not blocking the whole configuration but only excludes section where error occurs.
3. We allow both block and line comments. 
4. Easy to read and write by humans and easy to parse and generate for machine (using existing JSON parsers).
5. Hierarchical config - cascade loading with config hierarchy
