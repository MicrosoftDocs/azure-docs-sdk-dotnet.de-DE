<Type Name="TableQuery&lt;TElement&gt;" FullName="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;">
  <TypeSignature Language="C#" Value="public class TableQuery&lt;TElement&gt; : System.Collections.Generic.IEnumerable&lt;TElement&gt;, System.Linq.IQueryable&lt;TElement&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi beforefieldinit TableQuery`1&lt;TElement&gt; extends System.Object implements class System.Collections.Generic.IEnumerable`1&lt;!TElement&gt;, class System.Collections.IEnumerable, class System.Linq.IQueryable, class System.Linq.IQueryable`1&lt;!TElement&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.WindowsAzure.Storage.Table.TableQuery`1" />
  <TypeSignature Language="VB.NET" Value="Public Class TableQuery(Of TElement)&#xA;Implements IEnumerable(Of TElement), IQueryable(Of TElement)" />
  <TypeSignature Language="F#" Value="type TableQuery&lt;'Element&gt; = class&#xA;    interface IQueryable&lt;'Element&gt;&#xA;    interface seq&lt;'Element&gt;&#xA;    interface IQueryable&#xA;    interface IEnumerable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
    <AssemblyVersion>8.4.0.0</AssemblyVersion>
    <AssemblyVersion>8.7.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TElement" />
  </TypeParameters>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces>
    <Interface>
      <InterfaceName>System.Collections.Generic.IEnumerable&lt;TElement&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.Linq.IQueryable&lt;TElement&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TElement">Eine Klasse, die implementiert <see cref="T:Microsoft.WindowsAzure.Storage.Table.ITableEntity" />.</typeparam>
    <summary>
            Stellt eine Abfrage für ein Microsoft Azure-Tabelle dar.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName=".ctor">
      <MemberSignature Language="C#" Value="public TableQuery ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig specialname rtspecialname instance void .ctor() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.#ctor" />
      <MemberSignature Language="VB.NET" Value="Public Sub New ()" />
      <MemberType>Constructor</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Parameters />
      <Docs>
        <summary>
            Initialisiert eine neue Instanz der <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery`1" />-Klasse.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteSegmented (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteSegmented(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.BeginExecuteSegmented(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function BeginExecuteSegmented (currentToken As TableContinuationToken, callback As AsyncCallback, state As Object) As ICancellableAsyncResult" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableQuery.BeginExecuteSegmented (currentToken, callback, state)" />
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> einem vorherigen Auflistungsvorgang zurückgegebenes Objekt. Möglicherweise <c>null</c>.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Ausführen einer Abfrage, und geben Sie die Ergebnisse als ein ergebnissegment zurück.
            </summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BeginExecuteSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteSegmented (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, AsyncCallback callback, object state);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.ICancellableAsyncResult BeginExecuteSegmented(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, class System.AsyncCallback callback, object state) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.BeginExecuteSegmented(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.AsyncCallback,System.Object)" />
      <MemberSignature Language="F#" Value="abstract member BeginExecuteSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult&#xA;override this.BeginExecuteSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * AsyncCallback * obj -&gt; Microsoft.WindowsAzure.Storage.ICancellableAsyncResult" Usage="tableQuery.BeginExecuteSegmented (currentToken, requestOptions, operationContext, callback, state)" />
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
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="callback" Type="System.AsyncCallback" />
        <Parameter Name="state" Type="System.Object" />
      </Parameters>
      <Docs>
        <param name="currentToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> einem vorherigen Auflistungsvorgang zurückgegebenes Objekt. Möglicherweise <c>null</c>.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="callback">Ein <see cref="T:System.AsyncCallback" /> Delegat, der Benachrichtigung erhalten sollen, wenn der asynchrone Vorgang abgeschlossen ist.</param>
        <param name="state">Ein benutzerdefiniertes Objekt, die an dem Rückrufdelegaten übergeben werden.</param>
        <summary>
            Startet einen asynchronen Vorgang zum Ausführen einer Abfrage, und geben Sie die Ergebnisse als ein ergebnissegment zurück.
            </summary>
        <returns>Ein <see cref="T:System.IAsyncResult" /> , das auf den asynchronen Vorgang verweist.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Copy">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; Copy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!TElement&gt; Copy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.Copy" />
      <MemberSignature Language="VB.NET" Value="Public Function Copy () As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.Copy : unit -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;" Usage="tableQuery.Copy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ElementType">
      <MemberSignature Language="C#" Value="public Type ElementType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Type ElementType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.ElementType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ElementType As Type" />
      <MemberSignature Language="F#" Value="member this.ElementType : Type" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;.ElementType" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Linq.IQueryable.ElementType</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Type</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ der Elemente, die zurückgegeben werden, wenn die Ausdrucksbaumstruktur ausgeführt wird.
            </summary>
        <value>Ein <see cref="T:System.Type" /> , der den Typ der Elemente, die zurückgegeben werden, wenn die Ausdrucksbaumstruktur, die diesem Objekt zugeordneten ausgeführt wird, darstellt.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndExecuteSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt; EndExecuteSegmented (IAsyncResult asyncResult);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt; EndExecuteSegmented(class System.IAsyncResult asyncResult) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.EndExecuteSegmented(System.IAsyncResult)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function EndExecuteSegmented (asyncResult As IAsyncResult) As TableQuerySegment(Of TElement)" />
      <MemberSignature Language="F#" Value="abstract member EndExecuteSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&#xA;override this.EndExecuteSegmented : IAsyncResult -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;" Usage="tableQuery.EndExecuteSegmented asyncResult" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="asyncResult" Type="System.IAsyncResult" />
      </Parameters>
      <Docs>
        <param name="asyncResult">Der Verweis auf die ausstehende asynchrone Anforderung, die beendet werden soll.</param>
        <summary>
            Beendet einen asynchronen Vorgang zum Ausführen einer Abfrage, und geben Sie die Ergebnisse als ein ergebnissegment zurück.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />-Objekt vom Typ <typeparamref name="TElement" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Execute">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerable&lt;TElement&gt; Execute (Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;!TElement&gt; Execute(class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.Execute(Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member Execute : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;'Element&gt;&#xA;override this.Execute : Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; seq&lt;'Element&gt;" Usage="tableQuery.Execute (requestOptions, operationContext)" />
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
        <ReturnType>System.Collections.Generic.IEnumerable&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine Abfrage für eine Tabelle an.
            </summary>
        <returns>Eine aufzählbare Auflistung für den Typ spezialisiert <c>TElement</c>, der die Ergebnisse der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmented">
      <MemberSignature Language="C#" Value="public virtual Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt; ExecuteSegmented (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken continuationToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions = null, Microsoft.WindowsAzure.Storage.OperationContext operationContext = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt; ExecuteSegmented(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken continuationToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.ExecuteSegmented(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&#xA;override this.ExecuteSegmented : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;" Usage="tableQuery.ExecuteSegmented (continuationToken, requestOptions, operationContext)" />
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
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="continuationToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="continuationToken">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" /> -Objekt, ein Fortsetzungstoken vom Server darstellt, wenn der Vorgang ein Teilergebnis zurückgibt.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Führt eine segmentierte Abfrage für eine Tabelle.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" />, für den Typ spezielle <c>TElement</c>, mit den Ergebnissen der Ausführung der Abfrage.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.ExecuteSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function ExecuteSegmentedAsync (currentToken As TableContinuationToken) As Task(Of TableQuerySegment(Of TElement))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;&#xA;override this.ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableQuery.ExecuteSegmentedAsync currentToken" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken kann null sein.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage, und geben Sie die Ergebnisse als ein ergebnissegment zurück.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.ExecuteSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;&#xA;override this.ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableQuery.ExecuteSegmentedAsync (currentToken, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken kann null sein.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage, und geben Sie die Ergebnisse als ein ergebnissegment zurück.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.ExecuteSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;&#xA;override this.ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableQuery.ExecuteSegmentedAsync (currentToken, requestOptions, operationContext)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
      </Parameters>
      <Docs>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken kann null sein.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage, und geben Sie die Ergebnisse als ein ergebnissegment zurück.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteSegmentedAsync">
      <MemberSignature Language="C#" Value="public virtual System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt; ExecuteSegmentedAsync (Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, Microsoft.WindowsAzure.Storage.OperationContext operationContext, System.Threading.CancellationToken cancellationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1&lt;!TElement&gt;&gt; ExecuteSegmentedAsync(class Microsoft.WindowsAzure.Storage.Table.TableContinuationToken currentToken, class Microsoft.WindowsAzure.Storage.Table.TableRequestOptions requestOptions, class Microsoft.WindowsAzure.Storage.OperationContext operationContext, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.ExecuteSegmentedAsync(Microsoft.WindowsAzure.Storage.Table.TableContinuationToken,Microsoft.WindowsAzure.Storage.Table.TableRequestOptions,Microsoft.WindowsAzure.Storage.OperationContext,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;&#xA;override this.ExecuteSegmentedAsync : Microsoft.WindowsAzure.Storage.Table.TableContinuationToken * Microsoft.WindowsAzure.Storage.Table.TableRequestOptions * Microsoft.WindowsAzure.Storage.OperationContext * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;'Element&gt;&gt;" Usage="tableQuery.ExecuteSegmentedAsync (currentToken, requestOptions, operationContext, cancellationToken)" />
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
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.WindowsAzure.Storage.Table.TableQuerySegment&lt;TElement&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="currentToken" Type="Microsoft.WindowsAzure.Storage.Table.TableContinuationToken" />
        <Parameter Name="requestOptions" Type="Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" />
        <Parameter Name="operationContext" Type="Microsoft.WindowsAzure.Storage.OperationContext" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="currentToken">Eine von einem vorherigen Auflistungsvorgang zurückgegebenes Fortsetzungstoken kann null sein.</param>
        <param name="requestOptions">Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableRequestOptions" /> -Objekt, das zusätzliche Optionen für die Anforderung angibt.</param>
        <param name="operationContext">Ein <see cref="T:Microsoft.WindowsAzure.Storage.OperationContext" /> -Objekt, das den Kontext für den aktuellen Vorgang darstellt.</param>
        <param name="cancellationToken">Ein <see cref="T:System.Threading.CancellationToken" />, das beim Warten auf den Abschluss einer Aufgabe überwacht werden soll.</param>
        <summary>
            Initiiert einen asynchronen Vorgang zum Ausführen einer Abfrage, und geben Sie die Ergebnisse als ein ergebnissegment zurück.
            </summary>
        <returns>Ein <see cref="T:System.Threading.Tasks.Task`1" /> des Typs <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuerySegment`1" /> , die den asynchronen Vorgang darstellt.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Expression">
      <MemberSignature Language="C#" Value="public System.Linq.Expressions.Expression Expression { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Linq.Expressions.Expression Expression" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.Expression" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Expression As Expression" />
      <MemberSignature Language="F#" Value="member this.Expression : System.Linq.Expressions.Expression" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;.Expression" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Linq.IQueryable.Expression</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.Expressions.Expression</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ausdrucksstruktur ab.
            </summary>
        <value>Die <see cref="T:System.Linq.Expressions.Expression" /> , dieser Instanz zugeordnet ist <see cref="T:System.Linq.IQueryable" />.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FilterString">
      <MemberSignature Language="C#" Value="public string FilterString { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FilterString" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.FilterString" />
      <MemberSignature Language="VB.NET" Value="Public Property FilterString As String" />
      <MemberSignature Language="F#" Value="member this.FilterString : string with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;.FilterString" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt den Filterausdruck für die Verwendung in der Tabellenabfrage.
            </summary>
        <value>Eine Zeichenfolge, die mit dem Filterausdruck in der Abfrage verwendet wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetEnumerator">
      <MemberSignature Language="C#" Value="public virtual System.Collections.Generic.IEnumerator&lt;TElement&gt; GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerator`1&lt;!TElement&gt; GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Overridable Function GetEnumerator () As IEnumerator(Of TElement)" />
      <MemberSignature Language="F#" Value="abstract member GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'Element&gt;&#xA;override this.GetEnumerator : unit -&gt; System.Collections.Generic.IEnumerator&lt;'Element&gt;" Usage="tableQuery.GetEnumerator " />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.Generic.IEnumerable`1.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerator&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt einen Enumerator zurück, der die <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery`1" /> durchläuft.
            </summary>
        <returns>Ein <see cref="T:System.Collections.Generic.IEnumerator`1" /> für das <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery`1" />.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Provider">
      <MemberSignature Language="C#" Value="public System.Linq.IQueryProvider Provider { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Linq.IQueryProvider Provider" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.Provider" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Provider As IQueryProvider" />
      <MemberSignature Language="F#" Value="member this.Provider : System.Linq.IQueryProvider" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;.Provider" />
      <MemberType>Property</MemberType>
      <Implements>
        <InterfaceMember>P:System.Linq.IQueryable.Provider</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Linq.IQueryProvider</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Abfrageanbieter, der mit dieser Datenquelle zugeordnet ist.
            </summary>
        <value>Die <see cref="T:System.Linq.IQueryProvider" /> , die mit dieser Datenquelle verknüpft ist.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Select">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; Select (System.Collections.Generic.IList&lt;string&gt; columns);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!TElement&gt; Select(class System.Collections.Generic.IList`1&lt;string&gt; columns) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.Select(System.Collections.Generic.IList{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Function Select (columns As IList(Of String)) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.Select : System.Collections.Generic.IList&lt;string&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;" Usage="tableQuery.Select columns" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="columns" Type="System.Collections.Generic.IList&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="columns">Eine Liste von Zeichenfolgenobjekten mit den Eigenschaftsnamen der tabellenentitätseigenschaften zurückgibt, wenn die Abfrage ausgeführt wird.</param>
        <summary>
            Definiert die Eigenschaftsnamen der tabellenentitätseigenschaften, die bei der Ausführung der Tabellenabfrage zurückgegeben. 
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> -Instanzensatz mit tabellenentitätseigenschaften zurückgegeben.</returns>
        <remarks>Die select-Klausel ist bei einer Tabellenabfrage optional und wird verwendet, um die vom Server zurückgegebenen Tabelleneigenschaften einzuschränken. Standardmäßig wird eine Abfrage alle Eigenschaften aus der Tabellenentität zurück.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelectColumns">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IList&lt;string&gt; SelectColumns { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IList`1&lt;string&gt; SelectColumns" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.SelectColumns" />
      <MemberSignature Language="VB.NET" Value="Public Property SelectColumns As IList(Of String)" />
      <MemberSignature Language="F#" Value="member this.SelectColumns : System.Collections.Generic.IList&lt;string&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;.SelectColumns" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Eigenschaftsnamen der tabellenentitätseigenschaften, die bei der Ausführung der Tabellenabfrage zurückgegeben.
            </summary>
        <value>Eine Liste von Zeichenfolgen, die mit den Eigenschaftsnamen der tabellenentitätseigenschaften zurückgibt, wenn die Abfrage ausgeführt wird.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="System.Collections.IEnumerable.GetEnumerator">
      <MemberSignature Language="C#" Value="System.Collections.IEnumerator IEnumerable.GetEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method hidebysig newslot virtual instance class System.Collections.IEnumerator System.Collections.IEnumerable.GetEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.System#Collections#IEnumerable#GetEnumerator" />
      <MemberSignature Language="VB.NET" Value="Function GetEnumerator () As IEnumerator Implements IEnumerable.GetEnumerator" />
      <MemberType>Method</MemberType>
      <Implements>
        <InterfaceMember>M:System.Collections.IEnumerable.GetEnumerator</InterfaceMember>
      </Implements>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.IEnumerator</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Take">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; Take (Nullable&lt;int&gt; take);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!TElement&gt; Take(valuetype System.Nullable`1&lt;int32&gt; take) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.Take(System.Nullable{System.Int32})" />
      <MemberSignature Language="VB.NET" Value="Public Function Take (take As Nullable(Of Integer)) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.Take : Nullable&lt;int&gt; -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;" Usage="tableQuery.Take take" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="take" Type="System.Nullable&lt;System.Int32&gt;" />
      </Parameters>
      <Docs>
        <param name="take">Die maximale Anzahl von Entitäten für die Tabellenabfrage zurückgegeben werden soll.</param>
        <summary>
            Definiert die obere Grenze für die Anzahl der Entitäten, die die Abfrage zurückgibt.
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> -Instanzensatz mit der Anzahl von Entitäten zurückgeben.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TakeCount">
      <MemberSignature Language="C#" Value="public Nullable&lt;int&gt; TakeCount { get; set; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.Nullable`1&lt;int32&gt; TakeCount" />
      <MemberSignature Language="DocId" Value="P:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.TakeCount" />
      <MemberSignature Language="VB.NET" Value="Public Property TakeCount As Nullable(Of Integer)" />
      <MemberSignature Language="F#" Value="member this.TakeCount : Nullable&lt;int&gt; with get, set" Usage="Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;.TakeCount" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Nullable&lt;System.Int32&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft ab oder legt die Anzahl der Entitäten, die von die der Abfrage angegebenen, in der Tabellenabfrage zurückgegeben. 
            </summary>
        <value>Die maximale Anzahl von Entitäten für die Tabellenabfrage zurückgegeben werden soll.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Where">
      <MemberSignature Language="C#" Value="public Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt; Where (string filter);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig instance class Microsoft.WindowsAzure.Storage.Table.TableQuery`1&lt;!TElement&gt; Where(string filter) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.WindowsAzure.Storage.Table.TableQuery`1.Where(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function Where (filter As String) As TableQuery(Of TElement)" />
      <MemberSignature Language="F#" Value="member this.Where : string -&gt; Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;'Element&gt;" Usage="tableQuery.Where filter" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.WindowsAzure.Storage</AssemblyName>
        <AssemblyVersion>8.4.0.0</AssemblyVersion>
        <AssemblyVersion>8.7.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.WindowsAzure.Storage.Table.TableQuery&lt;TElement&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="filter" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="filter">Eine Zeichenfolge, die mit dem Filterausdruck für die Tabellenabfrage angewendet wird.</param>
        <summary>
            Definiert einen Filterausdruck für die Tabellenabfrage. Nur Entitäten, die den angegebenen Filterausdruck entsprechen, werden von der Abfrage zurückgegeben. 
            </summary>
        <returns>Ein <see cref="T:Microsoft.WindowsAzure.Storage.Table.TableQuery" /> -Instanzensatz mit dem Filter für Entitäten zurückgeben.</returns>
        <remarks>Festlegen eines Filterausdrucks ist optional. Standardmäßig werden alle Entitäten in der Tabelle zurückgegeben, wenn kein Filterausdruck in der Tabellenabfrage angegeben ist.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>