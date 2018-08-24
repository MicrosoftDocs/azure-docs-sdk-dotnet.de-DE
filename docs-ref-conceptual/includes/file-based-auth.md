<span data-ttu-id="46da9-101">Erstellen Sie eine Textdatei namens `azureauth.json`.</span><span class="sxs-lookup"><span data-stu-id="46da9-101">Create a text file named `azureauth.json`.</span></span> <span data-ttu-id="46da9-102">Fügen Sie die JSON-Ausgabe ein, die Sie beim Erstellen des Dienstprinzipals erhalten haben.</span><span class="sxs-lookup"><span data-stu-id="46da9-102">Paste the JSON output from when you created the service principal.</span></span>

<span data-ttu-id="46da9-103">Speichern Sie diese Datei an einem sicheren Ort in Ihrem System, an dem sie vom Code gelesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="46da9-103">Save this file in a secure location on your system where your code can read it.</span></span> <span data-ttu-id="46da9-104">Verwenden Sie PowerShell zum Festlegen einer Umgebungsvariablen mit dem Namen `AZURE_AUTH_LOCATION` mit dem vollständigen Pfad zur Datei, z.B.:</span><span class="sxs-lookup"><span data-stu-id="46da9-104">Use PowerShell to set an environment variable named `AZURE_AUTH_LOCATION` with the full path to the file, for example:</span></span>

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.json", "User")
```
