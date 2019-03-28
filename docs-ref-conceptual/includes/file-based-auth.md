---
ms.service: multiple
ms.date: 9/20/2018
ms.topic: include
ms.openlocfilehash: 7f7c24957d2bc0574fc0b1bf2a8ae8fe8b4dfc64
ms.sourcegitcommit: e534dad2d96b72ab6a9bc4b5567508962bd7e05c
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 03/22/2019
ms.locfileid: "58343339"
---
<span data-ttu-id="efe57-101">Erstellen Sie eine Textdatei namens `azureauth.json`.</span><span class="sxs-lookup"><span data-stu-id="efe57-101">Create a text file named `azureauth.json`.</span></span> <span data-ttu-id="efe57-102">Fügen Sie die JSON-Ausgabe ein, die Sie beim Erstellen des Dienstprinzipals erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="efe57-102">Paste the JSON output from when you created the service principal.</span></span>

<span data-ttu-id="efe57-103">Speichern Sie diese Datei an einem sicheren Ort in Ihrem System, an dem sie vom Code gelesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="efe57-103">Save this file in a secure location on your system where your code can read it.</span></span> <span data-ttu-id="efe57-104">Verwenden Sie PowerShell zum Festlegen einer Umgebungsvariablen mit dem Namen `AZURE_AUTH_LOCATION` mit dem vollständigen Pfad zur Datei, z.B.:</span><span class="sxs-lookup"><span data-stu-id="efe57-104">Use PowerShell to set an environment variable named `AZURE_AUTH_LOCATION` with the full path to the file, for example:</span></span>

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.json", "User")
```
