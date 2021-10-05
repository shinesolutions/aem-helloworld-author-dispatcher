[![Build Status](https://github.com/shinesolutions/aem-helloworld-author-dispatcher/workflows/CI/badge.svg)](https://github.com/shinesolutions/aem-helloworld-author-dispatcher/actions?query=workflow%3ACI)

# AEM Hello World Author-Dispatcher

This is an example AEM Hello World artifact that will be deployed to an AEM Author-Dispatcher instance.

This artifact contains:
* [Apache configuration template(s)](https://httpd.apache.org/docs/2.4/configuring.html) in `apache-conf-templates` directory
* [AEM Dispatcher configuration template(s)](https://docs.adobe.com/docs/en/dispatcher/disp-config.html) in `dispatcher-conf-templates` directory

Template files are written in [Embedded Puppet template syntax](https://docs.puppet.com/puppet/4.10/lang_template_epp.html).

Check out [Dispatcher Template Parameters](https://github.com/shinesolutions/puppet-aem-curator/blob/main/docs/dispatcher-template-parameters.md) for a list of available parameters to be used from EPP template files.

## Usage

To create artifact zip file:

```
make package
```

The artifact will be written at `stage/aem-helloworld-author-dispatcher-<version>.zip`
