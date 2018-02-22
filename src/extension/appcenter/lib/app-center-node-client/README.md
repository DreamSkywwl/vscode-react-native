# Introduction
AppCenter NodeJS client generated by AutoRest and swagger-tools.

# Getting Started
To install use local installation or npm package.

# Build and Test
No building required for this package.

# Contribute
DO NOT contribute to this repo because it contains automatically generated content.
Contribute to https://msmobilecenter.visualstudio.com/Mobile-Center/Build/_git/swagger-tools.

# How to use

1) Simple client usage

```
    import { AppCenterClient } from 'app-center-node-client';

    const client = new AppCenterClient('api token here');

    console.log(client.account.apps.create({
        displayName: 'test',
        os: 'iOS',
        platform: 'mobile'
    }));
```

2) Importing models

Import models from `/models` index path.

```
    import { FileAsset } from 'app-center-node-client/models';
```