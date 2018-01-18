<Type Name="IBatchRequest" FullName="Microsoft.Azure.Batch.Protocol.IBatchRequest">
  <TypeSignature Language="C#" Value="public interface IBatchRequest" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBatchRequest" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBatchRequest" />
  <TypeSignature Language="F#" Value="type IBatchRequest = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="7c92f-101">Stellt eine Anforderung an den Batch-Dienst an.</span><span class="sxs-lookup"><span data-stu-id="7c92f-101">Represents a request to the Batch service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="CancellationToken">
      <MemberSignature Language="C#" Value="public System.Threading.CancellationToken CancellationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Threading.CancellationToken CancellationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.CancellationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property CancellationToken As CancellationToken" />
      <MemberSignature Language="F#" Value="member this.CancellationToken : System.Threading.CancellationToken with get, set" Usage="Microsoft.Azure.Batch.Protocol.IBatchRequest.CancellationToken" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.CancellationToken</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c92f-102">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.CancellationToken" /> zugeordnete <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.</span><span class="sxs-lookup"><span data-stu-id="7c92f-102">Gets or sets the <see cref="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.CancellationToken" /> associated with this <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="7c92f-103">Dieses Token abgebrochen wird die gerade laufende Anforderung abgebrochen.</span><span class="sxs-lookup"><span data-stu-id="7c92f-103">Cancelling this token will cancel the currently ongoing request.</span></span> <span data-ttu-id="7c92f-104">Dies gilt für die ursprüngliche Anforderung sowie alle nachfolgenden Anforderungen aufgrund von erstellt <see cref="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.RetryPolicy" />.</span><span class="sxs-lookup"><span data-stu-id="7c92f-104">This applies to the initial request as well as any subsequent requests created due to <see cref="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.RetryPolicy" />.</span></span> <span data-ttu-id="7c92f-105">Dieses Token wird abgebrochen. alle zukünftige Wiederholungen dieses auch verbietet <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.</span><span class="sxs-lookup"><span data-stu-id="7c92f-105">Cancelling this token also forbids all future retries of this <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestIdProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ClientRequestIdProvider ClientRequestIdProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ClientRequestIdProvider ClientRequestIdProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.ClientRequestIdProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestIdProvider As ClientRequestIdProvider" />
      <MemberSignature Language="F#" Value="member this.ClientRequestIdProvider : Microsoft.Azure.Batch.ClientRequestIdProvider with get, set" Usage="Microsoft.Azure.Batch.Protocol.IBatchRequest.ClientRequestIdProvider" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.ClientRequestIdProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c92f-106">Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.ClientRequestIdProvider" /> von dieser Anforderung zum Generieren von Client-Request-Ids verwendet.</span><span class="sxs-lookup"><span data-stu-id="7c92f-106">Gets or sets the <see cref="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.ClientRequestIdProvider" /> used by this request to generate client request ids.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationContext">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.OperationContext OperationContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Common.OperationContext OperationContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.OperationContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationContext As OperationContext" />
      <MemberSignature Language="F#" Value="member this.OperationContext : Microsoft.Azure.Batch.Common.OperationContext" Usage="Microsoft.Azure.Batch.Protocol.IBatchRequest.OperationContext" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.OperationContext</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c92f-107">Ruft den Vorgangskontext zugeordnete <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.</span><span class="sxs-lookup"><span data-stu-id="7c92f-107">Gets the operation context associated with this <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Options">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.Models.IOptions Options { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.IOptions Options" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.Options" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Options As IOptions" />
      <MemberSignature Language="F#" Value="member this.Options : Microsoft.Azure.Batch.Protocol.Models.IOptions" Usage="Microsoft.Azure.Batch.Protocol.IBatchRequest.Options" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.Models.IOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c92f-108">Ruft die Optionen, die erforderlich sind, durch die REST-Proxy für die aktuelle Anforderung ab.</span><span class="sxs-lookup"><span data-stu-id="7c92f-108">Gets the options needed by the REST proxy for the current request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.BatchServiceClient RestClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.BatchServiceClient RestClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.RestClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestClient As BatchServiceClient" />
      <MemberSignature Language="F#" Value="member this.RestClient : Microsoft.Azure.Batch.Protocol.BatchServiceClient" Usage="Microsoft.Azure.Batch.Protocol.IBatchRequest.RestClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Protocol.BatchServiceClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c92f-109">Ruft den REST-Client, der für diese Anforderung verwendet werden.</span><span class="sxs-lookup"><span data-stu-id="7c92f-109">Gets the REST client that will be used for this request.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Common.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.Batch.Common.IRetryPolicy with get, set" Usage="Microsoft.Azure.Batch.Protocol.IBatchRequest.RetryPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Batch.Common.IRetryPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c92f-110">Ruft ab oder legt die wiederholungsrichtlinie angewendet werden.</span><span class="sxs-lookup"><span data-stu-id="7c92f-110">Gets or sets the retry policy to be applied.</span></span>
            <span data-ttu-id="7c92f-111">NULL bedeutet, dass keine Wiederholungsversuche unternommen werden.</span><span class="sxs-lookup"><span data-stu-id="7c92f-111">Null means no retries will be attempted.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public TimeSpan Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.IBatchRequest.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Timeout : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.IBatchRequest.Timeout" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.TimeSpan</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="7c92f-112">Ruft ab oder legt die clientseitiges Timeout für eine Anforderung an den Batch-Dienst.</span><span class="sxs-lookup"><span data-stu-id="7c92f-112">Gets or sets the client side timeout for a request to the Batch service.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            <span data-ttu-id="7c92f-113">Dieses Timeout gilt für eine einzelne Anforderung des Batch-Dienst. Wenn eine wiederholungsrichtlinie angegeben wird, wird jeder Wiederholung der vollständigen Dauer dieses Werts gewährt werden.</span><span class="sxs-lookup"><span data-stu-id="7c92f-113">This timeout applies to a single Batch service request; if a retry policy is specified, then each retry will be granted the full duration of this value.</span></span>
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>