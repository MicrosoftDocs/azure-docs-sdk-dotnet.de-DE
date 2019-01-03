---
ms.service: multiple
ms.date: 9/20/2018
ms.topic: include
ms.openlocfilehash: 7f7c24957d2bc0574fc0b1bf2a8ae8fe8b4dfc64
ms.sourcegitcommit: e25b6ac74033f3b0a7610bf66feb654acb43054c
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 12/15/2018
ms.locfileid: "53430520"
---
<span data-ttu-id="4c932-101">Erstellen Sie eine Textdatei namens `azureauth.json`.</span><span class="sxs-lookup"><span data-stu-id="4c932-101">Create a text file named `azureauth.json`.</span></span> <span data-ttu-id="4c932-102">Fügen Sie die JSON-Ausgabe ein, die Sie beim Erstellen des Dienstprinzipals erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="4c932-102">Paste the JSON output from when you created the service principal.</span></span>

<span data-ttu-id="4c932-103">Speichern Sie diese Datei an einem sicheren Ort in Ihrem System, an dem sie vom Code gelesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="4c932-103">Save this file in a secure location on your system where your code can read it.</span></span> <span data-ttu-id="4c932-104">Verwenden Sie PowerShell zum Festlegen einer Umgebungsvariablen mit dem Namen `AZURE_AUTH_LOCATION` mit dem vollständigen Pfad zur Datei, z.B.:</span><span class="sxs-lookup"><span data-stu-id="4c932-104">Use PowerShell to set an environment variable named `AZURE_AUTH_LOCATION` with the full path to the file, for example:</span></span>

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.json", "User")
```
