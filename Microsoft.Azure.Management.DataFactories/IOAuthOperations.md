<Type Name="IOAuthOperations" FullName="Microsoft.Azure.Management.DataFactories.IOAuthOperations">
  <TypeSignature Language="C#" Value="public interface IOAuthOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOAuthOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.DataFactories.IOAuthOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOAuthOperations" />
  <TypeSignature Language="F#" Value="type IOAuthOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
    <AssemblyVersion>4.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="12e84-101">Vorgänge für die OAuth-Autorisierung.</span><span class="sxs-lookup"><span data-stu-id="12e84-101">Operations for OAuth authorization.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt; GetAsync (string resourceGroupName, string dataFactoryName, string linkedServiceType, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt; GetAsync(string resourceGroupName, string dataFactoryName, string linkedServiceType, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.DataFactories.IOAuthOperations.GetAsync(System.String,System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAsync : string * string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt;" Usage="iOAuthOperations.GetAsync (resourceGroupName, dataFactoryName, linkedServiceType, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.DataFactories</AssemblyName>
        <AssemblyVersion>4.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.DataFactories.Models.AuthorizationSessionGetResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="dataFactoryName" Type="System.String" />
        <Parameter Name="linkedServiceType" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="12e84-102">Der Ressourcengruppenname der Data Factory.</span><span class="sxs-lookup"><span data-stu-id="12e84-102">The resource group name of the data factory.</span></span>
            </param>
        <param name="dataFactoryName">
            <span data-ttu-id="12e84-103">Eine eindeutige Data Factory-Instanzname.</span><span class="sxs-lookup"><span data-stu-id="12e84-103">A unique data factory instance name.</span></span>
            </param>
        <param name="linkedServiceType">
            <span data-ttu-id="12e84-104">Der Typ des verknüpften OAuth-Dienst.</span><span class="sxs-lookup"><span data-stu-id="12e84-104">The type of OAuth linked service.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="12e84-105">Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="12e84-105">Cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="12e84-106">Ruft eine Sitzung für OAuth Authorization ab.</span><span class="sxs-lookup"><span data-stu-id="12e84-106">Gets an OAuth authorization session.</span></span>
            </summary>
        <returns>
            <span data-ttu-id="12e84-107">Get-Autorisierung Sitzung Antworten für den Vorgang.</span><span class="sxs-lookup"><span data-stu-id="12e84-107">The Get authorization session operation response.</span></span>
            </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>