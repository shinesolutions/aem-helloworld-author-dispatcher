[![Build Status](https://img.shields.io/travis/shinesolutions/aem-helloworld-author-dispatcher.svg)](http://travis-ci.org/shinesolutions/aem-helloworld-author-dispatcher)

# AEM Hello World Author-Dispatcher

This is an example AEM Hello World artifact that will be deployed to an AEM Author-Dispatcher instance.

This artifact contains:
* [Apache configuration template(s)](https://httpd.apache.org/docs/2.4/configuring.html) in `apache-conf-templates` directory
* [AEM Dispatcher configuration template(s)](https://docs.adobe.com/docs/en/dispatcher/disp-config.html) in `dispatcher-conf-templates` directory

Template files are written in [Embedded Puppet template syntax](https://docs.puppet.com/puppet/4.10/lang_template_epp.html).

Check out [Dispatcher Template Parameters](https://github.com/shinesolutions/puppet-aem-curator/blob/master/docs/dispatcher-template-parameters.md) for a list of available parameters to be used from EPP template files.

## Usage

To create artifact zip file:

```
make package
```

The artifact will be written at `stage/aem-helloworld-author-dispatcher-<version>.zip`
