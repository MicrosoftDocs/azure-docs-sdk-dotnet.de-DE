<Type Name="IContainerLogsOperations" FullName="Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations">
  <TypeSignature Language="C#" Value="public interface IContainerLogsOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IContainerLogsOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IContainerLogsOperations" />
  <TypeSignature Language="F#" Value="type IContainerLogsOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
    <AssemblyVersion>0.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="366c1-101">ContainerLogsOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="366c1-101">ContainerLogsOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt; ListWithHttpMessagesAsync (string resourceGroupName, string containerGroupName, string containerName, Nullable&lt;int&gt; tail = null, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt; ListWithHttpMessagesAsync(string resourceGroupName, string containerGroupName, string containerName, valuetype System.Nullable`1&lt;int32&gt; tail, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ContainerInstance.IContainerLogsOperations.ListWithHttpMessagesAsync(System.String,System.String,System.String,System.Nullable{System.Int32},System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : string * string * string * Nullable&lt;int&gt; * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt;" Usage="iContainerLogsOperations.ListWithHttpMessagesAsync (resourceGroupName, containerGroupName, containerName, tail, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ContainerInstance</AssemblyName>
        <AssemblyVersion>0.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Azure.Management.ContainerInstance.Models.Logs&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="containerGroupName" Type="System.String" />
        <Parameter Name="containerName" Type="System.String" />
        <Parameter Name="tail" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="366c1-102">Der Name der Ressourcengruppe.</span><span class="sxs-lookup"><span data-stu-id="366c1-102">The name of the resource group.</span></span>
            </param>
        <param name="containerGroupName">
            <span data-ttu-id="366c1-103">Der Name der Gruppe "Container".</span><span class="sxs-lookup"><span data-stu-id="366c1-103">The name of the container group.</span></span>
            </param>
        <param name="containerName">
            <span data-ttu-id="366c1-104">Der Name der Containerinstanz.</span><span class="sxs-lookup"><span data-stu-id="366c1-104">The name of the container instance.</span></span>
            </param>
        <param name="tail">
            <span data-ttu-id="366c1-105">Die Anzahl der Zeilen, die das Ende des Protokolls Instanz Container anzuzeigen.</span><span class="sxs-lookup"><span data-stu-id="366c1-105">The number of lines to show from the tail of the container instance log.</span></span> <span data-ttu-id="366c1-106">Wenn nicht angegeben, werden alle verfügbaren Protokolle mit bis zu 4 mb angezeigt.</span><span class="sxs-lookup"><span data-stu-id="366c1-106">If not provided, all available logs are shown up to 4mb.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="366c1-107">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="366c1-107">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="366c1-108">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="366c1-108">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="366c1-109">Rufen Sie die Protokolle für eine Instanz des angegebenen Container.</span><span class="sxs-lookup"><span data-stu-id="366c1-109">Get the logs for a specified container instance.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="366c1-110">Rufen Sie die Protokolle für eine Instanz der angegebenen Container in einem angegebenen Ressourcengruppe und die Containergruppe.</span><span class="sxs-lookup"><span data-stu-id="366c1-110">Get the logs for a specified container instance in a specified resource group and container group.</span></span>
            </remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="366c1-111">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="366c1-111">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="366c1-112">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="366c1-112">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="366c1-113">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="366c1-113">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>