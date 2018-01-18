<Type Name="ITypeFieldOperations" FullName="Microsoft.Azure.Management.Automation.ITypeFieldOperations">
  <TypeSignature Language="C#" Value="public interface ITypeFieldOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITypeFieldOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Automation.ITypeFieldOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITypeFieldOperations" />
  <TypeSignature Language="F#" Value="type ITypeFieldOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="5a4b9-101">Der Dienstvorgang für Automation-Feldern.</span><span class="sxs-lookup"><span data-stu-id="5a4b9-101">Service operation for automation type fields.</span></span>  <span data-ttu-id="5a4b9-102">(siehe http://aka.ms/azureautomationsdk/typefieldoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5a4b9-102">(see http://aka.ms/azureautomationsdk/typefieldoperations for more information)</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListAsync (string resourceGroupName, string automationAccount, string moduleName, string typeName, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt; ListAsync(string resourceGroupName, string automationAccount, string moduleName, string typeName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Automation.ITypeFieldOperations.ListAsync(System.String,System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListAsync : string * string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;" Usage="iTypeFieldOperations.ListAsync (resourceGroupName, automationAccount, moduleName, typeName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Automation</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Automation.Models.TypeFieldListResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="automationAccount" Type="System.String" />
        <Parameter Name="moduleName" Type="System.String" />
        <Parameter Name="typeName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="5a4b9-103">der Name der Ressourcengruppe</span><span class="sxs-lookup"><span data-stu-id="5a4b9-103">The name of the resource group</span></span>
            </param>
        <param name="automationAccount">
            <span data-ttu-id="5a4b9-104">Der Name des Automation-Konto.</span><span class="sxs-lookup"><span data-stu-id="5a4b9-104">The automation account name.</span></span>
            </param>
        <param name="moduleName">
            <span data-ttu-id="5a4b9-105">Der Name des Moduls.</span><span class="sxs-lookup"><span data-stu-id="5a4b9-105">The name of module.</span></span>
            </param>
        <param name="typeName">
            <span data-ttu-id="5a4b9-106">Der Name des Typs.</span><span class="sxs-lookup"><span data-stu-id="5a4b9-106">The name of type.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="5a4b9-107">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="5a4b9-107">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="5a4b9-108">Abgerufen Sie eine Liste der Felder eines bestimmten Typs Modulname identifizierte werden.</span><span class="sxs-lookup"><span data-stu-id="5a4b9-108">Retrieve a list of fields of a given type identified by module name.</span></span>  <span data-ttu-id="5a4b9-109">(siehe http://aka.ms/azureautomationsdk/typefieldoperations für Weitere Informationen)</span><span class="sxs-lookup"><span data-stu-id="5a4b9-109">(see http://aka.ms/azureautomationsdk/typefieldoperations for more information)</span></span>
            </summary>
        <returns>
            <span data-ttu-id="5a4b9-110">Das Antwort-Modell für die Liste Felder-Vorgang.</span><span class="sxs-lookup"><span data-stu-id="5a4b9-110">The response model for the list fields operation.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>