---
ms.service: multiple
ms.date: 9/20/2018
ms.topic: include
ms.openlocfilehash: 7f7c24957d2bc0574fc0b1bf2a8ae8fe8b4dfc64
ms.sourcegitcommit: 70982e900bd4adfbc121eba55d94544f17c6b495
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 11/06/2018
ms.locfileid: "51196046"
---
<span data-ttu-id="c0b68-101">Erstellen Sie eine Textdatei namens `azureauth.json`.</span><span class="sxs-lookup"><span data-stu-id="c0b68-101">Create a text file named `azureauth.json`.</span></span> <span data-ttu-id="c0b68-102">Fügen Sie die JSON-Ausgabe ein, die Sie beim Erstellen des Dienstprinzipals erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="c0b68-102">Paste the JSON output from when you created the service principal.</span></span>

<span data-ttu-id="c0b68-103">Speichern Sie diese Datei an einem sicheren Ort in Ihrem System, an dem sie vom Code gelesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="c0b68-103">Save this file in a secure location on your system where your code can read it.</span></span> <span data-ttu-id="c0b68-104">Verwenden Sie PowerShell zum Festlegen einer Umgebungsvariablen mit dem Namen `AZURE_AUTH_LOCATION` mit dem vollständigen Pfad zur Datei, z.B.:</span><span class="sxs-lookup"><span data-stu-id="c0b68-104">Use PowerShell to set an environment variable named `AZURE_AUTH_LOCATION` with the full path to the file, for example:</span></span>

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.json", "User")
```
