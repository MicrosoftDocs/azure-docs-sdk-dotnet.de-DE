---
title: "Azure-Verwaltungsbibliotheken für .NET-Beispielanweisungen"
description: "Rufen Sie Beispielcode für das Erstellen und Aktualisieren von Ressourcen mithilfe der Azure-Verwaltungsbibliotheken für .NET ab."
keywords: Azure, .NET, SDK, API, Beispiele, Beispiel
author: camsoper
ms.author: casoper
manager: wpickett
ms.date: 10/19/2017
ms.topic: reference
ms.technology: azure
ms.devlang: dotnet
ms.service: multiple
ms.custom: devcenter
ms.openlocfilehash: a931e623768e1fddad263c7da8eb864c37613379
ms.sourcegitcommit: 3ba0ff4463338a0ab0f3f15a7601b89417c06970
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/05/2018
---
# <a name="azure-management-libraries-for-net-sample-instructions"></a><span data-ttu-id="7d910-104">Azure-Verwaltungsbibliotheken für .NET-Beispielanweisungen</span><span class="sxs-lookup"><span data-stu-id="7d910-104">Azure management libraries for .NET sample instructions</span></span>

<span data-ttu-id="7d910-105">In diesem Artikel werden die Voraussetzungen und die Authentifizierung beschrieben, die für die Ausführung der Beispiele für die Azure-Verwaltungsbibliotheken für .NET erforderlich ist.</span><span class="sxs-lookup"><span data-stu-id="7d910-105">This article describes the prerequisites and authentication required for running the samples for the Azure management libraries for .NET.</span></span>

## <a name="prerequisties"></a><span data-ttu-id="7d910-106">Voraussetzungen</span><span class="sxs-lookup"><span data-stu-id="7d910-106">Prerequisties</span></span> 

* <span data-ttu-id="7d910-107">[Visual Studio 2017](https://www.visualstudio.com/vs/) oder [.NET Core SDK](https://www.microsoft.com/net/download/core)</span><span class="sxs-lookup"><span data-stu-id="7d910-107">[Visual Studio 2017](https://www.visualstudio.com/vs/) or [.NET Core SDK](https://www.microsoft.com/net/download/core)</span></span>
* <span data-ttu-id="7d910-108">Ein [Microsoft Azure-Abonnement](https://azure.microsoft.com/free/)</span><span class="sxs-lookup"><span data-stu-id="7d910-108">A [Microsoft Azure subscription](https://azure.microsoft.com/free/)</span></span>
* [<span data-ttu-id="7d910-109">Git-Befehlszeilenclient</span><span class="sxs-lookup"><span data-stu-id="7d910-109">Git command line client</span></span>](https://git-scm.com/)
* [<span data-ttu-id="7d910-110">Azure PowerShell</span><span class="sxs-lookup"><span data-stu-id="7d910-110">Azure PowerShell</span></span>](/powershell/azure/install-azurerm-ps)

## <a name="authentication-for-all-samples"></a><span data-ttu-id="7d910-111">Authentifizierung für alle Beispiele</span><span class="sxs-lookup"><span data-stu-id="7d910-111">Authentication for all samples</span></span>

[!include[Create service principal](includes/create-sp.md)]

[!include[File-based authentication](includes/file-based-auth.md)]

## <a name="running-the-samples"></a><span data-ttu-id="7d910-112">Ausführen der Beispiele</span><span class="sxs-lookup"><span data-stu-id="7d910-112">Running the samples</span></span>

<span data-ttu-id="7d910-113">Sobald Sie Git zum Klonen des Beispiels verwendet haben, können Sie das Beispiel in Visual Studio öffnen und es mithilfe der IDE ausführen.</span><span class="sxs-lookup"><span data-stu-id="7d910-113">Once you have used Git to clone the sample, you can open the sample in Visual Studio and run the sample using the IDE.</span></span>  <span data-ttu-id="7d910-114">Verwenden Sie alternativ das .NET Core SDK zum Erstellen und Ausführen des Beispiels über die Befehlszeile wie folgt:</span><span class="sxs-lookup"><span data-stu-id="7d910-114">Alternatively, use the .NET Core SDK to build and run the sample from the command line, like this:</span></span>

```cmd
git clone https://github.com/Azure-Samples/app-service-dotnet-configure-deployment-sources-for-web-apps.git
cd app-service-dotnet-configure-deployment-sources-for-web-apps
dotnet restore
dotnet run
```