---
title: "Azure-Verwaltungsbibliotheken für .NET-Beispielanweisungen"
description: "Rufen Sie Beispielcode für das Erstellen und Aktualisieren von Ressourcen mithilfe der Azure-Verwaltungsbibliotheken für .NET ab."
keywords: Azure, .NET, SDK, API, Beispiele, Beispiel
author: camsoper
ms.author: casoper
manager: douge
ms.date: 06/20/2017
ms.topic: article
ms.prod: azure
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.assetid: 
ms.openlocfilehash: ffda7cca724962e6f953432c5cab04485ddabb03
ms.sourcegitcommit: d95a6ad3774a49b16f652e40e7860e47636c7ad0
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 08/28/2017
---
# <a name="azure-management-libraries-for-net-sample-instructions"></a>Azure-Verwaltungsbibliotheken für .NET-Beispielanweisungen

In diesem Artikel werden die Voraussetzungen und die Authentifizierung beschrieben, die für die Ausführung der Beispiele für die Azure-Verwaltungsbibliotheken für .NET erforderlich ist.

## <a name="prerequisties"></a>Voraussetzungen 

* [Visual Studio 2017](https://www.visualstudio.com/vs/) oder [.NET Core SDK](https://www.microsoft.com/net/download/core)
* Ein [Microsoft Azure-Abonnement](https://azure.microsoft.com/free/)
* [Git-Befehlszeilenclient](https://git-scm.com/)
* [Azure PowerShell](https://docs.microsoft.com/en-us/powershell/azure/install-azurerm-ps)

## <a name="authentication-for-all-samples"></a>Authentifizierung für alle Beispiele

[!include[Create service principal](includes/create-sp.md)]

[!include[File-based authentication](includes/file-based-auth.md)]

## <a name="running-the-samples"></a>Ausführen der Beispiele

Sobald Sie Git zum Klonen des Beispiels verwendet haben, können Sie das Beispiel in Visual Studio öffnen und es mithilfe der IDE ausführen.  Verwenden Sie alternativ das .NET Core SDK zum Erstellen und Ausführen des Beispiels über die Befehlszeile wie folgt:

```cmd
git clone https://github.com/Azure-Samples/app-service-dotnet-configure-deployment-sources-for-web-apps.git
cd app-service-dotnet-configure-deployment-sources-for-web-apps
dotnet restore
dotnet run
```