---
title: Azure GraalVM Netty Support client library for Java
keywords: Azure, java, SDK, API, azure-aot-graalvm-support-netty, aot
author: joshfree
ms.author: jfree
ms.date: 04/08/2022
ms.topic: reference
ms.prod: azure
ms.technology: azure
ms.devlang: java
ms.service: aot
---
# Azure GraalVM Netty Support client library for Java - Version 1.0.0-beta.1 


The Azure GraalVM Netty Support client library provides support for applications using 
[Azure client libraries](https://azure.github.io/azure-sdk/releases/latest/java.html) that take a dependency on 
[azure-core-http-netty](https://github.com/Azure/azure-sdk-for-java/tree/azure-aot-graalvm-support-netty_1.0.0-beta.1/sdk/core/azure-core-http-netty) to be 
built as [GraalVM nativeimages](https://www.graalvm.org/22.0/reference-manual/native-image/). The library contains all the necessary
[configuration files](https://www.graalvm.org/22.0/reference-manual/native-image/BuildConfiguration/) and [GraalVM
features](https://www.graalvm.org/sdk/javadoc/index.html?org/graalvm/nativeimage/hosted/Feature.html) required to build
a native image of an application that uses Azure client libraries.

## Getting started

### Prerequisites
- A [Java Development Kit (JDK)][jdk_link], version 8 or later.
- [Azure Subscription][azure_subscription]
- [GraalVM](https://www.graalvm.org/downloads/) version 22 or later.
- [GraalVM Native Image](https://www.graalvm.org/22.0/reference-manual/native-image/)
- 
### Include the package

This package should be included in addition to `azure-aot-graalvm-support` library when using Azure client libraries 
that take a dependency on `azure-core-http-netty`.

[//]: # ({x-version-update-start;com.azure:azure-aot-graalvm-support-netty;current})
```xml
<dependency>
    <groupId>com.azure</groupId>
    <artifactId>azure-aot-graalvm-support-netty</artifactId>
    <version>1.0.0-beta.1</version>
</dependency>
```
## Key concepts

Please refer to the [Key Concepts](https://github.com/Azure/azure-sdk-for-java/tree/azure-aot-graalvm-support-netty_1.0.0-beta.1/sdk/aot/azure-aot-graalvm-support#key-concepts) section of the azure-aot-graalvm-support library.

## Examples

Please refer to the [Examples](https://github.com/Azure/azure-sdk-for-java/tree/azure-aot-graalvm-support-netty_1.0.0-beta.1/sdk/aot/azure-aot-graalvm-support#examples) section of the 
`azure-aot-graalvm-support` library.

## Troubleshooting
Please refer to the [Troubleshooting](https://github.com/Azure/azure-sdk-for-java/tree/azure-aot-graalvm-support-netty_1.0.0-beta.1/sdk/aot/azure-aot-graalvm-support#troubleshooting) section of the
`azure-aot-graalvm-support` library.

## Next steps
Please refer to the [Next Steps](https://github.com/Azure/azure-sdk-for-java/tree/azure-aot-graalvm-support-netty_1.0.0-beta.1/sdk/aot/azure-aot-graalvm-support#next-steps) section of the
`azure-aot-graalvm-support` library.

## Contributing

This project welcomes contributions and suggestions. Most contributions require you to agree to a Contributor License
Agreement (CLA) declaring that you have the right to, and actually do, grant us the rights to use your contribution.
For details, visit [https://cla.microsoft.com](https://cla.microsoft.com).

When you submit a pull request, a CLA-bot will automatically determine whether you need to provide a CLA and decorate the
PR appropriately (e.g., label, comment). Simply follow the instructions provided by the bot. You will only need to do this
once across all repos using our CLA.

This project has adopted the [Microsoft Open Source Code of Conduct](https://opensource.microsoft.com/codeofconduct/).
For more information see the [Code of Conduct FAQ](https://opensource.microsoft.com/codeofconduct/faq/) or contact
[opencode@microsoft.com](mailto:opencode@microsoft.com) with any additional questions or comments.

<!-- LINKS -->
[cla]: https://cla.microsoft.com
[coc]: https://opensource.microsoft.com/codeofconduct/
[coc_faq]: https://opensource.microsoft.com/codeofconduct/faq/
[coc_contact]: mailto:opencode@microsoft.com
[jdk_link]: https://docs.microsoft.com/java/azure/jdk/?view=azure-java-stable
[azure_subscription]: https://azure.microsoft.com/free

![Impressions](https://azure-sdk-impressions.azurewebsites.net/api/impressions/azure-sdk-for-java%2Fsdk%2Faot%2Fazure-aot-graalvm-support-netty%2FREADME.png)

