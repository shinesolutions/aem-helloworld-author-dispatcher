# AEM Hello World Author Dispatcher Config

## Content

This project includes the Apache Server configuration template, as well as the dispatcher configuration template.

Go to [AEM's dispatcher config page](https://docs.adobe.com/docs/en/dispatcher/disp-config.html) to learn more about it.

## Build

To build the aem-author-dispatcher-config package, just run: 

```
make package
```

This will create a stage folder which will contain a zip file with the following structure:

```
aem-author-dispatcher-config-{version number}
│   README.md
│   LICENCE    
│   Makefile
│
└───apache-conf-templates
│       httpd.conf.epp
│   
└───dispatcher-conf-templates
        dispatcher.conf.epp
        dispatcher.farms.any.epp
```

This package needs to be deployed on author-dispatcher instance.