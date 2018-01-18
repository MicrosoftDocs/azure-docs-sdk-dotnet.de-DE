<Type Name="PagedEnumerableExtensions" FullName="Microsoft.Azure.Batch.PagedEnumerableExtensions">
  <TypeSignature Language="C#" Value="public static class PagedEnumerableExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit PagedEnumerableExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.PagedEnumerableExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module PagedEnumerableExtensions" />
  <TypeSignature Language="F#" Value="type PagedEnumerableExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="32b05-101">Stellt einen Satz statischer (Shared in Visual Basic) Methoden zum Arbeiten mit Sequenzen, die implementieren <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />.</span><span class="sxs-lookup"><span data-stu-id="32b05-101">Provides a set of static (Shared in Visual Basic) methods for working with sequences that implement <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ForEachAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ForEachAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, Action&lt;T&gt; body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ForEachAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, class System.Action`1&lt;!!T&gt; body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Action{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForEachAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * Action&lt;'T&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync (source, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ForEachAsync&gt;d__2`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="body" Type="System.Action&lt;T&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source"><span data-ttu-id="32b05-102">Die <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> zu durchlaufen.</span><span class="sxs-lookup"><span data-stu-id="32b05-102">The <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> to iterate over.</span></span></param>
        <param name="body"><span data-ttu-id="32b05-103">Der Delegat, führen Sie für jedes Element im <paramref name="source" />.</span><span class="sxs-lookup"><span data-stu-id="32b05-103">The delegate to execute for each element in <paramref name="source" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="32b05-104">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="32b05-104">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="32b05-105">Führt eine Iteration durch eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> Sequenz Aufrufs eines synchronen Delegaten für jedes Element.</span><span class="sxs-lookup"><span data-stu-id="32b05-105">Iterates over an <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> sequence, invoking a synchronous delegate for each element.</span></span>
            </summary>
        <returns><span data-ttu-id="32b05-106">Ein <see cref="T:System.Threading.Tasks.Task" /> , die der Iteration Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="32b05-106">A <see cref="T:System.Threading.Tasks.Task" /> that represents the iteration operation.</span></span> <span data-ttu-id="32b05-107">Die Aufgabe abgeschlossen ist, wenn die Iteration abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="32b05-107">The task completes when iteration is complete.</span></span></returns>
        <remarks><span data-ttu-id="32b05-108">Diese Methode verarbeitet Elemente sequenziell, nicht gleichzeitig.</span><span class="sxs-lookup"><span data-stu-id="32b05-108">This method processes elements sequentially, not concurrently.</span></span>  <span data-ttu-id="32b05-109">D. h. Abschluss für jedes Element in der Sequenz, die-Methode des Delegaten vor der Verarbeitung des nächsten Elements.</span><span class="sxs-lookup"><span data-stu-id="32b05-109">That is, for each element in the sequence, the method completes execution of the delegate before processing the next element.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ForEachAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ForEachAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, Func&lt;T,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt; body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ForEachAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, class System.Func`3&lt;!!T, valuetype System.Threading.CancellationToken, class System.Threading.Tasks.Task&gt; body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Func{``0,System.Threading.CancellationToken,System.Threading.Tasks.Task},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForEachAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * Func&lt;'T, System.Threading.CancellationToken, System.Threading.Tasks.Task&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync (source, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ForEachAsync&gt;d__1`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="body" Type="System.Func&lt;T,System.Threading.CancellationToken,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source"><span data-ttu-id="32b05-110">Die <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> zu durchlaufen.</span><span class="sxs-lookup"><span data-stu-id="32b05-110">The <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> to iterate over.</span></span></param>
        <param name="body"><span data-ttu-id="32b05-111">Asynchrone Delegaten auszuführende für jedes Element im <paramref name="source" />.</span><span class="sxs-lookup"><span data-stu-id="32b05-111">The asynchronous delegate to execute for each element in <paramref name="source" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="32b05-112">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="32b05-112">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="32b05-113">Führt eine Iteration durch eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> Sequenz, die einen asynchronen Delegaten für jedes Element aufrufen.</span><span class="sxs-lookup"><span data-stu-id="32b05-113">Iterates over an <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> sequence, invoking an asynchronous delegate for each element.</span></span>
            </summary>
        <returns><span data-ttu-id="32b05-114">Ein <see cref="T:System.Threading.Tasks.Task" /> , die der Iteration Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="32b05-114">A <see cref="T:System.Threading.Tasks.Task" /> that represents the iteration operation.</span></span> <span data-ttu-id="32b05-115">Die Aufgabe abgeschlossen ist, wenn die Iteration abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="32b05-115">The task completes when iteration is complete.</span></span></returns>
        <remarks><span data-ttu-id="32b05-116">Diese Methode verarbeitet Elemente sequenziell, nicht gleichzeitig.</span><span class="sxs-lookup"><span data-stu-id="32b05-116">This method processes elements sequentially, not concurrently.</span></span>  <span data-ttu-id="32b05-117">D. h., wartet der asynchronen Delegaten für jedes Element in der Sequenz, die Methode vor der Verarbeitung des nächsten Elements auf.</span><span class="sxs-lookup"><span data-stu-id="32b05-117">That is, for each element in the sequence, the method awaits the asynchronous delegate before processing the next element.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ForEachAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task ForEachAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, Func&lt;T,System.Threading.Tasks.Task&gt; body, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task ForEachAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, class System.Func`2&lt;!!T, class System.Threading.Tasks.Task&gt; body, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Func{``0,System.Threading.Tasks.Task},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ForEachAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * Func&lt;'T, System.Threading.Tasks.Task&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ForEachAsync (source, body, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ForEachAsync&gt;d__0`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="body" Type="System.Func&lt;T,System.Threading.Tasks.Task&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source"><span data-ttu-id="32b05-118">Die <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> zu durchlaufen.</span><span class="sxs-lookup"><span data-stu-id="32b05-118">The <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> to iterate over.</span></span></param>
        <param name="body"><span data-ttu-id="32b05-119">Asynchrone Delegaten auszuführende für jedes Element im <paramref name="source" />.</span><span class="sxs-lookup"><span data-stu-id="32b05-119">The asynchronous delegate to execute for each element in <paramref name="source" />.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="32b05-120">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="32b05-120">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="32b05-121">Führt eine Iteration durch eine <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> Sequenz, die einen asynchronen Delegaten für jedes Element aufrufen.</span><span class="sxs-lookup"><span data-stu-id="32b05-121">Iterates over an <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> sequence, invoking an asynchronous delegate for each element.</span></span>
            </summary>
        <returns><span data-ttu-id="32b05-122">Ein <see cref="T:System.Threading.Tasks.Task" /> , die der Iteration Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="32b05-122">A <see cref="T:System.Threading.Tasks.Task" /> that represents the iteration operation.</span></span> <span data-ttu-id="32b05-123">Die Aufgabe abgeschlossen ist, wenn die Iteration abgeschlossen ist.</span><span class="sxs-lookup"><span data-stu-id="32b05-123">The task completes when iteration is complete.</span></span></returns>
        <remarks><span data-ttu-id="32b05-124">Diese Methode verarbeitet Elemente sequenziell, nicht gleichzeitig.</span><span class="sxs-lookup"><span data-stu-id="32b05-124">This method processes elements sequentially, not concurrently.</span></span>  <span data-ttu-id="32b05-125">D. h., wartet der asynchronen Delegaten für jedes Element in der Sequenz, die Methode vor der Verarbeitung des nächsten Elements auf.</span><span class="sxs-lookup"><span data-stu-id="32b05-125">That is, for each element in the sequence, the method awaits the asynchronous delegate before processing the next element.</span></span></remarks>
      </Docs>
    </Member>
    <Member MemberName="ToListAsync&lt;T&gt;">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt; ToListAsync&lt;T&gt; (this Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt; source, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.List`1&lt;!!T&gt;&gt; ToListAsync&lt;T&gt;(class Microsoft.Azure.Batch.IPagedEnumerable`1&lt;!!T&gt; source, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.PagedEnumerableExtensions.ToListAsync``1(Microsoft.Azure.Batch.IPagedEnumerable{``0},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ToListAsync : Microsoft.Azure.Batch.IPagedEnumerable&lt;'T&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;'T&gt;&gt;" Usage="Microsoft.Azure.Batch.PagedEnumerableExtensions.ToListAsync (source, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Batch.PagedEnumerableExtensions/&lt;ToListAsync&gt;d__3`1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.List&lt;T&gt;&gt;</ReturnType>
      </ReturnValue>
      <TypeParameters>
        <TypeParameter Name="T" />
      </TypeParameters>
      <Parameters>
        <Parameter Name="source" Type="Microsoft.Azure.Batch.IPagedEnumerable&lt;T&gt;" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <typeparam name="T">To be added.</typeparam>
        <param name="source"><span data-ttu-id="32b05-126">Die <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> zum Erstellen einer Liste aus.</span><span class="sxs-lookup"><span data-stu-id="32b05-126">The <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" /> to create a list from.</span></span></param>
        <param name="cancellationToken"><span data-ttu-id="32b05-127">Ein <see cref="T:System.Threading.CancellationToken" /> für die Steuerung der Lebensdauer eines asynchronen Vorgangs.</span><span class="sxs-lookup"><span data-stu-id="32b05-127">A <see cref="T:System.Threading.CancellationToken" /> for controlling the lifetime of the asynchronous operation.</span></span></param>
        <summary>
            <span data-ttu-id="32b05-128">Erstellt ein <see cref="T:System.Collections.Generic.List`1" /> aus einem <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />.</span><span class="sxs-lookup"><span data-stu-id="32b05-128">Creates a <see cref="T:System.Collections.Generic.List`1" /> from an <see cref="T:Microsoft.Azure.Batch.IPagedEnumerable`1" />.</span></span>
            </summary>
        <returns><span data-ttu-id="32b05-129">Ein <see cref="T:System.Threading.Tasks.Task`1" />-Element, das den asynchronen Vorgang darstellt.</span><span class="sxs-lookup"><span data-stu-id="32b05-129">A <see cref="T:System.Threading.Tasks.Task`1" /> that represents the asynchronous operation.</span></span> <span data-ttu-id="32b05-130">Das Ergebnis der Aufgabe ist eine <see cref="T:System.Collections.Generic.List`1" /> , die alle Elemente der Quellsequenz enthält.</span><span class="sxs-lookup"><span data-stu-id="32b05-130">The result of the task is a <see cref="T:System.Collections.Generic.List`1" /> containing all elements of the source sequence.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>