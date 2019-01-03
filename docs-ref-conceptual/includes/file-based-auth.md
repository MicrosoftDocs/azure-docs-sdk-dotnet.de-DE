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
Erstellen Sie eine Textdatei namens `azureauth.json`. Fügen Sie die JSON-Ausgabe ein, die Sie beim Erstellen des Dienstprinzipals erhalten haben.

Speichern Sie diese Datei an einem sicheren Ort in Ihrem System, an dem sie vom Code gelesen werden kann. Verwenden Sie PowerShell zum Festlegen einer Umgebungsvariablen mit dem Namen `AZURE_AUTH_LOCATION` mit dem vollständigen Pfad zur Datei, z.B.:

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.json", "User")
```
