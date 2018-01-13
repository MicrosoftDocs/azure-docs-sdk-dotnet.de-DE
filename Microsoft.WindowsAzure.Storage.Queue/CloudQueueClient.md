<Type Name="CloudQueueClient" FullName="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient">
  <TypeSignature Language="C#" Value="public class CloudQueueClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudQueueClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudQueueClient" />
  <TypeSignature Language="F#" Value="type CloudQueueClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Bietet eine clientseitige logische Darstellung des Microsoft Azure-Warteschlangendienst. Dieser Client wird verwendet, um zu konfigurieren und Ausführen von Anforderungen für den Warteschlangendienst.
            </summary>
    <remarks>Der Dienstclient kapselt den Endpunkt oder die Endpunkte für den Warteschlangendienst. Wenn der Dienstclient für den authentifizierten Zugriff verwendet wird, kapselt er auch die Anmeldeinformationen für den Zugriff auf das Speicherkonto an.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueClient (Microsoft.WindowsAzure.Storage.StorageUri storageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri storageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient (storageUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageUri" Type="Microsoft.WindowsAzure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="storageUri">Ein <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" /> Objekt, das den Warteschlangendienst-Endpunkt, mit der Erstellung des Clients enthält.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> -Klasse unter Verwendung der angegebenen Warteschlange-Endpunkt und der Kontoanmeldeinformationen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudQueueClient (Uri baseUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" Usage="new Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient (baseUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="baseUri">Die <see cref="T:System.Uri" /> , enthält den warteschlangendienstendpunkt zum Erstellen des Clients verwenden.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient" /> -Klasse unter Verwendung der angegebenen Warteschlange-Endpunkt und der Kontoanmeldeinformationen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationScheme">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.AuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationScheme As AuthenticationScheme" />
      <MemberSignature Language="F#" Value="member this.AuthenticationScheme : Microsoft.WindowsAzure.Storage.AuthenticationScheme with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.AuthenticationScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.AuthenticationScheme</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Authentifizierungsschema zum Signieren von HTTP-Anforderungen.
            </summary>
        <value>To be added.</value>
        <remarks>
            Diese Eigenschaft wird nur festgelegt, wenn Shared Key oder Shared Key Lite-Anmeldeinformationen verwendet werden; Es gilt nicht für die Authentifizierung über eine SAS oder anonymer Zugriff.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Basis-URI für den warteschlangendienstclient am primären Speicherort ab.
            </summary>
        <value>Ein <see cref="T:System.Uri" /> -Objekt für den warteschlangendienstclient am primären Standort.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceProperties (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceProperties (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceStats(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceStats (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceStats (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceStats(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceStats(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginGetServiceStats (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginListQueuesSegmented(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListQueuesSegmented (currentToken As QueueContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginListQueuesSegmented (currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListQueuesSegmented (prefix As String, currentToken As QueueContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginListQueuesSegmented (prefix, currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListQueuesSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginListQueuesSegmented (prefix, queueListingDetails, maxResults, currentToken, options, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</param>
        <param name="queueListingDetails">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetServiceProperties (properties As ServiceProperties, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginSetServiceProperties (properties, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudQueueClient.BeginSetServiceProperties (properties, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.IBufferManager BufferManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.IBufferManager BufferManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BufferManager" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferManager As IBufferManager" />
      <MemberSignature Language="F#" Value="member this.BufferManager : Microsoft.WindowsAzure.Storage.IBufferManager with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BufferManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.IBufferManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Puffer-Manager, die implementiert die <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> -Schnittstelle, einen zu verwendender Pufferpool mit Vorgängen für den warteschlangendienstclient angeben.
            </summary>
        <value>Ein Objekt vom Typ <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Auth.StorageCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Kontoanmeldeinformationen, die zum Erstellen der Warteschlangen-Dienstclient ab.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRequestOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions DefaultRequestOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions DefaultRequestOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.DefaultRequestOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRequestOptions As QueueRequestOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultRequestOptions : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions with get, set" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.DefaultRequestOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab und legt den Standardwert Anforderungsoptionen für über den Warteschlangen-Dienstclient vorgenommene Anforderungen.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndGetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceProperties (asyncResult As IAsyncResult) As ServiceProperties" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudQueueClient.EndGetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Das Ergebnis von einem vorherigen Aufruf für zurückgegeben <see cref="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndGetServiceStats(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceStats (asyncResult As IAsyncResult) As ServiceStats" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.EndGetServiceStats : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudQueueClient.EndGetServiceStats asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment EndListQueuesSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment EndListQueuesSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndListQueuesSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListQueuesSegmented (asyncResult As IAsyncResult) As QueueResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListQueuesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.EndListQueuesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.EndListQueuesSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.EndSetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetServiceProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetServiceProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetServiceProperties : IAsyncResult -&gt; unit" Usage="cloudQueueClient.EndSetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Die <see cref="T:System.IAsyncResult" /> zurückgegeben, die von einem vorherigen Aufruf für <see cref="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetQueueReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.CloudQueue GetQueueReference (string queueName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.CloudQueue GetQueueReference(string queueName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetQueueReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetQueueReference (queueName As String) As CloudQueue" />
      <MemberSignature Language="F#" Value="abstract member GetQueueReference : string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue&#xA;override this.GetQueueReference : string -&gt; Microsoft.WindowsAzure.Storage.Queue.CloudQueue" Usage="cloudQueueClient.GetQueueReference queueName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.CloudQueue</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="queueName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="queueName">Eine Zeichenfolge, die mit dem Namen der Warteschlange.</param>
        <summary>
            Gibt einen Verweis auf ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> Objekt mit dem angegebenen Namen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceProperties(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.GetServiceProperties : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudQueueClient.GetServiceProperties (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Ruft die Diensteigenschaften für den Warteschlangendienst ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> mit den Eigenschaften der Warteschlange.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServicePropertiesAsync () As Task(Of ServiceProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudQueueClient.GetServicePropertiesAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats GetServiceStats(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStats(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&#xA;override this.GetServiceStats : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" Usage="cloudQueueClient.GetServiceStats (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Ruft die dienststatistik für den sekundären Warteschlangendienst-Endpunkt ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServiceStatsAsync () As Task(Of ServiceStats)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.GetServiceStatsAsync(Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudQueueClient.GetServiceStatsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für den sekundärer Warteschlangendienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueues">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt; ListQueues (string prefix = null, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails = Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails.None, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt; ListQueues(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueues(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListQueues : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;&#xA;override this.ListQueues : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;" Usage="cloudQueueClient.ListQueues (prefix, queueListingDetails, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.Queue.CloudQueue&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</param>
        <param name="queueListingDetails">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumerationswert ab, der gibt an, welche Details in die Auflistung eingeschlossen werden sollen.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine aufzählbare Auflistung von Warteschlangen im Speicherkonto, deren Namen mit dem angegebenen Präfix beginnen und verzögert werden abgerufen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Objekten des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.CloudQueue" /> verzögert werden abgerufen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmented(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmented (currentToken As QueueContinuationToken) As QueueResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.ListQueuesSegmented : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.ListQueuesSegmented currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <summary>
            Gibt ein ergebnissegment mit einer Sammlung von Warteschlangen zurück.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmented (prefix As String, currentToken As QueueContinuationToken) As QueueResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.ListQueuesSegmented (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <summary>
            Gibt ein ergebnissegment mit einer Sammlung von Warteschlangen zurück.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment ListQueuesSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmented(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&#xA;override this.ListQueuesSegmented : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" Usage="cloudQueueClient.ListQueuesSegmented (prefix, queueListingDetails, maxResults, currentToken, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</param>
        <param name="queueListingDetails">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt. Wenn <c>null</c>, Standardoptionen gelten für die Anforderung.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt ein ergebnissegment mit einer Sammlung von Warteschlangen zurück.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmentedAsync (currentToken As QueueContinuationToken) As Task(Of QueueResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListQueuesSegmentedAsync (prefix As String, currentToken As QueueContinuationToken) As Task(Of QueueResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, queueListingDetails, maxResults, currentToken, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</param>
        <param name="queueListingDetails">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListQueuesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt; ListQueuesSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails queueListingDetails, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.ListQueuesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;&#xA;override this.ListQueuesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;" Usage="cloudQueueClient.ListQueuesSegmentedAsync (prefix, queueListingDetails, maxResults, currentToken, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="queueListingDetails" Type="Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix eines Warteschlangennamens.</param>
        <param name="queueListingDetails">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.Protocol.QueueListingDetails" /> -Enumeration, die in die Auflistung einzuschließenden Elemente beschreibt.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert null ist, ist die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Warteschlangen enthält.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void SetServiceProperties (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetServiceProperties(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServiceProperties(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetServiceProperties : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudQueueClient.SetServiceProperties (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Legt die Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetServicePropertiesAsync (properties As ServiceProperties) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync (properties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync (properties, options, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties,Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties * Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudQueueClient.SetServicePropertiesAsync (properties, options, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.WindowsAzure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Queue.QueueRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Warteschlangendienst.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die warteschlangendienstendpunkte sowohl für die primären und sekundären Speicherorte ab.
            </summary>
        <value>Ein Objekt des Typs <see cref="P:Microsoft.WindowsAzure.Storage.Queue.CloudQueueClient.StorageUri" /> mit Warteschlangen-URIs für die primären und sekundären Speicherorte.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>