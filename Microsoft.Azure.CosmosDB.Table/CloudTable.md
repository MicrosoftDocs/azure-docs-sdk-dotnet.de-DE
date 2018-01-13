<Type Name="CloudTable" FullName="Microsoft.Azure.CosmosDB.Table.CloudTable">
  <TypeSignature Language="C#" Value="public class CloudTable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit CloudTable extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />
  <TypeSignature Language="VB.NET" Value="Public Class CloudTable" />
  <TypeSignature Language="F#" Value="type CloudTable = class" />
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
            Stellt eine Microsoft Azure-Tabelle dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Uri tableAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri tableAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.#ctor(System.Uri)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAddress As Uri)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTable : Uri -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTable tableAddress" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAddress" Type="System.Uri" />
      </Parameters>
      <Docs>
        <param name="tableAddress">Ein <see cref="T:System.Uri" /> den absoluten URI zur Tabelle angeben.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Microsoft.Azure.Storage.StorageUri tableAddress, Microsoft.Azure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.Azure.Storage.StorageUri tableAddress, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.#ctor(Microsoft.Azure.Storage.StorageUri,Microsoft.Azure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAddress As StorageUri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTable : Microsoft.Azure.Storage.StorageUri * Microsoft.Azure.Storage.Auth.StorageCredentials -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTable (tableAddress, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAddress" Type="Microsoft.Azure.Storage.StorageUri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="tableAddress">Ein <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" /> , den absoluten URI der Tabelle auf dem primären und sekundären Speicherorte enthält.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public CloudTable (Uri tableAbsoluteUri, Microsoft.Azure.Storage.Auth.StorageCredentials credentials);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class System.Uri tableAbsoluteUri, class Microsoft.Azure.Storage.Auth.StorageCredentials credentials) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.#ctor(System.Uri,Microsoft.Azure.Storage.Auth.StorageCredentials)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (tableAbsoluteUri As Uri, credentials As StorageCredentials)" />
      <MemberSignature Language="F#" Value="new Microsoft.Azure.CosmosDB.Table.CloudTable : Uri * Microsoft.Azure.Storage.Auth.StorageCredentials -&gt; Microsoft.Azure.CosmosDB.Table.CloudTable" Usage="new Microsoft.Azure.CosmosDB.Table.CloudTable (tableAbsoluteUri, credentials)" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters>
        <Parameter Name="tableAbsoluteUri" Type="System.Uri" />
        <Parameter Name="credentials" Type="Microsoft.Azure.Storage.Auth.StorageCredentials" />
      </Parameters>
      <Docs>
        <param name="tableAbsoluteUri">Ein <see cref="T:System.Uri" /> den absoluten URI zur Tabelle angeben.</param>
        <param name="credentials">Ein <see cref="T:Microsoft.Azure.Storage.Auth.StorageCredentials" />-Objekt.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreate (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (requestOptions, operationContext, callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Nullable{Microsoft.Azure.CosmosDB.IndexingMode},System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (requestOptions, operationContext, indexingMode, throughput, callback, state)" />
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
        <Parameter Name="indexingMode" Type="System.Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt;" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="indexingMode">Geben Sie indizierungsmodus für CosmosDB-Tabelle</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreate">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreate(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreate(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreate : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreate (requestOptions, operationContext, serializedIndexingPolicy, throughput, callback, state)" />
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
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="serializedIndexingPolicy">CosmosDB Tabelle indizierungsrichtlinie</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginCreateIfNotExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.Azure.CosmosDB.IndexingMode indexingMode, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(Microsoft.Azure.CosmosDB.IndexingMode,System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (indexingMode, throughput, callback, state)" />
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
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="indexingMode">CosmosDB Tabelle indizierungsmodus</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (requestOptions, operationContext, callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginCreateIfNotExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginCreateIfNotExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginCreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginCreateIfNotExists (requestOptions, operationContext, serializedIndexingPolicy, throughput, callback, state)" />
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
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="serializedIndexingPolicy">CosmosDB Tabelle indizierungsrichtlinie</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDelete(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDelete (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDelete (callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Löschen einer Tabelle an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDelete">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDelete(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDelete(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDelete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDelete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDelete (requestOptions, operationContext, callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Löschen einer Tabelle an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDeleteIfExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginDeleteIfExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDeleteIfExists (callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginDeleteIfExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginDeleteIfExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginDeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginDeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginDeleteIfExists (requestOptions, operationContext, callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute (Microsoft.Azure.CosmosDB.Table.TableOperation operation, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecute(Microsoft.Azure.CosmosDB.Table.TableOperation,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecute (operation As TableOperation, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecute (operation, callback, state)" />
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
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operation">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt die Ausführung eines asynchronen Tabelle-Vorgangs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecute(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecute(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecute (operation, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="operation">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt die Ausführung eines asynchronen Tabelle-Vorgangs.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteBatch(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteBatch (batch As TableBatchOperation, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteBatch (batch, callback, state)" />
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
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="batch">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteBatch(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteBatch(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteBatch (batch, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="batch">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQueryForKeyRotationSegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQueryForKeyRotationSegmented (query As TableQuery, token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQueryForKeyRotationSegmented (query, token, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone segmentierte Abfrage für eine Tabelle an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQueryForKeyRotationSegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQueryForKeyRotationSegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQueryForKeyRotationSegmented (query, token, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone segmentierte Abfrage für eine Tabelle an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented (query As TableQuery, token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone segmentierte Abfrage für eine Tabelle an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone segmentierte Abfrage für eine Tabelle an.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TElement As {ITableEntityNew}) (query As TableQuery(Of TElement), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, token, requestOptions, operationContext, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TResult) (query As TableQuery, resolver As EntityResolver(Of TResult), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz unter Angabe der Tabelle Abfragen ausgeführt und die Abfrageparameter verwendet.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteQuerySegmented(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (query As TableQuery(Of TElement), resolver As EntityResolver(Of TResult), token As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExecuteQuerySegmented``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.BeginExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.BeginExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext, callback, state)" />
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
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExists(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExists (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExists (callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExists">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginExists (requestOptions, operationContext, callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginGetPermissions(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginGetPermissions (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginGetPermissions (callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung an die berechtigungseinstellungen für die Tabelle zu erhalten.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginGetPermissions(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginGetPermissions(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginGetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginGetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginGetPermissions (requestOptions, operationContext, callback, state)" />
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung an die berechtigungseinstellungen für die Tabelle zu erhalten.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginSetPermissions(Microsoft.Azure.CosmosDB.Table.TablePermissions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginSetPermissions (permissions As TablePermissions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginSetPermissions (permissions, callback, state)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung zum Festlegen von Berechtigungen für die Tabelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Storage.ICancellableAsyncResult BeginSetPermissions(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.BeginSetPermissions(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult&#xA;override this.BeginSetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.Azure.Storage.ICancellableAsyncResult" Usage="cloudTable.BeginSetPermissions (permissions, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="permissions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Beginnt eine asynchrone Anforderung zum Festlegen von Berechtigungen für die Tabelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.Storage.ICancellableAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.CosmosDB.IndexingMode&gt; indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Create(System.Nullable{Microsoft.Azure.CosmosDB.IndexingMode},System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub Create (indexingMode As Nullable(Of IndexingMode), Optional throughput As Nullable(Of Integer) = null)" />
      <MemberSignature Language="F#" Value="abstract member Create : Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; -&gt; unit&#xA;override this.Create : Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt; * Nullable&lt;int&gt; -&gt; unit" Usage="cloudTable.Create (indexingMode, throughput)" />
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
        <Parameter Name="indexingMode" Type="System.Nullable&lt;Microsoft.Azure.CosmosDB.IndexingMode&gt;" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="indexingMode">Geben Sie indizierungsmodus für CosmosDB-Tabelle</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <summary>
            Erstellt eine Tabelle.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Create">
      <MemberSignature Language="C#" Value="public virtual void Create (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null, string serializedIndexingPolicy = null, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Create(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Create(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="abstract member Create : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; unit&#xA;override this.Create : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; unit" Usage="cloudTable.Create (requestOptions, operationContext, serializedIndexingPolicy, throughput)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="serializedIndexingPolicy">CosmosDB Tabelle indizierungsrichtlinie</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <summary>
            Erstellt eine Tabelle.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Nullable&lt;int&gt; throughput, Microsoft.Azure.CosmosDB.IndexingMode indexingMode, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(System.Nullable{System.Int32},Microsoft.Azure.CosmosDB.IndexingMode,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.IndexingMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Nullable&lt;int&gt; * Microsoft.Azure.CosmosDB.IndexingMode * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (throughput, indexingMode, cancellationToken)" />
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
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <param name="indexingMode">Geben Sie indizierungsmodus für CosmosDB-Tabelle</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Nullable&lt;int&gt; throughput, string serializedindexingPolicy, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(valuetype System.Nullable`1&lt;int32&gt; throughput, string serializedindexingPolicy, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(System.Nullable{System.Int32},System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Nullable&lt;int&gt; * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (throughput, serializedindexingPolicy, cancellationToken)" />
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
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="serializedindexingPolicy" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <param name="serializedindexingPolicy">CosmosDB Tabelle indizierungsrichtlinie</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task CreateAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task CreateAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.CreateAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.CreateAsync (requestOptions, operationContext, serializedIndexingPolicy, throughput, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="serializedIndexingPolicy">CosmosDB Tabelle indizierungsrichtlinie</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.Azure.CosmosDB.IndexingMode indexingMode, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExists(Microsoft.Azure.CosmosDB.IndexingMode,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; -&gt; bool" Usage="cloudTable.CreateIfNotExists (indexingMode, throughput)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="indexingMode">CosmosDB Tabelle indizierungsmodus</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <summary>
            Erstellt die Tabelle aus, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn Tabelle erstellt; andernfalls wurde, <c>"false"</c>.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool CreateIfNotExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null, string serializedIndexingPolicy = null, Nullable&lt;int&gt; throughput = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool CreateIfNotExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32})" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; bool&#xA;override this.CreateIfNotExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; -&gt; bool" Usage="cloudTable.CreateIfNotExists (requestOptions, operationContext, serializedIndexingPolicy, throughput)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="serializedIndexingPolicy">CosmosDB Tabelle indizierungsrichtlinie</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <summary>
            Erstellt die Tabelle aus, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn Tabelle erstellt; andernfalls wurde, <c>"false"</c>.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateIfNotExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.IndexingMode indexingMode, Nullable&lt;int&gt; throughput, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(valuetype Microsoft.Azure.CosmosDB.IndexingMode indexingMode, valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.IndexingMode,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.IndexingMode * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (indexingMode, throughput, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="indexingMode" Type="Microsoft.Azure.CosmosDB.IndexingMode" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="indexingMode">CosmosDB Tabelle indizierungsmodus</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
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
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateIfNotExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; CreateIfNotExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, Nullable&lt;int&gt; throughput, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; CreateIfNotExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, string serializedIndexingPolicy, valuetype System.Nullable`1&lt;int32&gt; throughput, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateIfNotExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.String,System.Nullable{System.Int32},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.CreateIfNotExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * string * Nullable&lt;int&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.CreateIfNotExistsAsync (requestOptions, operationContext, serializedIndexingPolicy, throughput, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="serializedIndexingPolicy" Type="System.String" />
        <Parameter Name="throughput" Type="System.Nullable&lt;System.Int32&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="serializedIndexingPolicy">CosmosDB Tabelle indizierungsrichtlinie</param>
        <param name="throughput">CosmosDB Tabelle Durchsatz</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>Diese API führt eine Überprüfung auf Vorhandensein und erfordert daher Listenberechtigungen.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreateQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; CreateQuery&lt;TElement&gt; () where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; CreateQuery&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.CreateQuery``1" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function CreateQuery(Of TElement As {ITableEntityNew}) () As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="abstract member CreateQuery : unit -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.CreateQuery : unit -&gt; Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.CreateQuery " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters />
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <summary>
            Eine Factorymethode, die eine Abfrage erstellt, kann mithilfe von LINQ geändert werden. Die Abfrage kann ausgeführt werden, anschließend mithilfe einer der Ausführungsmethoden zur <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTable" />, wie z. B. <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />, <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />, oder <see cref="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> -Objekt, für den Typ spezialisiert <c>TElement</c>, wiederholt ausgeführt werden kann.</returns>
        <remarks>
            Die <see cref="N:Microsoft.Azure.CosmosDB.Table.Queryable" /> Namespace enthält Erweiterungsmethoden für die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Objekts, einschließlich <see cref="M:WithOptions" />, <see cref="M:WithContext" />, und <see cref="M:AsTableQuery" />. Um diese Methoden verwenden, schließen Sie eine <c>mit</c> -Anweisung, verweist der <see cref="N:Microsoft.Azure.CosmosDB.Table.Queryable" /> Namespace.
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public virtual void Delete (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Delete(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Delete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.Delete : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="cloudTable.Delete (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Löscht eine Tabelle.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteAsync () As Task" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : unit -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : unit -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync " />
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
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen einer Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync cancellationToken" />
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
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen einer Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync (requestOptions, operationContext)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen einer Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task DeleteAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeleteAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.DeleteAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.DeleteAsync (requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen einer Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool DeleteIfExists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool DeleteIfExists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool&#xA;override this.DeleteIfExists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool" Usage="cloudTable.DeleteIfExists (requestOptions, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Löscht die Tabelle aus, falls vorhanden.
            </summary>
        <returns>
          <c>"true"</c> , wenn die Tabelle gelöscht; andernfalls wurde, <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function DeleteIfExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeleteIfExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; DeleteIfExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; DeleteIfExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.DeleteIfExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.DeleteIfExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.DeleteIfExistsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
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
            Initiiert einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreate">
      <MemberSignature Language="C#" Value="public virtual void EndCreate (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndCreate(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndCreate(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndCreate (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndCreate : IAsyncResult -&gt; unit&#xA;override this.EndCreate : IAsyncResult -&gt; unit" Usage="cloudTable.EndCreate asyncResult" />
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
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Erstellen einer Tabelle an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndCreateIfNotExists">
      <MemberSignature Language="C#" Value="public virtual bool EndCreateIfNotExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndCreateIfNotExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndCreateIfNotExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndCreateIfNotExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndCreateIfNotExists : IAsyncResult -&gt; bool&#xA;override this.EndCreateIfNotExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndCreateIfNotExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Erstellen einer Tabelle, wenn sie nicht bereits vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn Tabelle erstellt; andernfalls wurde, <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDelete">
      <MemberSignature Language="C#" Value="public virtual void EndDelete (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndDelete(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndDelete(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndDelete (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndDelete : IAsyncResult -&gt; unit&#xA;override this.EndDelete : IAsyncResult -&gt; unit" Usage="cloudTable.EndDelete asyncResult" />
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
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Löschen einer Tabelle an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndDeleteIfExists">
      <MemberSignature Language="C#" Value="public virtual bool EndDeleteIfExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndDeleteIfExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndDeleteIfExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndDeleteIfExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndDeleteIfExists : IAsyncResult -&gt; bool&#xA;override this.EndDeleteIfExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndDeleteIfExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Löschen der Tabelle, sofern vorhanden.
            </summary>
        <returns>
          <c>"true"</c> , wenn die Tabelle gelöscht; andernfalls wurde, <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResult EndExecute (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResult EndExecute(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecute(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecute (asyncResult As IAsyncResult) As TableResult" />
      <MemberSignature Language="F#" Value="abstract member EndExecute : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableResult&#xA;override this.EndExecute : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableResult" Usage="cloudTable.EndExecute asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet die Ausführung einer asynchronen Table-Vorgang.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die das Ergebnis der Ausführung des Vorgangs für die Tabelle enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; EndExecuteBatch (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; EndExecuteBatch(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteBatch(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteBatch (asyncResult As IAsyncResult) As IList(Of TableResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteBatch : IAsyncResult -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.EndExecuteBatch : IAsyncResult -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.EndExecuteBatch asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.
            </summary>
        <returns>Eine aufzählbare Auflistung vom Typ <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , enthält die Ergebnisse in der Reihenfolge jedes Vorgangs in der <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> für die Tabelle.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; EndExecuteQueryForKeyRotationSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; EndExecuteQueryForKeyRotationSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQueryForKeyRotationSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQueryForKeyRotationSegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of KeyRotationEntity)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQueryForKeyRotationSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&#xA;override this.EndExecuteQueryForKeyRotationSegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;" Usage="cloudTable.EndExecuteQueryForKeyRotationSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet eine asynchrone segmentierte Abfrage für eine Tabelle an. 
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> , die die Ergebnisse der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; EndExecuteQuerySegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; EndExecuteQuerySegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQuerySegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of DynamicTableEntity)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet eine asynchrone segmentierte Abfrage für eine Tabelle an. 
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> , die die Ergebnisse der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; EndExecuteQuerySegmented&lt;TResult&gt; (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; EndExecuteQuerySegmented&lt;TResult&gt;(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQuerySegmented``1(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented(Of TResult) (asyncResult As IAsyncResult) As TableQuerySegment(Of TResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Der Typ der zurückzugebenden Ergebnisse. Der Entitätstyp angegeben, die in den BEGIN- oder der Ergebnistyp des Konfliktlösers möglich</typeparam>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die die Ergebnisse der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; EndExecuteQuerySegmented&lt;TElement,TResult&gt; (IAsyncResult asyncResult) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; EndExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExecuteQuerySegmented``2(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteQuerySegmented(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (asyncResult As IAsyncResult) As TableQuerySegment(Of TResult)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.EndExecuteQuerySegmented : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.EndExecuteQuerySegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , enthält die Projektion in den Typ <c>TResult</c> der Ergebnisse der Ausführung der Abfrage. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExists">
      <MemberSignature Language="C#" Value="public virtual bool EndExists (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool EndExists(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndExists(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExists (asyncResult As IAsyncResult) As Boolean" />
      <MemberSignature Language="F#" Value="abstract member EndExists : IAsyncResult -&gt; bool&#xA;override this.EndExists : IAsyncResult -&gt; bool" Usage="cloudTable.EndExists asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn Tabelle vorhanden ist; andernfalls <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndGetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TablePermissions EndGetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TablePermissions EndGetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndGetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndGetPermissions (asyncResult As IAsyncResult) As TablePermissions" />
      <MemberSignature Language="F#" Value="abstract member EndGetPermissions : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions&#xA;override this.EndGetPermissions : IAsyncResult -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions" Usage="cloudTable.EndGetPermissions asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Das asynchrone Ergebnis der Anforderung zum Abrufen der berechtigungseinstellungen für die Tabelle zurückgegeben.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSetPermissions">
      <MemberSignature Language="C#" Value="public virtual void EndSetPermissions (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void EndSetPermissions(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.EndSetPermissions(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Sub EndSetPermissions (asyncResult As IAsyncResult)" />
      <MemberSignature Language="F#" Value="abstract member EndSetPermissions : IAsyncResult -&gt; unit&#xA;override this.EndSetPermissions : IAsyncResult -&gt; unit" Usage="cloudTable.EndSetPermissions asyncResult" />
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
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Das asynchrone Ergebnis der Anforderung zum Abrufen der berechtigungseinstellungen für die Tabelle zurückgegeben.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableResult Execute (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableResult Execute(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Execute(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Execute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableResult&#xA;override this.Execute : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableResult" Usage="cloudTable.Execute (operation, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operation">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt einen Vorgang für eine Tabelle.  
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteAsync (operation As TableOperation) As Task(Of TableResult)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync operation" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
      </Parameters>
      <Docs>
        <param name="operation">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, der einen asynchronen Table-Vorgang ausgeführt wird.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operation">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, der einen asynchronen Table-Vorgang ausgeführt wird.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="operation">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, der einen asynchronen Table-Vorgang ausgeführt wird.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync (Microsoft.Azure.CosmosDB.Table.TableOperation operation, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteAsync(class Microsoft.Azure.CosmosDB.Table.TableOperation operation, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteAsync(Microsoft.Azure.CosmosDB.Table.TableOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteAsync : Microsoft.Azure.CosmosDB.Table.TableOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteAsync (operation, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operation" Type="Microsoft.Azure.CosmosDB.Table.TableOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operation">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableOperation" /> Objekt, das den auszuführenden Vorgang darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, der einen asynchronen Table-Vorgang ausgeführt wird.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatch">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteBatch (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt; ExecuteBatch(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatch(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&#xA;override this.ExecuteBatch : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;" Usage="cloudTable.ExecuteBatch (batch, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="batch">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt einen Batchvorgang für eine Tabelle als atomarer Vorgang.
            </summary>
        <returns>Eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> Objekte, die die Ergebnisse jedes Vorgangs im nacheinander enthält die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> für die Tabelle.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteBatchAsync (batch As TableBatchOperation) As Task(Of IList(Of TableResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync batch" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
      </Parameters>
      <Docs>
        <param name="batch">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das eine Liste vom Typ <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das eine Liste vom Typ <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="batch">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das eine Liste vom Typ <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteBatchAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync (Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IList`1&lt;class Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt; ExecuteBatchAsync(class Microsoft.Azure.CosmosDB.Table.TableBatchOperation batch, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteBatchAsync(Microsoft.Azure.CosmosDB.Table.TableBatchOperation,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;&#xA;override this.ExecuteBatchAsync : Microsoft.Azure.CosmosDB.Table.TableBatchOperation * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;" Usage="cloudTable.ExecuteBatchAsync (batch, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IList&lt;Microsoft.Azure.CosmosDB.Table.TableResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="batch" Type="Microsoft.Azure.CosmosDB.Table.TableBatchOperation" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="batch">Die <see cref="T:Microsoft.Azure.CosmosDB.Table.TableBatchOperation" /> Objekt, das die Vorgänge zum Ausführen für die Tabelle darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen eines Batches von Vorgängen für eine Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> -Objekt, das eine Liste vom Typ <see cref="T:Microsoft.Azure.CosmosDB.Table.TableResult" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuery (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuery(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;" Usage="cloudTable.ExecuteQuery (query, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine Abfrage für eine Tabelle und gibt eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> Objekte.
            </summary>
        <returns>Eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> Objekten, die von der Abfrage zurückgegebenen Tabellenentitäten darstellen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TElement&gt; ExecuteQuery&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TElement&gt; ExecuteQuery&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuery (query, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Eine TableQuery-Instanz, die die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine Abfrage für eine Tabelle an.
            </summary>
        <returns>Eine aufzählbare Auflistung für den Typ spezialisiert <c>TElement</c>, der die Ergebnisse der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TResult&gt; ExecuteQuery&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TResult&gt; ExecuteQuery&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt;&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt;" Usage="cloudTable.ExecuteQuery (query, resolver, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine Abfrage für eine Tabelle, und wendet die angegebene <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.
            </summary>
        <returns>Eine aufzählbare Auflistung, die mit der Projektion in den Typ <c>TResult</c>, der die Ergebnisse der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuery&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TResult&gt; ExecuteQuery&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!!TResult&gt; ExecuteQuery&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuery``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuery : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuery (query, resolver, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine Abfrage aus und wendet die angegebene <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.
            </summary>
        <returns>Eine aufzählbare Auflistung, die mit der Projektion in den Typ <c>TResult</c>, der die Ergebnisse der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotation">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotation (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotation(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotation(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotation : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&#xA;override this.ExecuteQueryForKeyRotation : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; seq&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;" Usage="cloudTable.ExecuteQueryForKeyRotation (query, requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine Abfrage für eine Tabelle und gibt eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> Objekte.
            </summary>
        <returns>Eine aufzählbare Auflistung von <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> Objekten, die von der Abfrage zurückgegebenen Tabellenentitäten darstellen.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotationSegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt; ExecuteQueryForKeyRotationSegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmented (query, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine segmentierte Abfrage für eine Tabelle aus und gibt eine <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> mit <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> Objekte.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.KeyRotationEntity" /> , die die Ergebnisse der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQueryForKeyRotationSegmentedAsync (query As TableQuery, token As TableContinuationToken) As Task(Of TableQuerySegment(Of KeyRotationEntity))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQueryForKeyRotationSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt; ExecuteQueryForKeyRotationSegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQueryForKeyRotationSegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;&#xA;override this.ExecuteQueryForKeyRotationSegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;" Usage="cloudTable.ExecuteQueryForKeyRotationSegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
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
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.CosmosDB.Table.CloudTable/&lt;ExecuteQueryForKeyRotationSegmentedAsync&gt;d__85))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.KeyRotationEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuerySegmented (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt; ExecuteQuerySegmented(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;" Usage="cloudTable.ExecuteQuerySegmented (query, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine segmentierte Abfrage für eine Tabelle aus und gibt eine <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> mit <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> Objekte.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.DynamicTableEntity" /> , die die Ergebnisse der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt; ExecuteQuerySegmented&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt; ExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmented (query, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine Abfrage für eine Tabelle im segmentierten Modus.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" />, für den Typ spezielle <c>TElement</c>, mit den Ergebnissen der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; ExecuteQuerySegmented&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; ExecuteQuerySegmented&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;" Usage="cloudTable.ExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">To be added.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine segmentierte Abfrage für eine Tabelle und wendet die angegebene <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> Objekt, das die Ergebnisse der Ausführung der Abfrage enthält.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmented&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt; ExecuteQuerySegmented&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt; ExecuteQuerySegmented&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmented``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmented : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmented (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine Abfrage im segmentierten Modus und wendet die angegebene <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , enthält die Projektion in den Typ <c>TResult</c> der Ergebnisse der Ausführung der Abfrage. </returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync (query As TableQuery, token As TableContinuationToken) As Task(Of TableQuerySegment(Of DynamicTableEntity))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;class Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt; ExecuteQuerySegmentedAsync(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;Microsoft.Azure.CosmosDB.Table.DynamicTableEntity&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> , die die auszuführende Abfrage darstellt.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um eine segmentierte Abfrage für eine Tabelle auszuführen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TElement As {ITableEntityNew}) (query As TableQuery(Of TElement), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TElement))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TElement&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Element&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abfragen einer Tabelle im segmentierten Modus.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TResult) (query As TableQuery, resolver As EntityResolver(Of TResult), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz unter Angabe der Tabelle Abfragen ausgeführt und die Abfrageparameter verwendet.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz unter Angabe der Tabelle Abfragen ausgeführt und die Abfrageparameter verwendet.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz unter Angabe der Tabelle Abfragen ausgeführt und die Abfrageparameter verwendet.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``1(Microsoft.Azure.CosmosDB.Table.TableQuery,Microsoft.Azure.CosmosDB.Table.EntityResolver{``0},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt;" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz unter Angabe der Tabelle Abfragen ausgeführt und die Abfrageparameter verwendet.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage segmentierten und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> auf das Ergebnis.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteQuerySegmentedAsync(Of TElement As {ITableEntityNew}, TResult As {ITableEntityNew}) (query As TableQuery(Of TElement), resolver As EntityResolver(Of TResult), token As TableContinuationToken) As Task(Of TableQuerySegment(Of TResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt;">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;TElement,TResult&gt; (Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt; query, Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt; resolver, Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken) where TElement : Microsoft.Azure.CosmosDB.Table.ITableEntitynew();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TableQuerySegment`1&lt;!!TResult&gt;&gt; ExecuteQuerySegmentedAsync&lt;.ctor (class Microsoft.Azure.CosmosDB.Table.ITableEntity) TElement, TResult&gt;(class Microsoft.Azure.CosmosDB.Table.TableQuery`1&lt;!!TElement&gt; query, class Microsoft.Azure.CosmosDB.Table.EntityResolver`1&lt;!!TResult&gt; resolver, class Microsoft.Azure.CosmosDB.Table.TableContinuationToken token, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExecuteQuerySegmentedAsync``2(Microsoft.Azure.CosmosDB.Table.TableQuery{``0},Microsoft.Azure.CosmosDB.Table.EntityResolver{``1},Microsoft.Azure.CosmosDB.Table.TableContinuationToken,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&#xA;override this.ExecuteQuerySegmentedAsync : Microsoft.Azure.CosmosDB.Table.TableQuery&lt;'Element (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))&gt; * Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;'Result&gt; * Microsoft.Azure.CosmosDB.Table.TableContinuationToken * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;'Result&gt;&gt; (requires 'Element :&gt; Microsoft.Azure.CosmosDB.Table.ITableEntity and 'Element : (new : unit -&gt; 'Element))" Usage="cloudTable.ExecuteQuerySegmentedAsync (query, resolver, token, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TableQuerySegment&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TElement">
          <Constraints>
            <ParameterAttribute>DefaultConstructorConstraint</ParameterAttribute>
            <InterfaceName>Microsoft.Azure.CosmosDB.Table.ITableEntity</InterfaceName>
          </Constraints>
        </TypeParameter>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="query" Type="Microsoft.Azure.CosmosDB.Table.TableQuery&lt;TElement&gt;" />
        <Parameter Name="resolver" Type="Microsoft.Azure.CosmosDB.Table.EntityResolver&lt;TResult&gt;" />
        <Parameter Name="token" Type="Microsoft.Azure.CosmosDB.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TElement">Der Entitätstyp der Abfrage.</typeparam>
        <typeparam name="TResult">Der Typ, in dem <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> projiziert die Ergebnisse der Abfrage.</typeparam>
        <param name="query">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableQuery" /> Instanz, die Tabelle Abfragen ausgeführt und die zu verwendenden Abfrageparameter angeben, für einen Typ spezialisiert <c>TElement</c>.</param>
        <param name="resolver">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> -Instanz, die eine Projektion der Tabellenabfrage in den angegebenen Typ ergebnisentitäten erstellt <c>TResult</c>.</param>
        <param name="token">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage im segmentierten Modus und Anwenden der angegebenen <see cref="T:Microsoft.Azure.CosmosDB.Table.EntityResolver`1" /> mit den Ergebnissen.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Exists">
      <MemberSignature Language="C#" Value="public virtual bool Exists (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance bool Exists(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.Exists(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Exists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool&#xA;override this.Exists : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; bool" Usage="cloudTable.Exists (requestOptions, operationContext)" />
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
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Überprüft, ob die Tabelle vorhanden ist.
            </summary>
        <returns>
          <c>"true"</c> Wenn Tabelle vorhanden ist; andernfalls <c>"false"</c>.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExistsAsync () As Task(Of Boolean)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : unit -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExistsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;bool&gt; ExistsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; ExistsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ExistsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;&#xA;override this.ExistsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="cloudTable.ExistsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
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
            Initiiert einen asynchronen Vorgang, um festzustellen, ob eine Tabelle vorhanden ist.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <c>Bool</c> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissions">
      <MemberSignature Language="C#" Value="public virtual Microsoft.Azure.CosmosDB.Table.TablePermissions GetPermissions (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.CosmosDB.Table.TablePermissions GetPermissions(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissions(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions&#xA;override this.GetPermissions : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; Microsoft.Azure.CosmosDB.Table.TablePermissions" Usage="cloudTable.GetPermissions (requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.Azure.CosmosDB.Table.TablePermissions</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Ruft die berechtigungseinstellungen für die Tabelle ab.
            </summary>
        <returns>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" />-Objekt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetPermissionsAsync () As Task(Of TablePermissions)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : unit -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync " />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync cancellationToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync (requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.CosmosDB.Table.TablePermissions&gt; GetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;&#xA;override this.GetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;" Usage="cloudTable.GetPermissionsAsync (requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.CosmosDB.Table.TablePermissions&gt;</ReturnType>
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
            Initiiert einen asynchronen Vorgang zum Abrufen der berechtigungseinstellungen für die Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> Objekt des Typs <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy -&gt; string" Usage="cloudTable.GetSharedAccessSignature policy" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
      </Parameters>
      <Docs>
        <param name="policy">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</param>
        <summary>
            Gibt eine SAS für die Tabelle zurück.
            </summary>
        <returns>Eine SAS als URI-Abfragezeichenfolge.</returns>
        <remarks>Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</remarks>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn die aktuellen Anmeldeinformationen nicht unterstützen, eine shared Access Signature erstellen.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy, accessPolicyIdentifier As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy * string -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</param>
        <param name="accessPolicyIdentifier">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</param>
        <summary>
            Gibt eine SAS für die Tabelle zurück.
            </summary>
        <returns>Eine SAS als URI-Abfragezeichenfolge.</returns>
        <remarks>Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</remarks>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn die aktuellen Anmeldeinformationen nicht unterstützen, eine shared Access Signature erstellen.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy,System.String,System.String,System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSharedAccessSignature (policy As SharedAccessTablePolicy, accessPolicyIdentifier As String, startPartitionKey As String, startRowKey As String, endPartitionKey As String, endRowKey As String) As String" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy * string * string * string * string * string -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier, startPartitionKey, startRowKey, endPartitionKey, endRowKey)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
        <Parameter Name="startPartitionKey" Type="System.String" />
        <Parameter Name="startRowKey" Type="System.String" />
        <Parameter Name="endPartitionKey" Type="System.String" />
        <Parameter Name="endRowKey" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="policy">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</param>
        <param name="accessPolicyIdentifier">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</param>
        <param name="startPartitionKey">Eine Zeichenfolge, die den startpartitionsschlüssel angibt oder <c>null</c>.</param>
        <param name="startRowKey">Eine Zeichenfolge, die den Zeilenschlüssel Start angibt oder <c>null</c>.</param>
        <param name="endPartitionKey">Eine Zeichenfolge, die den endpartitionsschlüssel angibt oder <c>null</c>.</param>
        <param name="endRowKey">Eine Zeichenfolge, die den endzeilenschlüssel angibt oder <c>null</c>.</param>
        <summary>
            Gibt eine SAS für die Tabelle zurück.
            </summary>
        <returns>Eine SAS als URI-Abfragezeichenfolge.</returns>
        <remarks>Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</remarks>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn die aktuellen Anmeldeinformationen nicht unterstützen, eine shared Access Signature erstellen.</exception>
      </Docs>
    </Member>
    <Member MemberName="GetSharedAccessSignature">
      <MemberSignature Language="C#" Value="public string GetSharedAccessSignature (Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey, Nullable&lt;Microsoft.Azure.Storage.SharedAccessProtocol&gt; protocols, Microsoft.Azure.Storage.IPAddressOrRange ipAddressOrRange);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance string GetSharedAccessSignature(class Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy policy, string accessPolicyIdentifier, string startPartitionKey, string startRowKey, string endPartitionKey, string endRowKey, valuetype System.Nullable`1&lt;valuetype Microsoft.Azure.Storage.SharedAccessProtocol&gt; protocols, class Microsoft.Azure.Storage.IPAddressOrRange ipAddressOrRange) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.GetSharedAccessSignature(Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy,System.String,System.String,System.String,System.String,System.String,System.Nullable{Microsoft.Azure.Storage.SharedAccessProtocol},Microsoft.Azure.Storage.IPAddressOrRange)" />
      <MemberSignature Language="F#" Value="member this.GetSharedAccessSignature : Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy * string * string * string * string * string * Nullable&lt;Microsoft.Azure.Storage.SharedAccessProtocol&gt; * Microsoft.Azure.Storage.IPAddressOrRange -&gt; string" Usage="cloudTable.GetSharedAccessSignature (policy, accessPolicyIdentifier, startPartitionKey, startRowKey, endPartitionKey, endRowKey, protocols, ipAddressOrRange)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="policy" Type="Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" />
        <Parameter Name="accessPolicyIdentifier" Type="System.String" />
        <Parameter Name="startPartitionKey" Type="System.String" />
        <Parameter Name="startRowKey" Type="System.String" />
        <Parameter Name="endPartitionKey" Type="System.String" />
        <Parameter Name="endRowKey" Type="System.String" />
        <Parameter Name="protocols" Type="System.Nullable&lt;Microsoft.Azure.Storage.SharedAccessProtocol&gt;" />
        <Parameter Name="ipAddressOrRange" Type="Microsoft.Azure.Storage.IPAddressOrRange" />
      </Parameters>
      <Docs>
        <param name="policy">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.SharedAccessTablePolicy" /> Objekt, das die Zugriffsrichtlinie für die SAS angibt.</param>
        <param name="accessPolicyIdentifier">Eine Zeichenfolge, die eine gespeicherte Zugriffsrichtlinie identifiziert.</param>
        <param name="startPartitionKey">Eine Zeichenfolge, die den startpartitionsschlüssel angibt oder <c>null</c>.</param>
        <param name="startRowKey">Eine Zeichenfolge, die den Zeilenschlüssel Start angibt oder <c>null</c>.</param>
        <param name="endPartitionKey">Eine Zeichenfolge, die den endpartitionsschlüssel angibt oder <c>null</c>.</param>
        <param name="endRowKey">Eine Zeichenfolge, die den endzeilenschlüssel angibt oder <c>null</c>.</param>
        <param name="protocols">Die zulässige Protokolle (nur Https oder http und Https). NULL, wenn Sie nicht Protokoll beschränken möchten.</param>
        <param name="ipAddressOrRange">Die zulässigen IP-Adresse oder IP-Adressbereich. NULL, wenn Sie einschränken möchten, nicht basierend auf IP-Adresse.</param>
        <summary>
            Gibt eine SAS für die Tabelle zurück.
            </summary>
        <returns>Eine SAS als URI-Abfragezeichenfolge.</returns>
        <remarks>Die zurückgegebene Abfragezeichenfolge enthält das vorangestellte Fragezeichen.</remarks>
        <exception cref="T:System.InvalidOperationException">Wird ausgelöst, wenn die aktuellen Anmeldeinformationen nicht unterstützen, eine shared Access Signature erstellen.</exception>
      </Docs>
    </Member>
    <Member MemberName="Name">
      <MemberSignature Language="C#" Value="public string Name { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Name" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.Name" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Name As String" />
      <MemberSignature Language="F#" Value="member this.Name : string" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.Name" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der Tabelle ab.
            </summary>
        <value>Eine Zeichenfolge, die mit dem Namen der Tabelle.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.CosmosDB.Table.CloudTableClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.CosmosDB.Table.CloudTableClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudTableClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.Azure.CosmosDB.Table.CloudTableClient" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.CosmosDB.Table.CloudTableClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> -Objekt, das den Tabellendienst darstellt.
            </summary>
        <value>Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.CloudTableClient" /> Objekt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissions">
      <MemberSignature Language="C#" Value="public virtual void SetPermissions (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions = null, Microsoft.Azure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void SetPermissions(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissions(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit&#xA;override this.SetPermissions : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; unit" Usage="cloudTable.SetPermissions (permissions, requestOptions, operationContext)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Legt die berechtigungseinstellungen für die Tabelle fest.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function SetPermissionsAsync (permissions As TablePermissions) As Task" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync permissions" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
      </Parameters>
      <Docs>
        <param name="permissions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, cancellationToken)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, requestOptions, operationContext)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="permissions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SetPermissionsAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task SetPermissionsAsync (Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, Microsoft.Azure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SetPermissionsAsync(class Microsoft.Azure.CosmosDB.Table.TablePermissions permissions, class Microsoft.Azure.CosmosDB.Table.TableRequestOptions requestOptions, class Microsoft.Azure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.SetPermissionsAsync(Microsoft.Azure.CosmosDB.Table.TablePermissions,Microsoft.Azure.CosmosDB.Table.TableRequestOptions,Microsoft.Azure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&#xA;override this.SetPermissionsAsync : Microsoft.Azure.CosmosDB.Table.TablePermissions * Microsoft.Azure.CosmosDB.Table.TableRequestOptions * Microsoft.Azure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="cloudTable.SetPermissionsAsync (permissions, requestOptions, operationContext, cancellationToken)" />
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
        <Parameter Name="permissions" Type="Microsoft.Azure.CosmosDB.Table.TablePermissions" />
        <Parameter Name="requestOptions" Type="Microsoft.Azure.CosmosDB.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.Azure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="permissions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TablePermissions" /> Objekt, das die Berechtigungen festgelegt darstellt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.Azure.CosmosDB.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.Azure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Festlegen von Berechtigungen für die Tabelle an.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StorageUri">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Storage.StorageUri StorageUri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Storage.StorageUri StorageUri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageUri As StorageUri" />
      <MemberSignature Language="F#" Value="member this.StorageUri : Microsoft.Azure.Storage.StorageUri" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" />
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
            Ruft die Tabellen URIs für die primären und sekundären Speicherorte ab.
            </summary>
        <value>Ein Objekt des Typs <see cref="P:Microsoft.Azure.CosmosDB.Table.CloudTable.StorageUri" /> , die die Tabellen URIs für die primären und sekundären Speicherorte enthält.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ToString">
      <MemberSignature Language="C#" Value="public override string ToString ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig virtual instance string ToString() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.CosmosDB.Table.CloudTable.ToString" />
      <MemberSignature Language="VB.NET" Value="Public Overrides Function ToString () As String" />
      <MemberSignature Language="F#" Value="override this.ToString : unit -&gt; string" Usage="cloudTable.ToString " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.CosmosDB.Table</AssemblyName>
        <AssemblyVersion>0.9.0.0</AssemblyVersion>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt den Namen der Tabelle zurück.
            </summary>
        <returns>Eine Zeichenfolge, die mit dem Namen der Tabelle.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Uri">
      <MemberSignature Language="C#" Value="public Uri Uri { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Uri Uri" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.CosmosDB.Table.CloudTable.Uri" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Uri As Uri" />
      <MemberSignature Language="F#" Value="member this.Uri : Uri" Usage="Microsoft.Azure.CosmosDB.Table.CloudTable.Uri" />
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
            Ruft den Tabelle-URI für den primären Speicherort ab.
            </summary>
        <value>Ein <see cref="T:System.Uri" /> den absoluten URI zur Tabelle am primären Standort angeben.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>