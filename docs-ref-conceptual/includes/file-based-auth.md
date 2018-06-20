<span data-ttu-id="f8ba2-101">Erstellen Sie eine Textdatei namens `azureauth.properties` mit den Dienstprinzipal-Anmeldeinformationen:</span><span class="sxs-lookup"><span data-stu-id="f8ba2-101">Create a text file named `azureauth.properties` using the service principal credentials:</span></span>

```plaintext
# sample management library properties file
subscription=15dbcfa8-4b93-4c9a-881c-6189d39f04d4
client=a2ab11af-01aa-4759-8345-7803287dbd39
key=password
tenant=43413cc1-5886-4711-9804-8cfea3d1c3ee
managementURI=https://management.core.windows.net/
baseURL=https://management.azure.com/
authURL=https://login.windows.net/
graphURL=https://graph.windows.net/
```

- <span data-ttu-id="f8ba2-102">subscription: Verwenden Sie den *SubscriptionId*-Wert aus der Ausführung von `Login-AzureRmAccount`.</span><span class="sxs-lookup"><span data-stu-id="f8ba2-102">subscription: use the *SubscriptionId* value from when you ran `Login-AzureRmAccount`.</span></span>
- <span data-ttu-id="f8ba2-103">client: Verwenden Sie den Wert von *ApplicationId* aus der Dienstprinzipalausgabe.</span><span class="sxs-lookup"><span data-stu-id="f8ba2-103">client: use the *ApplicationId* value from the service principal output.</span></span>
- <span data-ttu-id="f8ba2-104">key: Verwenden Sie den Parameter *-Password* (ohne Anführungszeichen), den Sie bei der Ausführung von `New-AzureRmADServicePrincipal` zugewiesen haben .</span><span class="sxs-lookup"><span data-stu-id="f8ba2-104">key: use the *-Password* parameter you assigned when you ran `New-AzureRmADServicePrincipal` (without quotes).</span></span>
- <span data-ttu-id="f8ba2-105">tenant: Verwenden Sie den Wert von *TenantId* aus der Ausführung von `Login-AzureRmAccount`.</span><span class="sxs-lookup"><span data-stu-id="f8ba2-105">tenant: use the *TenantId* value from when you ran `Login-AzureRmAccount`.</span></span>

<span data-ttu-id="f8ba2-106">Speichern Sie diese Datei an einem sicheren Ort in Ihrem System, an dem sie vom Code gelesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="f8ba2-106">Save this file in a secure location on your system where your code can read it.</span></span> <span data-ttu-id="f8ba2-107">Verwenden Sie PowerShell zum Festlegen einer Umgebungsvariablen mit dem Namen `AZURE_AUTH_LOCATION` mit dem vollständigen Pfad zur Datei, z.B.:</span><span class="sxs-lookup"><span data-stu-id="f8ba2-107">Use PowerShell to set an environment variable named `AZURE_AUTH_LOCATION` with the full path to the file, for example:</span></span>

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.properties", "User")
```
