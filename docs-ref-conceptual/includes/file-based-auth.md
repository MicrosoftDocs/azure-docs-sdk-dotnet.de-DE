---
ms.service: multiple
ms.date: 9/20/2018
ms.topic: include
ms.openlocfilehash: 7f7c24957d2bc0574fc0b1bf2a8ae8fe8b4dfc64
ms.sourcegitcommit: 5d9b713653b3d03e1d0a67f6e126ee399d1c2a60
ms.translationtype: HT
ms.contentlocale: de-DE
ms.lasthandoff: 09/26/2018
ms.locfileid: "47190713"
---
Erstellen Sie eine Textdatei namens `azureauth.json`. Fügen Sie die JSON-Ausgabe ein, die Sie beim Erstellen des Dienstprinzipals erhalten haben.

Speichern Sie diese Datei an einem sicheren Ort in Ihrem System, an dem sie vom Code gelesen werden kann. Verwenden Sie PowerShell zum Festlegen einer Umgebungsvariablen mit dem Namen `AZURE_AUTH_LOCATION` mit dem vollständigen Pfad zur Datei, z.B.:

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.json", "User")
```
