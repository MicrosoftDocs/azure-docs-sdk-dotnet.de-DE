<Type Name="BatchRequestBase&lt;TOptions,TResponse&gt;" FullName="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;TOptions,TResponse&gt;">
  <TypeSignature Language="C#" Value="public abstract class BatchRequestBase&lt;TOptions,TResponse&gt; : Microsoft.Azure.Batch.Protocol.IBatchRequest&lt;TResponse&gt; where TOptions : IOptionsnew() where TResponse : IAzureOperationResponse" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract beforefieldinit BatchRequestBase`2&lt;.ctor (class Microsoft.Azure.Batch.Protocol.Models.IOptions) TOptions, (class Microsoft.Rest.Azure.IAzureOperationResponse) TResponse&gt; extends System.Object implements class Microsoft.Azure.Batch.Protocol.IBatchRequest, class Microsoft.Azure.Batch.Protocol.IBatchRequest`1&lt;!TResponse&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2" />
  <TypeSignature Language="VB.NET" Value="Public MustInherit Class BatchRequestBase(Of TOptions, TResponse)&#xA;Implements IBatchRequest(Of TResponse)" />
  <TypeSignature Language="F#" Value="type BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; IAzureOperationResponse)&gt; = class&#xA;    interface IBatchRequest&lt;'Response (requires 'Response :&gt; IAzureOperationResponse)&gt;&#xA;    interface IBatchRequest" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TOptions">
      <Constraints>
        <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
        <InterfaceName>Microsoft.Azure.Batch.Protocol.Models.IOptions</InterfaceName>
      </Constraints>
    </TypeParameter>
    <TypeParameter Name="TResponse">
      <Constraints>
        <InterfaceName>Microsoft.Rest.Azure.IAzureOperationResponse</InterfaceName>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.IBatchRequest&lt;TResponse&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TOptions">Der Typ der Parameter übergeben außerhalb der Hauptteil der Anforderung mit der Anforderung verknüpft ist.</typeparam>
    <typeparam name="TResponse">Der Antworttyp aus der Anforderung erwartet.</typeparam>
    <summary>
            Eine Basisklasse für alle Anforderungen der Batch-Dienst. Stellt die erforderlichen Informationen an einen bestimmten Aufruf mit keinen Anforderungstext an der Batch-Dienst-REST-API vornehmen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="protected BatchRequestBase (Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Batch.Protocol.BatchServiceClient restClient, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.#ctor(Microsoft.Azure.Batch.Protocol.BatchServiceClient,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt; : Microsoft.Azure.Batch.Protocol.BatchServiceClient * System.Threading.CancellationToken -&gt; Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;" Usage="new Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt; (restClient, cancellationToken)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="restClient" Type="Microsoft.Azure.Batch.Protocol.BatchServiceClient" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="restClient">Der REST-Client verwendet werden soll.</param>
        <param name="cancellationToken">Das CancellationToken verwenden.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CancellationToken">
      <MemberSignature Language="C#" Value="public System.Threading.CancellationToken CancellationToken { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Threading.CancellationToken CancellationToken" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.CancellationToken" />
      <MemberSignature Language="VB.NET" Value="Public Property CancellationToken As CancellationToken" />
      <MemberSignature Language="F#" Value="member this.CancellationToken : System.Threading.CancellationToken with get, set" Usage="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.CancellationToken" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.IBatchRequest.CancellationToken</InterfaceMember>
      </Implements>
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
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.CancellationToken" /> zugeordnete <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Dieses Token abgebrochen wird die gerade laufende Anforderung abgebrochen. Dies gilt für die ursprüngliche Anforderung sowie alle nachfolgenden Anforderungen aufgrund von erstellt <see cref="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.RetryPolicy" />. Dieses Token wird abgebrochen. alle zukünftige Wiederholungen dieses auch verbietet <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.
            </para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientRequestIdProvider">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.ClientRequestIdProvider ClientRequestIdProvider { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.ClientRequestIdProvider ClientRequestIdProvider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.ClientRequestIdProvider" />
      <MemberSignature Language="VB.NET" Value="Public Property ClientRequestIdProvider As ClientRequestIdProvider" />
      <MemberSignature Language="F#" Value="member this.ClientRequestIdProvider : Microsoft.Azure.Batch.ClientRequestIdProvider with get, set" Usage="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.ClientRequestIdProvider" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.IBatchRequest.ClientRequestIdProvider</InterfaceMember>
      </Implements>
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
            Ruft ab oder legt die <see cref="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.ClientRequestIdProvider" /> von dieser Anforderung zum Generieren von Client-Request-Ids verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomHeaders">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.Dictionary&lt;string,System.Collections.Generic.List&lt;string&gt;&gt; CustomHeaders { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.Dictionary`2&lt;string, class System.Collections.Generic.List`1&lt;string&gt;&gt; CustomHeaders" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.CustomHeaders" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomHeaders As Dictionary(Of String, List(Of String))" />
      <MemberSignature Language="F#" Value="member this.CustomHeaders : System.Collections.Generic.Dictionary&lt;string, System.Collections.Generic.List&lt;string&gt;&gt;" Usage="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.CustomHeaders" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.Dictionary&lt;System.String,System.Collections.Generic.List&lt;System.String&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Header für die Anforderung verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteRequestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TResponse&gt; ExecuteRequestAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TResponse&gt; ExecuteRequestAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.ExecuteRequestAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteRequestAsync () As Task(Of TResponse)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteRequestAsync : unit -&gt; System.Threading.Tasks.Task&lt;'Response (requires 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;&#xA;override this.ExecuteRequestAsync : unit -&gt; System.Threading.Tasks.Task&lt;'Response (requires 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;" Usage="batchRequestBase.ExecuteRequestAsync " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:Microsoft.Azure.Batch.Protocol.IBatchRequest`1.ExecuteRequestAsync</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.Protocol.BatchRequestBase`2/&lt;ExecuteRequestAsync&gt;d__40))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Führt die Anforderung.
            </summary>
        <returns>Einen asynchronen Vorgang des Rückgabetyps <typeparamref name="TResponse" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Microsoft.Azure.Batch.Protocol.IBatchRequest.Options">
      <MemberSignature Language="C#" Value="Microsoft.Azure.Batch.Protocol.Models.IOptions Microsoft.Azure.Batch.Protocol.IBatchRequest.Options { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.Models.IOptions Microsoft.Azure.Batch.Protocol.IBatchRequest.Options" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.Microsoft#Azure#Batch#Protocol#IBatchRequest#Options" />
      <MemberSignature Language="VB.NET" Value=" ReadOnly Property Options As IOptions Implements IBatchRequest.Options" />
      <MemberSignature Language="F#" Usage="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.Microsoft.Azure.Batch.Protocol.IBatchRequest.Options" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.IBatchRequest.Options</InterfaceMember>
      </Implements>
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
            Ruft die Optionen, die erforderlich sind, durch die REST-Proxy für die aktuelle Anforderung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperationContext">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.OperationContext OperationContext { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Common.OperationContext OperationContext" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.OperationContext" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperationContext As OperationContext" />
      <MemberSignature Language="F#" Value="member this.OperationContext : Microsoft.Azure.Batch.Common.OperationContext" Usage="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.OperationContext" />
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
            Ruft den Vorgangskontext zugeordnete <see cref="T:Microsoft.Azure.Batch.Protocol.IBatchRequest" />.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Options">
      <MemberSignature Language="C#" Value="public TOptions Options { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !TOptions Options" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.Options" />
      <MemberSignature Language="VB.NET" Value="Public Property Options As TOptions" />
      <MemberSignature Language="F#" Value="member this.Options : 'Options with get, set" Usage="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.Options" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>TOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Optionen für die Anforderung verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Protocol.BatchServiceClient RestClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Protocol.BatchServiceClient RestClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.RestClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RestClient As BatchServiceClient" />
      <MemberSignature Language="F#" Value="member this.RestClient : Microsoft.Azure.Batch.Protocol.BatchServiceClient" Usage="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.RestClient" />
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
            Ruft den REST-Client, der für diese Anforderung verwendet werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RetryPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Batch.Common.IRetryPolicy RetryPolicy { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Batch.Common.IRetryPolicy RetryPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.RetryPolicy" />
      <MemberSignature Language="VB.NET" Value="Public Property RetryPolicy As IRetryPolicy" />
      <MemberSignature Language="F#" Value="member this.RetryPolicy : Microsoft.Azure.Batch.Common.IRetryPolicy with get, set" Usage="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.RetryPolicy" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.IBatchRequest.RetryPolicy</InterfaceMember>
      </Implements>
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
            Ruft ab oder legt die wiederholungsrichtlinie angewendet werden.
            NULL bedeutet, dass keine Wiederholungsversuche unternommen werden.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceRequestFunc">
      <MemberSignature Language="C#" Value="public Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;TResponse&gt;&gt; ServiceRequestFunc { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Func`2&lt;valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task`1&lt;!TResponse&gt;&gt; ServiceRequestFunc" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.ServiceRequestFunc" />
      <MemberSignature Language="VB.NET" Value="Public Property ServiceRequestFunc As Func(Of CancellationToken, Task(Of TResponse))" />
      <MemberSignature Language="F#" Value="member this.ServiceRequestFunc : Func&lt;System.Threading.CancellationToken, System.Threading.Tasks.Task&lt;'Response&gt;&gt; with get, set" Usage="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.ServiceRequestFunc" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Func&lt;System.Threading.CancellationToken,System.Threading.Tasks.Task&lt;TResponse&gt;&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Funktion die erstellen, wird eine <see cref="T:System.Threading.Tasks.Task" /> der Batch-Dienst aufgerufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ThrowIfRequestExecutionHasStarted">
      <MemberSignature Language="C#" Value="protected void ThrowIfRequestExecutionHasStarted ();" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig instance void ThrowIfRequestExecutionHasStarted() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.ThrowIfRequestExecutionHasStarted" />
      <MemberSignature Language="VB.NET" Value="Protected Sub ThrowIfRequestExecutionHasStarted ()" />
      <MemberSignature Language="F#" Value="member this.ThrowIfRequestExecutionHasStarted : unit -&gt; unit" Usage="batchRequestBase.ThrowIfRequestExecutionHasStarted " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Löst eine Ausnahme aus, wenn die die anforderungsausführung gestartet hat.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Timeout">
      <MemberSignature Language="C#" Value="public TimeSpan Timeout { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.TimeSpan Timeout" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.Protocol.BatchRequestBase`2.Timeout" />
      <MemberSignature Language="VB.NET" Value="Public Property Timeout As TimeSpan" />
      <MemberSignature Language="F#" Value="member this.Timeout : TimeSpan with get, set" Usage="Microsoft.Azure.Batch.Protocol.BatchRequestBase&lt;'Options, 'Response (requires 'Options :&gt; Microsoft.Azure.Batch.Protocol.Models.IOptions and 'Options : (new : unit -&gt; 'Options) and 'Response :&gt; Microsoft.Rest.Azure.IAzureOperationResponse)&gt;.Timeout" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:Microsoft.Azure.Batch.Protocol.IBatchRequest.Timeout</InterfaceMember>
      </Implements>
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
            Ruft ab oder legt die clientseitiges Timeout für eine Anforderung an den Batch-Dienst.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>
            Dieses Timeout gilt für eine einzelne Anforderung des Batch-Dienst. Wenn eine wiederholungsrichtlinie angegeben wird, wird jeder Wiederholung der vollständigen Dauer dieses Werts gewährt werden.
            </para>
        </remarks>
      </Docs>
    </Member>
  </Members>
</Type>