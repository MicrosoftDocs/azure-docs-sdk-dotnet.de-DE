<Type Name="IDocumentQuery&lt;T&gt;" FullName="Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IDocumentQuery&lt;T&gt; : IDisposable, Microsoft.Azure.Documents.Linq.IDocumentQuery" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDocumentQuery`1&lt;T&gt; implements class Microsoft.Azure.Documents.Linq.IDocumentQuery, class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Documents.Linq.IDocumentQuery`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDocumentQuery(Of T)&#xA;Implements IDisposable, IDocumentQuery" />
  <TypeSignature Language="F#" Value="type IDocumentQuery&lt;'T&gt; = interface&#xA;    interface IDocumentQuery&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
    <AssemblyVersion>1.6.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.0.0</AssemblyVersion>
    <AssemblyVersion>1.7.1.0</AssemblyVersion>
  </AssemblyInfo>
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
    <AssemblyVersion>1.18.0.0</AssemblyVersion>
    <AssemblyVersion>1.19.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Documents.Linq.IDocumentQuery</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="8931a-101">Quelltyp der Abfrage</span><span class="sxs-lookup"><span data-stu-id="8931a-101">Source Query Type</span></span></typeparam>
    <summary>
            <span data-ttu-id="8931a-102">Stellt Methoden bereit, die abfragenpaginierung und asynchrone Ausführung im Azure-Cosmos-DB-Dienst zu unterstützen.</span><span class="sxs-lookup"><span data-stu-id="8931a-102">Provides methods to support query pagination and asynchronous execution in the Azure Cosmos DB service.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExecuteNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;dynamic&gt;&gt; ExecuteNextAsync (System.Threading.CancellationToken token = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;object&gt;&gt; ExecuteNextAsync(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.IDocumentQuery`1.ExecuteNextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteNextAsync (Optional token As CancellationToken = null) As Task(Of FeedResponse(Of Object))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteNextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;obj&gt;&gt;" Usage="iDocumentQuery.ExecuteNextAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;System.Object&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="token"><span data-ttu-id="8931a-103">(Optional) Die <see cref="T:System.Threading.CancellationToken" /> ermöglicht die Benachrichtigung, dass Vorgänge abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="8931a-103">(Optional) The <see cref="T:System.Threading.CancellationToken" /> allows for notification that operations should be cancelled.</span></span></param>
        <summary>
            <span data-ttu-id="8931a-104">Führt die Abfrage, und ruft die nächste Seite der Ergebnisse als dynamische Objekte in der Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="8931a-104">Executes the query and retrieves the next page of results as dynamic objects in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="8931a-105">Das Aufgabenobjekt für die asynchrone Antwort von der abfrageausführung.</span><span class="sxs-lookup"><span data-stu-id="8931a-105">The Task object for the asynchronous response from query execution.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExecuteNextAsync&lt;TResult&gt;">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;TResult&gt;&gt; ExecuteNextAsync&lt;TResult&gt; (System.Threading.CancellationToken token = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Documents.Client.FeedResponse`1&lt;!!TResult&gt;&gt; ExecuteNextAsync&lt;TResult&gt;(valuetype System.Threading.CancellationToken token) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Documents.Linq.IDocumentQuery`1.ExecuteNextAsync``1(System.Threading.CancellationToken)" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteNextAsync(Of TResult) (Optional token As CancellationToken = null) As Task(Of FeedResponse(Of TResult))" />
      <MemberSignature Language="F#" Value="abstract member ExecuteNextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;'Result&gt;&gt;" Usage="iDocumentQuery.ExecuteNextAsync token" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Documents.Client.FeedResponse&lt;TResult&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="TResult" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="token" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="TResult"><span data-ttu-id="8931a-106">Der Typ des Objekts in den Abfrageergebnissen zurückgegeben werden soll.</span><span class="sxs-lookup"><span data-stu-id="8931a-106">The type of the object returned in the query result.</span></span></typeparam>
        <param name="token"><span data-ttu-id="8931a-107">(Optional) Die <see cref="T:System.Threading.CancellationToken" /> ermöglicht die Benachrichtigung, dass Vorgänge abgebrochen werden soll.</span><span class="sxs-lookup"><span data-stu-id="8931a-107">(Optional) The <see cref="T:System.Threading.CancellationToken" /> allows for notification that operations should be cancelled.</span></span></param>
        <summary>
            <span data-ttu-id="8931a-108">Führt die Abfrage, und ruft die nächste Seite der Ergebnisse im Azure-Cosmos-DB-Dienst ab.</span><span class="sxs-lookup"><span data-stu-id="8931a-108">Executes the query and retrieves the next page of results in the Azure Cosmos DB service.</span></span>
            </summary>
        <returns><span data-ttu-id="8931a-109">Das Aufgabenobjekt für die asynchrone Antwort von der abfrageausführung.</span><span class="sxs-lookup"><span data-stu-id="8931a-109">The Task object for the asynchronous response from query execution.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HasMoreResults">
      <MemberSignature Language="C#" Value="public bool HasMoreResults { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HasMoreResults" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Documents.Linq.IDocumentQuery`1.HasMoreResults" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HasMoreResults As Boolean" />
      <MemberSignature Language="F#" Value="member this.HasMoreResults : bool" Usage="Microsoft.Azure.Documents.Linq.IDocumentQuery&lt;'T&gt;.HasMoreResults" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.DocumentDB.Core</AssemblyName>
        <AssemblyVersion>1.6.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.0.0</AssemblyVersion>
        <AssemblyVersion>1.7.1.0</AssemblyVersion>
      </AssemblyInfo>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Documents.Client</AssemblyName>
        <AssemblyVersion>1.18.0.0</AssemblyVersion>
        <AssemblyVersion>1.19.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="8931a-110">Ruft einen Wert, der angibt, ob es sind möglicherweise zusätzliche Ergebnisse, die aus der Abfrage in der Azure-Cosmos-DB-Dienst zurückgegeben werden können.</span><span class="sxs-lookup"><span data-stu-id="8931a-110">Gets a value indicating whether there are potentially additional results that can be returned from the query in the Azure Cosmos DB service.</span></span>
            </summary>
        <value><span data-ttu-id="8931a-111">Boolescher Wert, wenn es sind möglicherweise zusätzliche Ergebnisse, die von der Abfrage zurückgegeben werden können.</span><span class="sxs-lookup"><span data-stu-id="8931a-111">Boolean value representing if there are potentially additional results that can be returned from the query.</span></span></value>
        <remarks><span data-ttu-id="8931a-112">Anfänglich gibt "true" zurück.</span><span class="sxs-lookup"><span data-stu-id="8931a-112">Initially returns true.</span></span> <span data-ttu-id="8931a-113">Dieser Wert wird festgelegt werden, abhängig davon, ob die letzte Ausführung ein Fortsetzungstoken zurückgegeben.</span><span class="sxs-lookup"><span data-stu-id="8931a-113">This value is set based on whether the last execution returned a continuation token.</span></span></remarks>
      </Docs>
    </Member>
  </Members>
</Type>