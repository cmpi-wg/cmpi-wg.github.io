CMPI pages repository
=====================

This Github project (cmpi-wg/cmpi-wg.github.io) is the place where the CMPI API
documentation generated from the CMPI header files is published.

CMPI stands for "Common Manageability Programming Interface" and is a C-language
API between a Management Broker (aka CIMOM) and Management Instrumentation (aka
Providers). CMPI supports the CIM and WBEM standards defined by
[DMTF](http://www.dmtf.org).

The CMPI Standard is maintained on the
[CMPI Working Group web space](https://wiki.opengroup.org/councils-wiki/doku.php?id=forums:enterprise_management:cmpi:start).

The CMPI header files for the CMPI Standard are maintained in the
[cmpi-wg/cmpi-headers project on Github](https://github.com/cmpi-wg/cmpi-headers).
The CMPI API documentation is generated and published to this project here
by creating a clone of the cmpi-headers project on your local system, building
the HTML files using doxygen in its work directory, and by committing the
generated HTML files into the cmpi-wg.github.io project, which causes
them to be published immediately on [http://cmpi-wg.github.io].
Details on how that is done, will be added later.

Requirements for your local system to do that:
- Being on a Linux system
- Doxygen v1.8.6 or higher
 
License
-------

See [LICENSE.md](LICENSE.md) (preliminary license)
