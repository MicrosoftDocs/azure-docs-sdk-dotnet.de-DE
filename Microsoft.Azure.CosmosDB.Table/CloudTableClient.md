<Type Name="CloudTableClient" FullName="Microsoft.Azure.CosmosDB.Table.CloudTableClient">
  <TypeSignature Language="C#" Value="public class CloudTableClient" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudTableClient extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudTableClient" />
  <TypeSignature Language="F#" Value="type CloudTableClient = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
    <AssemblyVersion>0.9.0.0</AssemblyVersion>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            Bietet eine clientseitige logische Darstellung des Microsoft Azure-tabellendiensts. Dieser Client wird verwendet, um zu konfigurieren und Ausführen von Anforderungen für den Tabellendienst.
            </summary>
    <remarks>Der Dienstclient kapselt den Endpunkt oder die Endpunkte für den Tabellendienst. Wenn der Dienstclient für den authentifizierten Zugriff verwendet wird, kapselt er auch die Anmeldeinformationen für den Zugriff auf das Speicherkonto an.</remarks>
    <remarks>Das Objekt CloudTableClient kapselt den Basis-URI für den Tabellendienst. Wenn der Dienstclient für den authentifizierten Zugriff verwendet wird, kapselt er auch die Anmeldeinformationen für den Zugriff auf das Speicherkonto an.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTableClient (Microsoft.Azure.Storage.StorageUri storageUri, Microsoft.Azure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Storage.StorageUri storageUri, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.#ctor(Microsoft.Azure.Storage.StorageUri,Microsoft.Azure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTableClient : Microsoft.Azure.Storage.StorageUri * Microsoft.Azure.Storage.Auth.StorageCredentials -&gt; Microsoft.Azure.CosmosDB.Table.CloudTableClient" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTableClient (storageUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageUri" Type="Microsoft.Azure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="storageUri">Ein <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" /> Objekt, das den tabellendienstendpunkt verwenden Sie zum Erstellen des Clients enthält.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> -Klasse unter Verwendung der angegebenen Tabelle-Endpunkt und der Kontoanmeldeinformationen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTableClient (Uri baseUri, Microsoft.Azure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri baseUri, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.#ctor(System.Uri,Microsoft.Azure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (baseUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTableClient : Uri * Microsoft.Azure.Storage.Auth.StorageCredentials -&gt; Microsoft.Azure.CosmosDB.Table.CloudTableClient" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTableClient (baseUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="baseUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="baseUri">Ein <see cref="T:System.Uri" /> Objekt, das den tabellendienstendpunkt verwenden Sie zum Erstellen des Clients enthält.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> -Klasse unter Verwendung der angegebenen Tabelle-Endpunkt und der Kontoanmeldeinformationen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTableClient (Microsoft.Azure.Storage.StorageUri storageUri, Microsoft.Azure.Storage.Auth.StorageCredentials credentials, Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy connectionPolicy = null, Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt; desiredConsistencyLevel = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Storage.StorageUri storageUri, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials, class Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy connectionPolicy, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel&gt; desiredConsistencyLevel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.#ctor(Microsoft.Azure.Storage.StorageUri,Microsoft.Azure.Storage.Auth.StorageCredentials,Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy,System.Nullable{Microsoft.Azure.CosmosDB.ConsistencyLevel})" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTableClient : Microsoft.Azure.Storage.StorageUri * Microsoft.Azure.Storage.Auth.StorageCredentials * Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy * Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt; -&gt; Microsoft.Azure.CosmosDB.Table.CloudTableClient" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTableClient (storageUri, credentials, connectionPolicy, desiredConsistencyLevel)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="storageUri" Type="Microsoft.Azure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
        <Parameter Name="connectionPolicy" Type="Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" />
        <Parameter Name="desiredConsistencyLevel" Type="System.Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt;" />
      </Parameters>
      <Docs>
        <param name="storageUri">Ein <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" /> Objekt, das den tabellendienstendpunkt verwenden Sie zum Erstellen des Clients enthält.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <param name="connectionPolicy">
            (Optional) Die Verbindungsrichtlinie für den Client für die Tabelle. Wenn keine übergeben wird, wird der Standardwert verwendet.<see cref="T:Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" /></param>
        <param name="desiredConsistencyLevel">
            (Optional) Dies kann verwendet werden, um die Datenbank-Konto-konsistenzebene für Lesevorgänge herabzusetzen. Wenn dies nicht festgelegt ist wird die konsistenzebene für Datenbank-Konto für alle Anforderungen verwendet werden.
            </param>
        <summary>
            Initialisiert eine neue Instanz der dem <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> -Klasse unter Verwendung der angegebenen Tabelle-Endpunkt und der Kontoanmeldeinformationen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AuthenticationScheme">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.AuthenticationScheme AuthenticationScheme { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Storage.AuthenticationScheme AuthenticationScheme" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.AuthenticationScheme" />
      <MemberSignature Language="VB.NET" Value="Public Property AuthenticationScheme As AuthenticationScheme" />
      <MemberSignature Language="F#" Value="member this.AuthenticationScheme : Microsoft.Azure.Storage.AuthenticationScheme with get, set" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.AuthenticationScheme" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.AuthenticationScheme</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt das Authentifizierungsschema zum Signieren von HTTP-Anforderungen.
            </summary>
        <value>To be added.</value>
        <remarks>
          <para>Diese Eigenschaft wird nur festgelegt, wenn Shared Key oder Shared Key Lite-Anmeldeinformationen verwendet werden; Es gilt nicht für die Authentifizierung über eine SAS oder anonymer Zugriff.</para>
        </remarks>
      </Docs>
    </Member>
    <Member MemberName="BaseUri">
      <MemberSignature Language="C#" Value="public Uri BaseUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri BaseUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BaseUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BaseUri As Uri" />
      <MemberSignature Language="F#" Value="member this.BaseUri : Uri" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.BaseUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Uri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Basis-URI für den tabellendienstclient am primären Speicherort ab.
            </summary>
        <value>Ein <see cref="T:System.Uri" /> Objekt mit dem Basis-URI verwendet, um den tabellendienstclient am primären Standort erstellen.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceProperties (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceProperties (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceProperties (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceProperties (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceProperties(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceProperties(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceProperties : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceProperties : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceProperties (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceStats (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceStats(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceStats(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetServiceStats (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceStats (callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für die sekundärer Tabellenspeicherdienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceStats (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetServiceStats(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceStats(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetServiceStats : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetServiceStats : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginGetServiceStats (requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für die sekundärer Tabellenspeicherdienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginListTablesSegmented(Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListTablesSegmented (currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments von Tabellen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented (string prefix, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented(string prefix, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginListTablesSegmented(System.String,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginListTablesSegmented (prefix As String, currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (prefix, currentToken, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix des Tabellennamens.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments von Tabellen, die mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginListTablesSegmented(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginListTablesSegmented(System.String,System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginListTablesSegmented (prefix, maxResults, currentToken, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix des Tabellennamens.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="requestOptions">Die Server-Timeouts, maximale Ausführungszeit und wiederholungsrichtlinien für den Vorgang.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments von Tabellen, die mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetServiceProperties (properties As ServiceProperties, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginSetServiceProperties (properties, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetServiceProperties (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetServiceProperties(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTableClient.BeginSetServiceProperties (properties, requestOptions, operationContext, callback, state)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt an den Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BufferManager">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.IBufferManager BufferManager { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.IBufferManager BufferManager" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BufferManager" />
      <MemberSignature Language="VB.NET" Value="Public Property BufferManager As IBufferManager" />
      <MemberSignature Language="F#" Value="member this.BufferManager : Microsoft.Azure.Storage.IBufferManager with get, set" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.BufferManager" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.IBufferManager</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt einen Puffer-Manager, die implementiert die <see cref="T:Microsoft.Azure.Storage.IBufferManager" /> -Schnittstelle, einen zu verwendender Pufferpool mit Vorgängen für den tabellendienstclient angeben.
            </summary>
        <value>Ein Objekt vom Typ <see cref="T:Microsoft.Azure.Storage.IBufferManager" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConnectionPolicy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy ConnectionPolicy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy ConnectionPolicy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ConnectionPolicy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConnectionPolicy As TableConnectionPolicy" />
      <MemberSignature Language="F#" Value="member this.ConnectionPolicy : Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.ConnectionPolicy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableConnectionPolicy</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Die Verbindungsrichtlinie für den Client für die Tabelle
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ConsistencyLevel">
      <MemberSignature Language="C#" Value="public Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt; ConsistencyLevel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.ConsistencyLevel&gt; ConsistencyLevel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ConsistencyLevel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ConsistencyLevel As Nullable(Of ConsistencyLevel)" />
      <MemberSignature Language="F#" Value="member this.ConsistencyLevel : Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt;" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.ConsistencyLevel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;Microsoft.Azure.CosmosDB.ConsistencyLevel&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Für Lesevorgänge verwendet konsistenzebene
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Credentials">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.Auth.StorageCredentials Credentials { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.Auth.StorageCredentials Credentials" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.Credentials" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Credentials As StorageCredentials" />
      <MemberSignature Language="F#" Value="member this.Credentials : Microsoft.Azure.Storage.Auth.StorageCredentials" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.Credentials" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Auth.StorageCredentials</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Kontoanmeldeinformationen verwendet, um den tabellendienstclient zu erstellen.
            </summary>
        <value>Ein <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultRequestOptions">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.TableRequestOptions DefaultRequestOptions { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.TableRequestOptions DefaultRequestOptions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.DefaultRequestOptions" />
      <MemberSignature Language="VB.NET" Value="Public Property DefaultRequestOptions As TableRequestOptions" />
      <MemberSignature Language="F#" Value="member this.DefaultRequestOptions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions with get, set" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.DefaultRequestOptions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableRequestOptions</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Standardwert Anforderungsoptionen für über den tabellendienstclient vorgenommene Anforderungen.
            </summary>
        <value>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />-Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties EndGetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.EndGetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceProperties (asyncResult As IAsyncResult) As ServiceProperties" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceProperties : IAsyncResult -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.EndGetServiceProperties : IAsyncResult -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudTableClient.EndGetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Das Ergebnis von einem vorherigen Aufruf für zurückgegeben <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginGetServiceProperties(System.AsyncCallback,System.Object)" />.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Abrufen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats EndGetServiceStats(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.EndGetServiceStats(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetServiceStats (asyncResult As IAsyncResult) As ServiceStats" />
      <MemberSignature Language="F#" Value="abstract member EndGetServiceStats : IAsyncResult -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&#xA;override this.EndGetServiceStats : IAsyncResult -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" Usage="cloudTableClient.EndGetServiceStats asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für die sekundärer Tabellenspeicherdienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResultSegment EndListTablesSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResultSegment EndListTablesSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.EndListTablesSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndListTablesSegmented (asyncResult As IAsyncResult) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member EndListTablesSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment&#xA;override this.EndListTablesSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment" Usage="cloudTableClient.EndListTablesSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments von Tabellen. 
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void EndSetServiceProperties (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetServiceProperties(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.EndSetServiceProperties(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetServiceProperties (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetServiceProperties : IAsyncResult -&gt; unit&#xA;override this.EndSetServiceProperties : IAsyncResult -&gt; unit" Usage="cloudTableClient.EndSetServiceProperties asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Das von einem vorherigen Aufruf zurückgegebene Ergebnis<see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.BeginSetServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,System.AsyncCallback,System.Object)" /></param>
        <summary>
            Beendet einen asynchronen Vorgang zum Festlegen der Diensteigenschaften des tabellendiensts.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties GetServiceProperties(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceProperties(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceProperties : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&#xA;override this.GetServiceProperties : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" Usage="cloudTableClient.GetServiceProperties (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Ruft die Diensteigenschaften für den Tabellendienst ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServicePropertiesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServicePropertiesAsync () As Task(Of ServiceProperties)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServicePropertiesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServicePropertiesAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt; GetServicePropertiesAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServicePropertiesAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServicePropertiesAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;&#xA;override this.GetServicePropertiesAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;" Usage="cloudTableClient.GetServicePropertiesAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStats">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.Shared.Protocol.ServiceStats GetServiceStats (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats GetServiceStats(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceStats(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStats : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&#xA;override this.GetServiceStats : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" Usage="cloudTableClient.GetServiceStats (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.Shared.Protocol.ServiceStats</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Ruft die dienststatistik für den sekundären tabellendienstendpunkt ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceStatsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetServiceStatsAsync () As Task(Of ServiceStats)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für die sekundärer Tabellenspeicherdienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceStatsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für die sekundärer Tabellenspeicherdienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceStatsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync (requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für die sekundärer Tabellenspeicherdienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetServiceStatsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt; GetServiceStatsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetServiceStatsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetServiceStatsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;&#xA;override this.GetServiceStatsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;" Usage="cloudTableClient.GetServiceStatsAsync (requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Storage.Shared.Protocol.ServiceStats&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen von Statistiken zum Dienst für die sekundärer Tabellenspeicherdienst-Endpunkt an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceStats" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetTableReference">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.CloudTable GetTableReference (string tableName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.CloudTable GetTableReference(string tableName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.GetTableReference(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetTableReference (tableName As String) As CloudTable" />
      <MemberSignature Language="F#" Value="abstract member GetTableReference : string -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable&#xA;override this.GetTableReference : string -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="cloudTableClient.GetTableReference tableName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.CloudTable</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="tableName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="tableName">Eine Zeichenfolge, die mit dem Namen der Tabelle.</param>
        <summary>
            Ruft einen Verweis auf die angegebene Tabelle ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTables">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt; ListTables (string prefix = null, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.CosmosDB.Table.CloudTable&gt; ListTables(string prefix, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTables(System.String,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTables : string * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;&#xA;override this.ListTables : string * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;" Usage="cloudTableClient.ListTables (prefix, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.CloudTable&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix des Tabellennamens.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt eine aufzählbare Auflistung von Tabellen, die verzögert, abgerufen, die mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" /> Objekte, die verzögert abgerufen werden.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmented(Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmented (currentToken As TableContinuationToken) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment&#xA;override this.ListTablesSegmented : Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <summary>
            Gibt ein ergebnissegment von Tabellen zurück.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented (string prefix, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented(string prefix, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmented(System.String,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmented (prefix As String, currentToken As TableContinuationToken) As TableResultSegment" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment&#xA;override this.ListTablesSegmented : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix des Tabellennamens.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <summary>
            Gibt ein ergebnissegment von Tabellen, die verzögert, abgerufen, die mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResultSegment ListTablesSegmented(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmented(System.String,System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment&#xA;override this.ListTablesSegmented : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableResultSegment" Usage="cloudTableClient.ListTablesSegmented (prefix, maxResults, currentToken, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResultSegment</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix des Tabellennamens.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Gibt ein ergebnissegment von Tabellen, die verzögert, abgerufen, die mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmentedAsync (currentToken As TableContinuationToken) As Task(Of TableResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync currentToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments von Tabellen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments von Tabellen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ListTablesSegmentedAsync (prefix As String, currentToken As TableContinuationToken) As Task(Of TableResultSegment)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, currentToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix des Tabellennamens.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments von Tabellen, die mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, currentToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix des Tabellennamens.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments von Tabellen, die mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, maxResults, currentToken, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix des Tabellennamens.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="requestOptions">Die Server-Timeouts, maximale Ausführungszeit und wiederholungsrichtlinien für den Vorgang.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments von Tabellen, die mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListTablesSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync (string prefix, Nullable&lt;int&gt; maxResults, Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt; ListTablesSegmentedAsync(string prefix, valuetype System.Nullable`1&lt;int32&gt; maxResults, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken currentToken, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.ListTablesSegmentedAsync(System.String,System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;&#xA;override this.ListTablesSegmentedAsync : string * Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;" Usage="cloudTableClient.ListTablesSegmentedAsync (prefix, maxResults, currentToken, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResultSegment&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="prefix" Type="System.String" />
        <Parameter Name="maxResults" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="currentToken" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="prefix">Eine Zeichenfolge, enthält das Präfix des Tabellennamens.</param>
        <param name="maxResults">Ein nicht negativer ganzzahliger Wert, der die maximale Anzahl von gleichzeitig pro Vorgang gilt ein Grenzwert von 5000 zurückzugebenden Ergebnisse angibt. Wenn dieser Wert ist <c>null</c>, die maximale zulässige Anzahl von Ergebnissen wird sein (bis 5.000) zurückgegeben.</param>
        <param name="currentToken">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> von einem vorherigen Auflistungsvorgang zurückgegeben.</param>
        <param name="requestOptions">Die Server-Timeouts, maximale Ausführungszeit und wiederholungsrichtlinien für den Vorgang.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Zurückgeben eines ergebnissegments von Tabellen, die mit dem angegebenen Präfix beginnen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResultSegment" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServiceProperties">
      <MemberSignature Language="C#" Value="public virtual void SetServiceProperties (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetServiceProperties(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.SetServiceProperties(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.SetServiceProperties : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="cloudTableClient.SetServiceProperties (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Legt die Diensteigenschaften des tabellendiensts fest.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetServicePropertiesAsync (properties As ServiceProperties) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync properties" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, requestOptions, operationContext)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetServicePropertiesAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetServicePropertiesAsync (Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetServicePropertiesAsync(class Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties properties, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTableClient.SetServicePropertiesAsync(Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetServicePropertiesAsync : Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTableClient.SetServicePropertiesAsync (properties, requestOptions, operationContext, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>Microsoft.Azure.Storage.DoesServiceRequest</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="properties" Type="Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="properties">Ein <see cref="T:Microsoft.Azure.Storage.Shared.Protocol.ServiceProperties" />-Objekt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen der Diensteigenschaften des tabellendiensts.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.Azure.Storage.StorageUri" Usage="Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Storage.StorageUri</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die tabellendienstendpunkte für die primären und sekundären Speicherorte ab.
            </summary>
        <value>Ein Objekt des Typs <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTableClient.StorageUri" /> , das Tabellendienst-URIs für die primären und sekundären Speicherorte.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>