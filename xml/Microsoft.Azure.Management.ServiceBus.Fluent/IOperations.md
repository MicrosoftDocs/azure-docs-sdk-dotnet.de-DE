<Type Name="IOperations" FullName="Microsoft.Azure.Management.ServiceBus.Fluent.IOperations">
  <TypeSignature Language="C#" Value="public interface IOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.ServiceBus.Fluent.IOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperations" />
  <TypeSignature Language="F#" Value="type IOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7c24c-101">Vorgänge für Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="7c24c-101">Operations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Operation&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.Operation&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.IOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Operation&gt;&gt;&gt;" Usage="iOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Operation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="7c24c-102">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="7c24c-102">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="7c24c-103">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="7c24c-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c24c-104">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7c24c-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c24c-105">Zeigt eine Liste aller verfügbaren Service Bus REST-API-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="7c24c-105">Lists all of the available ServiceBus REST API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7c24c-106">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="7c24c-106">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7c24c-107">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="7c24c-107">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7c24c-108">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="7c24c-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Operation&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.ServiceBus.Fluent.Models.Operation&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.ServiceBus.Fluent.IOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Operation&gt;&gt;&gt;" Usage="iOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.ServiceBus.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.ServiceBus.Fluent.Models.Operation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="7c24c-109">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="7c24c-109">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="7c24c-110">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="7c24c-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="7c24c-111">Zeigt eine Liste aller verfügbaren Service Bus REST-API-Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="7c24c-111">Lists all of the available ServiceBus REST API operations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="7c24c-112">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="7c24c-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="7c24c-113">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="7c24c-113">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="7c24c-114">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="7c24c-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>