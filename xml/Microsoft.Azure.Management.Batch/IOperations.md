<Type Name="IOperations" FullName="Microsoft.Azure.Management.Batch.IOperations">
  <TypeSignature Language="C#" Value="public interface IOperations" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IOperations" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.IOperations" />
  <TypeSignature Language="VB.NET" Value="Public Interface IOperations" />
  <TypeSignature Language="F#" Value="type IOperations = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
    <AssemblyVersion>6.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9197b-101">Vorgänge für Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="9197b-101">Operations operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ListNextWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Operation&gt;&gt;&gt; ListNextWithHttpMessagesAsync (string nextPageLink, System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Operation&gt;&gt;&gt; ListNextWithHttpMessagesAsync(string nextPageLink, class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IOperations.ListNextWithHttpMessagesAsync(System.String,System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListNextWithHttpMessagesAsync : string * System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Operation&gt;&gt;&gt;" Usage="iOperations.ListNextWithHttpMessagesAsync (nextPageLink, customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Operation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nextPageLink" Type="System.String" />
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="nextPageLink">
            <span data-ttu-id="9197b-102">Die "NextLink" aus dem vorherigen erfolgreichen Aufruf List-Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="9197b-102">The NextLink from the previous successful call to List operation.</span></span>
            </param>
        <param name="customHeaders">
            <span data-ttu-id="9197b-103">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9197b-103">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9197b-104">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9197b-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9197b-105">Eine Liste der verfügbaren Vorgänge für den Anbieter Microsoft.Batch</span><span class="sxs-lookup"><span data-stu-id="9197b-105">Lists available operations for the Microsoft.Batch provider</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9197b-106">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="9197b-106">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9197b-107">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="9197b-107">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9197b-108">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="9197b-108">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
    <Member MemberName="ListWithHttpMessagesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Operation&gt;&gt;&gt; ListWithHttpMessagesAsync (System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; customHeaders = null, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Rest.Azure.AzureOperationResponse`1&lt;class Microsoft.Rest.Azure.IPage`1&lt;class Microsoft.Azure.Management.Batch.Models.Operation&gt;&gt;&gt; ListWithHttpMessagesAsync(class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; customHeaders, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.IOperations.ListWithHttpMessagesAsync(System.Collections.Generic.Dictionary{System.String,System.Collections.Generic.List{System.String}},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListWithHttpMessagesAsync : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Operation&gt;&gt;&gt;" Usage="iOperations.ListWithHttpMessagesAsync (customHeaders, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
        <AssemblyVersion>6.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Rest.Azure.AzureOperationResponse&lt;Microsoft.Rest.Azure.IPage&lt;Microsoft.Azure.Management.Batch.Models.Operation&gt;&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="customHeaders" Type="System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="customHeaders">
            <span data-ttu-id="9197b-109">Die Header, die hinzugefügt werden auf Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9197b-109">The headers that will be added to request.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9197b-110">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9197b-110">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9197b-111">Eine Liste der verfügbaren Vorgänge für den Anbieter Microsoft.Batch</span><span class="sxs-lookup"><span data-stu-id="9197b-111">Lists available operations for the Microsoft.Batch provider</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <exception cref="T:Microsoft.Rest.Azure.CloudException">
            <span data-ttu-id="9197b-112">Wird ausgelöst, wenn der Vorgang einen ungültigen Statuscode zurückgegeben hat.</span><span class="sxs-lookup"><span data-stu-id="9197b-112">Thrown when the operation returned an invalid status code</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.SerializationException">
            <span data-ttu-id="9197b-113">Wird ausgelöst, wenn nicht die Antwort zu deserialisieren.</span><span class="sxs-lookup"><span data-stu-id="9197b-113">Thrown when unable to deserialize the response</span></span>
            </exception>
        <exception cref="T:Microsoft.Rest.ValidationException">
            <span data-ttu-id="9197b-114">Wird ausgelöst, wenn ein erforderlicher Parameter null ist.</span><span class="sxs-lookup"><span data-stu-id="9197b-114">Thrown when a required parameter is null</span></span>
            </exception>
      </Docs>
    </Member>
  </Members>
</Type>