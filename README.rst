=========================================
rbc-tools - Command line tools for managing RedBridge Cloud
=========================================

rbc-tools are command line tools for managing RedBridge Cloud.

Using rbc-tools you can manage instances, networks and othe compute resources in RBC.

The tools are tested on MacOS and Linux only at the moment, but should also work on Windows in a cygwin environment.

THe tools are in a early beta stage so please report any bugs to support@redbridge.se or as issues on github: 

To start using the client:
1. Register for an account on `RedBridge Portal <https://portal.redbridge.se/account/signup/>`_
2. Get your access key and secret key from your ccount page in the portal.
3. Create a ~/.rbc/rbc.cfg file (in a terminal)

Usage::

    import molnctrl
    csapi = molnctrl.Initialize("apikey", "api_secret", api_host='cloud.fqdn')
    accounts = csapi.list_accounts()

Changelog
=========
* 0.5.0 2014-07-31 Support for rbc-tools 0.1, the command line client for managing RedBridge Cloud.

* 0.4.10 2014-06-16 Added more Cloudstack object classes

* 0.4.9 2014-06-12 Added more Cloudstack object classes

* 0.4.8 2014-06-06 Packaging fixes

* 0.4.2 2014-06-06 Packaging fixes

* 0.4.1 2014-06-06 Fix a few bugs in the package includes and install_requires

* 0.4.0 2014-06-06 Initial release
