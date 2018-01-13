<Type Name="IPagedEnumerator&lt;T&gt;" FullName="Microsoft.Azure.Batch.IPagedEnumerator&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IPagedEnumerator&lt;T&gt; : IDisposable" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPagedEnumerator`1&lt;T&gt; implements class System.IDisposable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.IPagedEnumerator`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPagedEnumerator(Of T)&#xA;Implements IDisposable" />
  <TypeSignature Language="F#" Value="type IPagedEnumerator&lt;'T&gt; = interface&#xA;    interface IDisposable" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>System.IDisposable</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="T"><span data-ttu-id="42c29-101">Der Typ des Enumerators.</span><span class="sxs-lookup"><span data-stu-id="42c29-101">The type of the enumerator.</span></span></typeparam>
    <summary>
            <span data-ttu-id="42c29-102">Ein Enumerator, der einen asynchronen Mechanismus für die Iteration verfügbar macht.</span><span class="sxs-lookup"><span data-stu-id="42c29-102">An enumerator which exposes an asynchronous mechanism for iteration.</span></span>
            
            <span data-ttu-id="42c29-103">Enumerator-Instanzen sind nicht hinsichtlich.</span><span class="sxs-lookup"><span data-stu-id="42c29-103">Enumerator instances are not threadsafe.</span></span>
            
            <span data-ttu-id="42c29-104">Each-Enumerator Ruft die Auflistung vom Server ab.</span><span class="sxs-lookup"><span data-stu-id="42c29-104">Each enumerator fetches the collection from the server.</span></span> <span data-ttu-id="42c29-105">Daher sehen each-Enumerator unterschiedliche Daten (Kollektionsgröße, Inhalt usw.).</span><span class="sxs-lookup"><span data-stu-id="42c29-105">As a consequence, each enumerator can see different data (collection size, contents, etc.).</span></span>
            
            <span data-ttu-id="42c29-106">Um mehrere Abruf der Daten vom Server über die häufige Verwendung Foreach/ForeachAsync und andere Vorgänge zu vermeiden, sollte vorsichtig vorgenommen werden.</span><span class="sxs-lookup"><span data-stu-id="42c29-106">Care should be taken to avoid multiple retrievals of the data from the server via casual use of foreach/ForeachAsync and other collection operations.</span></span>
            
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Current">
      <MemberSignature Language="C#" Value="public T Current { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance !T Current" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Batch.IPagedEnumerator`1.Current" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Current As T" />
      <MemberSignature Language="F#" Value="member this.Current : 'T" Usage="Microsoft.Azure.Batch.IPagedEnumerator&lt;'T&gt;.Current" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>T</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="42c29-107">Ruft das Element in der Auflistung an der aktuellen Position des Enumerators ab.</span><span class="sxs-lookup"><span data-stu-id="42c29-107">Gets the element in the collection at the current position of the enumerator.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MoveNextAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;bool&gt; MoveNextAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;bool&gt; MoveNextAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.IPagedEnumerator`1.MoveNextAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member MoveNextAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;bool&gt;" Usage="iPagedEnumerator.MoveNextAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Boolean&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="42c29-108">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="42c29-108">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="42c29-109">Startet einen asynchronen Aufruf an den Enumerator auf das nächste Element der Auflistung.</span><span class="sxs-lookup"><span data-stu-id="42c29-109">Begins an asynchronous call to advance the enumerator to the next element of the collection.</span></span>
            </summary>
        <returns><span data-ttu-id="42c29-110">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="42c29-110">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResetAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ResetAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.IPagedEnumerator`1.ResetAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResetAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iPagedEnumerator.ResetAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken"><span data-ttu-id="42c29-111">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="42c29-111">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="42c29-112">Startet einen asynchronen Aufruf an den Enumerator auf seine anfängliche Position festgelegt, das vor dem ersten Element in der Auflistung ist.</span><span class="sxs-lookup"><span data-stu-id="42c29-112">Begins an asynchronous call to set the enumerator to its initial position, which is before the first element in the collection.</span></span>
            </summary>
        <returns><span data-ttu-id="42c29-113">Ein <see cref="T:System.Threading.Tasks.Task" />-Objekt, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="42c29-113">A <see cref="T:System.Threading.Tasks.Task" /> object that represents the asynchronous operation.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>