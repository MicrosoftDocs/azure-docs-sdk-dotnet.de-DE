---
<span data-ttu-id="e6df3-101">uid: Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters) Zusammenfassung: *Inhalt</span><span class="sxs-lookup"><span data-stu-id="e6df3-101">uid: Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters) summary: *content</span></span>
---

<span data-ttu-id="e6df3-102">Hier ist Inhalt aufgeführt, der durch die Methode zur Dateiüberschreibung eingefügt wird, sodass Autoren der erstellten API-Dokumentation Inhalt in beliebigem Umfang im Markdown-Format hinzufügen können.</span><span class="sxs-lookup"><span data-stu-id="e6df3-102">Here is content that is injected by the overwrite file method, so writers can add as much as they want to the generated API documentation in Markown format.</span></span>

---
<span data-ttu-id="e6df3-103">uid: Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters) Hinweise: *Inhalt</span><span class="sxs-lookup"><span data-stu-id="e6df3-103">uid: Microsoft.Azure.Management.Compute.VirtualMachinesOperationsExtensions.Capture(Microsoft.Azure.Management.Compute.IVirtualMachinesOperations,System.String,System.String,Microsoft.Azure.Management.Compute.Models.VirtualMachineCaptureParameters) remarks: *content</span></span>
---

<span data-ttu-id="e6df3-104">Der folgende Code veranschaulicht, wie die Capture-Methode mithilfe des Azure .NET SDK aufgerufen wird.</span><span class="sxs-lookup"><span data-stu-id="e6df3-104">The code below demonstrates how to call the Capture method using the Azure .NET SDK.</span></span> 

```csharp
using Microsoft.Azure.Management.Compute;
using Microsoft.Azure.Management.Compute.Models;
using Microsoft.Rest;

namespace MyAzureVmClientApp
{
    class Program
    {
        static void Main(string[] args)
        {
            var token = "[Token Obtained from ADAL]";

            var credential = new TokenCredentials(token);

            var captureResponse = 
                new ComputeManagementClient(credential)
                .VirtualMachines
                    .Capture(
                        "myResourceGroup",
                        "myVmName",
                        new VirtualMachineCaptureParameters
                        {
                            DestinationContainerName = "myblobcontainer",
                            OverwriteVhds = true,
                            VhdPrefix = "backup"
                        });
        }
    }
}
```

