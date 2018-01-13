<Type Name="ITransparentDataEncryptionActivitiesOperations" FullName="Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations">
  <TypeSignature Language="C#" Value="public interface ITransparentDataEncryptionActivitiesOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITransparentDataEncryptionActivitiesOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITransparentDataEncryptionActivitiesOperations" />
  <TypeSignature Language="F#" Value="type ITransparentDataEncryptionActivitiesOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="78cd3-101">TransparentDataEncryptionActivitiesOperations-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="78cd3-101">TransparentDataEncryptionActivitiesOperations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListByConfigurationWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt;&gt;&gt; ListByConfigurationWithHttpMessagesAsync (string resourceGroupName, string serverName, string databaseName, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt;&gt;&gt; ListByConfigurationWithHttpMessagesAsync(string resourceGroupName, string serverName, string databaseName, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.ITransparentDataEncryptionActivitiesOperations.ListByConfigurationWithHttpMessagesAsync(System.String,System.String,System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListByConfigurationWithHttpMessagesAsync : string * string * string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;seq&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt;&gt;&gt;" Usage="iTransparentDataEncryptionActivitiesOperations.ListByConfigurationWithHttpMessagesAsync (resourceGroupName, serverName, databaseName, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Sql.Models.TransparentDataEncryptionActivity&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceGroupName" Type="System.String" />
        <Parameter Name="serverName" Type="System.String" />
        <Parameter Name="databaseName" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="resourceGroupName">
            <span data-ttu-id="78cd3-102">Der Name der Ressourcengruppe, die die Ressource enthält.</span><span class="sxs-lookup"><span data-stu-id="78cd3-102">The name of the resource group that contains the resource.</span></span> <span data-ttu-id="78cd3-103">Dieser Wert kann über die Azure-Ressourcen-Manager-API oder das Portal abgerufen werden.</span><span class="sxs-lookup"><span data-stu-id="78cd3-103">You can obtain this value from the Azure Resource Manager API or the portal.</span></span>
            </param>
        <param name="serverName">
            <span data-ttu-id="78cd3-104">Der Name des Servers.</span><span class="sxs-lookup"><span data-stu-id="78cd3-104">The name of the server.</span></span>
            </param>
        <param name="databaseName">
            <span data-ttu-id="78cd3-105">Der Name der Datenbank, für die die transparente datenverschlüsselung bezieht.</span><span class="sxs-lookup"><span data-stu-id="78cd3-105">The name of the database for which the transparent data encryption applies.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="78cd3-106">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="78cd3-106">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="78cd3-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="78cd3-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="78cd3-108">Gibt eine Datenbank transparent Data Encryption Ergebnis des Vorgangs zurück.</span><span class="sxs-lookup"><span data-stu-id="78cd3-108">Returns a database's transparent data encryption operation result.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="78cd3-109">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="78cd3-109">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="78cd3-110">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="78cd3-110">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="78cd3-111">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="78cd3-111">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>