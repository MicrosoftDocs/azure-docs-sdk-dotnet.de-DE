Erstellen Sie eine Textdatei namens `azureauth.properties` mit den Dienstprinzipal-Anmeldeinformationen:

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

- subscription: Verwenden Sie den *SubscriptionId*-Wert aus der Ausführung von `Login-AzureRmAccount`.
- client: Verwenden Sie den Wert von *ApplicationId* aus der Dienstprinzipalausgabe.
- key: Verwenden Sie den Parameter *-Password* (ohne Anführungszeichen), den Sie bei der Ausführung von `New-AzureRmADServicePrincipal` zugewiesen haben .
- tenant: Verwenden Sie den Wert von *TenantId* aus der Ausführung von `Login-AzureRmAccount`.

Speichern Sie diese Datei an einem sicheren Ort in Ihrem System, an dem sie vom Code gelesen werden kann. Verwenden Sie PowerShell zum Festlegen einer Umgebungsvariablen mit dem Namen `AZURE_AUTH_LOCATION` mit dem vollständigen Pfad zur Datei, z.B.:

```powershell
[Environment]::SetEnvironmentVariable("AZURE_AUTH_LOCATION", "C:\src\azureauth.properties", "User")
```
