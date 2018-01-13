<Type Name="TableServiceContext" FullName="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext">
  <TypeSignature Language="C#" Value="public class TableServiceContext : System.Data.Services.Client.DataServiceContext, IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableServiceContext extends System.Data.Services.Client.DataServiceContext implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />
  <TypeSignature Language="VB.NET" Value="Public Class TableServiceContext&#xA;Inherits DataServiceContext&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type TableServiceContext = class&#xA;    inherit DataServiceContext&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Data.Services.Client.DataServiceContext</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Attributes>
    <Attribute>
      <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
    </Attribute>
  </Attributes>
  <Docs>
    <summary>
            Stellt eine <see cref="T:System.Data.Services.Client.DataServiceContext" /> Objekt für die Verwendung mit dem Windows Azure-Tabellendienst.
            </summary>
    <remarks>Die <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" /> Klasse unterstützt keine gleichzeitigen Abfragen oder Anforderungen.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableServiceContext (Microsoft.WindowsAzure.Storage.Table.CloudTableClient client);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor(class Microsoft.WindowsAzure.Storage.Table.CloudTableClient client) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.#ctor(Microsoft.WindowsAzure.Storage.Table.CloudTableClient)" />
      <MemberSignature Language="VB.NET" Value="Public Sub New (client As CloudTableClient)" />
      <MemberSignature Language="F#" Value="new Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext : Microsoft.WindowsAzure.Storage.Table.CloudTableClient -&gt; Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" Usage="new Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext client" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <Parameters>
        <Parameter Name="client" Type="Microsoft.WindowsAzure.Storage.Table.CloudTableClient" />
      </Parameters>
      <Docs>
        <param name="client">To be added.</param>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries (AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries(class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.BeginSaveChangesWithRetries(System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginSaveChangesWithRetries (callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginSaveChangesWithRetries : AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceContext.BeginSaveChangesWithRetries (callback, state)" />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
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
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries (System.Data.Services.Client.SaveChangesOptions options, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries(valuetype System.Data.Services.Client.SaveChangesOptions options, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.BeginSaveChangesWithRetries(System.Data.Services.Client.SaveChangesOptions,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Function BeginSaveChangesWithRetries (options As SaveChangesOptions, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="member this.BeginSaveChangesWithRetries : System.Data.Services.Client.SaveChangesOptions * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceContext.BeginSaveChangesWithRetries (options, callback, state)" />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginSaveChangesWithRetries(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.BeginSaveChangesWithRetries(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="member this.BeginSaveChangesWithRetries : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableServiceContext.BeginSaveChangesWithRetries (options, requestOptions, operationContext, callback, state)" />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.ICancellableAsyncResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</param>
        <param name="requestOptions"></param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="public void Dispose ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Dispose() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.Dispose" />
      <MemberSignature Language="VB.NET" Value="Public Sub Dispose ()" />
      <MemberSignature Language="F#" Value="abstract member Dispose : unit -&gt; unit&#xA;override this.Dispose : unit -&gt; unit" Usage="tableServiceContext.Dispose " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.IDisposable.Dispose</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt alle von der TableServiceContext verwendete Ressourcen frei.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Dispose">
      <MemberSignature Language="C#" Value="protected virtual void Dispose (bool disposing);" />
      <MemberSignature Language="ILAsm" Value=".method familyhidebysig newslot virtual instance void Dispose(bool disposing) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.Dispose(System.Boolean)" />
      <MemberSignature Language="VB.NET" Value="Protected Overridable Sub Dispose (disposing As Boolean)" />
      <MemberSignature Language="F#" Value="abstract member Dispose : bool -&gt; unit&#xA;override this.Dispose : bool -&gt; unit" Usage="tableServiceContext.Dispose disposing" />
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
        <Parameter Name="disposing" Type="System.Boolean" />
      </Parameters>
      <Docs>
        <param name="disposing">
          <c>"true"</c> um sowohl verwaltete als auch nicht verwaltete Ressourcen freizugeben <c>"false"</c> um ausschließlich nicht verwaltete Ressourcen freizugeben.</param>
        <summary>
            Die von der TableServiceContext verwendeten nicht verwalteten Ressourcen frei, und optional die verwalteten Ressourcen frei.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndSaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.DataServiceResponse EndSaveChangesWithRetries (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.Services.Client.DataServiceResponse EndSaveChangesWithRetries(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.EndSaveChangesWithRetries(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Function EndSaveChangesWithRetries (asyncResult As IAsyncResult) As DataServiceResponse" />
      <MemberSignature Language="F#" Value="member this.EndSaveChangesWithRetries : IAsyncResult -&gt; System.Data.Services.Client.DataServiceResponse" Usage="tableServiceContext.EndSaveChangesWithRetries asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.DataServiceResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Eine <see cref="T:System.IAsyncResult" /> , die auf den ausstehenden asynchronen Vorgang verweist.</param>
        <summary>
            Beendet einen asynchronen Vorgang, um Änderungen zu speichern.
            </summary>
        <returns> Ein <see cref="T:System.Data.Services.Client.DataServiceResponse" /> , die das Ergebnis des Vorgangs darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetries" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesWithRetries () As DataServiceResponse" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetries : unit -&gt; System.Data.Services.Client.DataServiceResponse" Usage="tableServiceContext.SaveChangesWithRetries " />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.DataServiceResponse</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Speichert die Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns>Ein <see cref="T:System.Data.Services.Client.DataServiceResponse" /> , die das Ergebnis des Vorgangs darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetries">
      <MemberSignature Language="C#" Value="public System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Data.Services.Client.DataServiceResponse SaveChangesWithRetries(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetries(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetries : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Data.Services.Client.DataServiceResponse" Usage="tableServiceContext.SaveChangesWithRetries (options, requestOptions, operationContext)" />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Data.Services.Client.DataServiceResponse</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Speichert die Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns> Ein <see cref="T:System.Data.Services.Client.DataServiceResponse" /> , die das Ergebnis des Vorgangs darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesWithRetriesAsync () As Task(Of DataServiceResponse)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : unit -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync " />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions)" />
      <MemberSignature Language="VB.NET" Value="Public Function SaveChangesWithRetriesAsync (options As SaveChangesOptions) As Task(Of DataServiceResponse)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync options" />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync cancellationToken" />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync (options, cancellationToken)" />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync (options, requestOptions, operationContext)" />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SaveChangesWithRetriesAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync (System.Data.Services.Client.SaveChangesOptions options, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class System.Threading.Tasks.Task`1&lt;class System.Data.Services.Client.DataServiceResponse&gt; SaveChangesWithRetriesAsync(valuetype System.Data.Services.Client.SaveChangesOptions options, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.SaveChangesWithRetriesAsync(System.Data.Services.Client.SaveChangesOptions,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="member this.SaveChangesWithRetriesAsync : System.Data.Services.Client.SaveChangesOptions * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;" Usage="tableServiceContext.SaveChangesWithRetriesAsync (options, requestOptions, operationContext, cancellationToken)" />
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
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Data.Services.Client.DataServiceResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="options" Type="System.Data.Services.Client.SaveChangesOptions" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="options">Ein <see cref="T:System.Data.Services.Client.SaveChangesOptions" />-Enumerationswert.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Speichern von Änderungen, über die wiederholungsrichtlinie für den Dienstkontext angegeben.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" />-Objekt, das den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ServiceClient">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.CloudTableClient ServiceClient { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.WindowsAzure.Storage.Table.CloudTableClient ServiceClient" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.ServiceClient" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ServiceClient As CloudTableClient" />
      <MemberSignature Language="F#" Value="member this.ServiceClient : Microsoft.WindowsAzure.Storage.Table.CloudTableClient" Usage="Microsoft.WindowsAzure.Storage.Table.DataServices.TableServiceContext.ServiceClient" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Obsolete("Support for accessing Windows Azure Tables via WCF Data Services is now obsolete. It's recommended that you use the Microsoft.WindowsAzure.Storage.Table namespace for working with tables.")</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.CloudTableClient</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die <see cref="T:Microsoft.WindowsAzure.Storage.Table.CloudTableClient" /> -Objekt, das den Tabellendienst darstellt.
            </summary>
        <value>Ein Clientobjekt, das den tabellendienstendpunkt angibt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>