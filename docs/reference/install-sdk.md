---
title: Install Rarible SDK
description: The main information about installing and initializing Rarible Multichain SDK
---

# Install Rarible SDK

## Installation

1. Protocol SDK:

    ```shell
    yarn add @rarible/sdk -D
    yarn add web3
    ```

2. SDK Wallet Connector:

    ```shell
    yarn add @rarible/connector
    # optional: add additional connectors
    yarn add @rarible/connector-walletconnect
    yarn add @rarible/connector-fortmatic
    # check other @rarible/connector-* packages to see what's supported 
    ```
    
    See more information about [Initialize wallets](wallets.md) with Wallet Connector. 

Make sure the SDK is installed correctly:

```shell
npm view @rarible/sdk version
```

## Using SDK on client application

SDK is written in TypeScript. You can use typings to explore SDK possibilities.

```ts
import { createRaribleSdk } from "@rarible/sdk"
import { Blockchain } from "@rarible/api-client"
```

--8<-- "docs/snippets/usage-sdk-on-server.md"