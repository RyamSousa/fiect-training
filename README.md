# AEM WKND Sites Project
## How to use

Pre-compiled AEM packages are available under the latest release for easy installation on local environments using [CRX Package Manager](http://localhost:4502/crx/packmgr/index.jsp)

* [`aem-guides-wknd.all-x.x.x.zip`](https://github.com/adobe/aem-guides-wknd/releases/latest): AEM as a Cloud Service, default build
* [`aem-guides-wknd.all-x.x.x-classic.zip`](https://github.com/adobe/aem-guides-wknd/releases/latest): AEM 6.5.x+

## How to build

For **AEM as a Cloud Service SDK**: 

```
$ cd aem-guides-wknd/
$ mvn clean install -PautoInstallBundle,autoInstallPackage
```

## System Requirements

WKND Version | AEM as a Cloud Service | AEM 6.5   | Java SE | Maven
-------------|------------------------|-----------|---------|---------
Latest (main branch)| Continual              | **6.5.13.0+** |  8, 11  | 3.3.9+
[v1.1.0](https://github.com/adobe/aem-guides-wknd/releases/tag/aem-guides-wknd-1.1.0) | Continual | 6.5.10+ | 8, 11 | 3.3.9+
[v1.0.0](https://github.com/adobe/aem-guides-wknd/releases/tag/aem-guides-wknd-1.0.0) | Continual | 6.5.4+ | 8, 11 | 3.3.9+

Setup your local development environment for [AEM as a Cloud Service SDK](https://experienceleague.adobe.com/docs/experience-manager-learn/cloud-service/local-development-environment-set-up/overview.html) or for [older versions of AEM](https://experienceleague.adobe.com/docs/experience-manager-learn/foundation/development/set-up-a-local-aem-development-environment.html).

# Tutorial

A corresponding [tutorial is available](https://experienceleague.adobe.com/docs/experience-manager-learn/getting-started-wknd-tutorial-develop/overview.html) where you can learn how to implement a website using the latest standards and technologies in AEM Sites.
