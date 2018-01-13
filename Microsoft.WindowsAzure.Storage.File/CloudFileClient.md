<Type Name="CloudFileClient" FullName="Microsoft.WindowsAzure.Storage.File.CloudFileClient">
  <TypeSignature Language="C#" Value="public class CloudFileClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudFileClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.File.CloudFileClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudFileClient" />
  <TypeSignature Language="F#" Value="type CloudFileClient = class" />
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
            Bietet eine clientseitige logische Darstellung des Microsoft Azure-dateidiensts an. Dieser Client wird verwendet, zu konfigurieren und Anforderungen für den Dienst auszuführen.
            </summary>
    <remarks>Der Dienstclient kapselt den Basis-URI für den Dateidienst an. Wenn der Dienstclient für den authentifizierten Zugriff verwendet wird, kapselt er auch die Anmeldeinformationen für den Zugriff auf das Speicherkonto an.</remarks>
    <remarks>Der Dienstclient kapselt den Basis-URI für den Dateidienst an. Wenn der Dienstclient für den authentifizierten Zugriff verwendet wird, kapselt er auch die Anmeldeinformationen für den Zugriff auf das Speicherkonto an.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileClient (Microsoft.WindowsAzure.Storage.StorageUri storageUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.StorageUri storageUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.#ctor(Microsoft.WindowsAzure.Storage.StorageUri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileClient : Microsoft.WindowsAzure.Storage.StorageUri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileClient" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileClient (storageUri, credentials)" />
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
        <param name="storageUri">Die Dateidienst-Endpunkt zu verwenden, um den Client zu erstellen.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileClient" /> -Klasse unter Verwendung der angegebenen Datei-Endpunkt und der Kontoanmeldeinformationen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudFileClient (Uri baseUri, Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.#ctor(System.Uri,Microsoft.WindowsAzure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.File.CloudFileClient : Uri * Microsoft.WindowsAzure.Storage.Auth.StorageCredentials -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileClient" Usage="new Microsoft.WindowsAzure.Storage.File.CloudFileClient (baseUri, credentials)" />
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
        <param name="baseUri">Die Dateidienst-Endpunkt zu verwenden, um den Client zu erstellen.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileClient" /> -Klasse unter Verwendung der angegebenen Datei-Endpunkt und der Kontoanmeldeinformationen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationScheme">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.WindowsAzure.Storage.AuthenticationScheme AuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.AuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationScheme As AuthenticationScheme" />
      <MemberSignature Language="F#" Value="member this.AuthenticationScheme : Microsoft.WindowsAzure.Storage.AuthenticationScheme with get, set" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.AuthenticationScheme" />
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
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.BaseUri" />
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
            Ruft den Basis-URI für den File-Dienstclient ab.
            </summary>
        <value>Die Basis-URI verwendet, um den File-Dienstclient erstellen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginGetServiceProperties (callback, state)" />
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
            Startet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginGetServiceProperties(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginGetServiceProperties (requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginListSharesSegmented(Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListSharesSegmented (currentToken As FileContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListSharesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListSharesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginListSharesSegmented (currentToken, callback, state)" />
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <param name="callback">Der Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, das eine Auflistung von Freigaben enthält.
            </summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented (string prefix, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginListSharesSegmented(System.String,Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListSharesSegmented (prefix As String, currentToken As FileContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginListSharesSegmented (prefix, currentToken, callback, state)" />
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix">Das Präfix des Freigabenamens.</param>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <param name="callback">Der Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, das eine Auflistung von Freigaben enthält.
            </summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented (string prefix, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginListSharesSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginListSharesSegmented(System.String,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginListSharesSegmented (prefix, detailsIncluded, maxResults, currentToken, options, operationContext, callback, state)" />
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
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix">Das Präfix des Freigabenamens.</param>
        <param name="detailsIncluded">Ein Wert, der angibt, ob die freigabemetadaten mit der Auflistung zurück.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von im ergebnissegment pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert null ist, ist die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Der Rückrufdelegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetServiceProperties (properties As FileServiceProperties, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginSetServiceProperties (properties, callback, state)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Dateidienst an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BeginSetServiceProperties(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="cloudFileClient.BeginSetServiceProperties (properties, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Dateidienst an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferManager">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.IBufferManager BufferManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.IBufferManager BufferManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.BufferManager" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferManager As IBufferManager" />
      <MemberSignature Language="F#" Value="member this.BufferManager : Microsoft.WindowsAzure.Storage.IBufferManager with get, set" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.BufferManager" />
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
            Ruft ab oder legt einen Puffer-Manager, die implementiert die <see cref="T:Microsoft.WindowsAzure.Storage.IBufferManager" /> -Schnittstelle, einen zu verwendender Pufferpool mit Vorgängen für den File-Dienstclient angeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.WindowsAzure.Storage.Auth.StorageCredentials" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.Credentials" />
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
            Ruft die Kontoanmeldeinformationen verwendet, um den File-Dienstclient erstellen.
            </summary>
        <value>Die Kontoanmeldeinformationen an.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRequestOptions">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.FileRequestOptions DefaultRequestOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.File.FileRequestOptions DefaultRequestOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.DefaultRequestOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRequestOptions As FileRequestOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultRequestOptions : Microsoft.WindowsAzure.Storage.File.FileRequestOptions with get, set" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.DefaultRequestOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.FileRequestOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Standardwert Anforderungsoptionen für über den File-Dienstclient vorgenommene Anforderungen.
            </summary>
        <value>Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties EndGetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties EndGetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.EndGetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceProperties (asyncResult As IAsyncResult) As FileServiceProperties" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&#xA;override this.EndGetServiceProperties : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" Usage="cloudFileClient.EndGetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.ShareResultSegment EndListSharesSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.ShareResultSegment EndListSharesSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.EndListSharesSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListSharesSegmented (asyncResult As IAsyncResult) As ShareResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListSharesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment&#xA;override this.EndListSharesSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment" Usage="cloudFileClient.EndListSharesSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.ShareResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments, das eine Auflistung von Freigaben enthält.
            </summary>
        <returns>Ein ergebnissegment von Freigaben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.EndSetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetServiceProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetServiceProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetServiceProperties : IAsyncResult -&gt; unit" Usage="cloudFileClient.EndSetServiceProperties asyncResult" />
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
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften für den Blob-Dienst an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties GetServiceProperties (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties GetServiceProperties(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetServiceProperties(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceProperties : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&#xA;override this.GetServiceProperties : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" Usage="cloudFileClient.GetServiceProperties (requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Ruft die Diensteigenschaften für den Dateidienst ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetServicePropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServicePropertiesAsync () As Task(Of FileServiceProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;" Usage="cloudFileClient.GetServicePropertiesAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetServicePropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;" Usage="cloudFileClient.GetServicePropertiesAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;" Usage="cloudFileClient.GetServicePropertiesAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;" Usage="cloudFileClient.GetServicePropertiesAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften für den Dateidienst an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShareReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.CloudFileShare GetShareReference (string shareName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.CloudFileShare GetShareReference(string shareName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetShareReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetShareReference (shareName As String) As CloudFileShare" />
      <MemberSignature Language="F#" Value="abstract member GetShareReference : string -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare&#xA;override this.GetShareReference : string -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="cloudFileClient.GetShareReference shareName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileShare</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shareName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="shareName">Eine Zeichenfolge, die mit dem Namen der Freigabe.</param>
        <summary>
            Gibt einen Verweis auf ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> Objekt mit dem angegebenen Namen.
            </summary>
        <returns>Ein Verweis auf eine Freigabe.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetShareReference">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.File.CloudFileShare GetShareReference (string shareName, Nullable&lt;DateTimeOffset&gt; snapshotTime);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.File.CloudFileShare GetShareReference(string shareName, valuetype System.Nullable`1&lt;valuetype System.DateTimeOffset&gt; snapshotTime) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.GetShareReference(System.String,System.Nullable{System.DateTimeOffset})" />
      <MemberSignature Language="VB.NET" Value="Public Function GetShareReference (shareName As String, snapshotTime As Nullable(Of DateTimeOffset)) As CloudFileShare" />
      <MemberSignature Language="F#" Value="member this.GetShareReference : string * Nullable&lt;DateTimeOffset&gt; -&gt; Microsoft.WindowsAzure.Storage.File.CloudFileShare" Usage="cloudFileClient.GetShareReference (shareName, snapshotTime)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.File.CloudFileShare</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="shareName" Type="System.String" />
        <Parameter Name="snapshotTime" Type="System.Nullable&lt;System.DateTimeOffset&gt;" />
      </Parameters>
      <Docs>
        <param name="shareName">Eine Zeichenfolge, die mit dem Namen der Freigabe.</param>
        <param name="snapshotTime">Ein <see cref="T:System.DateTimeOffset" /> den Momentaufnahme-Zeitstempel angeben, wenn die Freigabe eine Momentaufnahme ist.</param>
        <summary>
            Gibt einen Verweis auf ein <see cref="T:Microsoft.WindowsAzure.Storage.File.CloudFileShare" /> Objekt mit dem angegebenen Namen und eine momentaufnahmezeit.
            </summary>
        <returns>Ein Verweis auf eine Freigabe.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListShares">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; ListShares (string prefix = null, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded = Microsoft.WindowsAzure.Storage.File.ShareListingDetails.None, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt; ListShares(string prefix, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListShares(System.String,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListShares : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;&#xA;override this.ListShares : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;" Usage="cloudFileClient.ListShares (prefix, detailsIncluded, options, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.WindowsAzure.Storage.File.CloudFileShare&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">Das Präfix des Freigabenamens.</param>
        <param name="detailsIncluded">Ein Wert, der angibt, ob die freigabemetadaten mit der Auflistung zurück.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine aufzählbare Auflistung von Freigaben, die verzögert abgerufen werden, deren Namen mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Eine aufzählbare Auflistung von Freigaben, die verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmented(Microsoft.WindowsAzure.Storage.File.FileContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListSharesSegmented (currentToken As FileContinuationToken) As ShareResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment&#xA;override this.ListSharesSegmented : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment" Usage="cloudFileClient.ListSharesSegmented currentToken" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.ShareResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileContinuationToken" /> Token von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <summary>
            Gibt ein ergebnissegment mit einer Auflistung von Freigaben zurück.
            </summary>
        <returns>Ein ergebnissegment von Freigaben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented (string prefix, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented(string prefix, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmented(System.String,Microsoft.WindowsAzure.Storage.File.FileContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListSharesSegmented (prefix As String, currentToken As FileContinuationToken) As ShareResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment&#xA;override this.ListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment" Usage="cloudFileClient.ListSharesSegmented (prefix, currentToken)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.ShareResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Das Präfix des Freigabenamens.</param>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <summary>
            Gibt ein ergebnissegment mit einer Auflistung von Freigaben zurück.
            </summary>
        <returns>Ein ergebnissegment von Freigaben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented (string prefix, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.File.ShareResultSegment ListSharesSegmented(string prefix, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmented(System.String,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment&#xA;override this.ListSharesSegmented : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.File.ShareResultSegment" Usage="cloudFileClient.ListSharesSegmented (prefix, detailsIncluded, maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.File.ShareResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">Das Präfix des Freigabenamens.</param>
        <param name="detailsIncluded">Ein Wert, der angibt, ob die freigabemetadaten mit der Auflistung zurück.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von im ergebnissegment pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert null ist, ist die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt ein ergebnissegment mit einer Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein ergebnissegment von Freigaben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(Microsoft.WindowsAzure.Storage.File.FileContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListSharesSegmentedAsync (currentToken As FileContinuationToken) As Task(Of ShareResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync currentToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileContinuationToken" /> Token von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <summary>
            Gibt eine Aufgabe, die eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben ausführt.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync (currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileContinuationToken" /> Token von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Gibt eine Aufgabe, die eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben ausführt.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.File.FileContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListSharesSegmentedAsync (prefix As String, currentToken As FileContinuationToken) As Task(Of ShareResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync (prefix, currentToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Das Präfix des Freigabenamens.</param>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <summary>
            Gibt eine Aufgabe, die führt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(string prefix, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.File.FileContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync (prefix, currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Das Präfix des Freigabenamens.</param>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Gibt eine Aufgabe, die führt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync (prefix, detailsIncluded, maxResults, currentToken, options, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">Das Präfix des Freigabenamens.</param>
        <param name="detailsIncluded">Ein Wert, der angibt, ob die freigabemetadaten mit der Auflistung zurück.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von im ergebnissegment pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert null ist, ist die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine Aufgabe, die führt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListSharesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync (string prefix, Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, Nullable&lt;int&gt; maxResults, Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt; ListSharesSegmentedAsync(string prefix, valuetype Microsoft.WindowsAzure.Storage.File.ShareListingDetails detailsIncluded, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.WindowsAzure.Storage.File.FileContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions options, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.ListSharesSegmentedAsync(System.String,Microsoft.WindowsAzure.Storage.File.ShareListingDetails,System.Nullable{System.Int32},Microsoft.WindowsAzure.Storage.File.FileContinuationToken,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;&#xA;override this.ListSharesSegmentedAsync : string * Microsoft.WindowsAzure.Storage.File.ShareListingDetails * Nullable&lt;int&gt; * Microsoft.WindowsAzure.Storage.File.FileContinuationToken * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;" Usage="cloudFileClient.ListSharesSegmentedAsync (prefix, detailsIncluded, maxResults, currentToken, options, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.File.ShareResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="detailsIncluded" Type="Microsoft.WindowsAzure.Storage.File.ShareListingDetails" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.File.FileContinuationToken" />
        <Parameter Name="options" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Das Präfix des Freigabenamens.</param>
        <param name="detailsIncluded">Ein Wert, der angibt, ob die freigabemetadaten mit der Auflistung zurück.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von im ergebnissegment pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert null ist, ist die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken.</param>
        <param name="options">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Gibt eine Aufgabe, die führt eine asynchrone Anforderung zum Zurückgeben eines ergebnissegments, enthält eine Auflistung von Freigaben, deren Namen mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das den aktuellen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void SetServiceProperties (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetServiceProperties(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.SetServiceProperties(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit&#xA;override this.SetServiceProperties : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; unit" Usage="cloudFileClient.SetServiceProperties (properties, requestOptions, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Legt die Diensteigenschaften für den Dateidienst.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetServicePropertiesAsync (properties As FileServiceProperties) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties -&gt; System.Threading.Tasks.Task" Usage="cloudFileClient.SetServicePropertiesAsync properties" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, durch die Diensteigenschaften für den Blob-Dienst festgelegt.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileClient.SetServicePropertiesAsync (properties, cancellationToken)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, durch die Diensteigenschaften für den Blob-Dienst festgelegt.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudFileClient.SetServicePropertiesAsync (properties, requestOptions, operationContext)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, der Diensteigenschaften für den Dateidienst festlegt.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties properties, class Microsoft.WindowsAzure.Storage.File.FileRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.File.CloudFileClient.SetServicePropertiesAsync(Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties,Microsoft.WindowsAzure.Storage.File.FileRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties * Microsoft.WindowsAzure.Storage.File.FileRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudFileClient.SetServicePropertiesAsync (properties, requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="properties" Type="Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.File.FileRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.Protocol.FileServiceProperties" />-Objekt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.File.FileRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, der Diensteigenschaften für den Dateidienst festlegt.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.File.CloudFileClient.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.WindowsAzure.Storage.StorageUri" Usage="Microsoft.WindowsAzure.Storage.File.CloudFileClient.StorageUri" />
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
            Ruft die Liste der URIs für alle Speicherorte ab.
            </summary>
        <value>Die Liste der URIs für alle Speicherorte.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>