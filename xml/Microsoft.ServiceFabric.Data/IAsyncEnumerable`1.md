<Type Name="IAsyncEnumerable&lt;T&gt;" FullName="Microsoft.ServiceFabric.Data.IAsyncEnumerable&lt;T&gt;">
  <TypeSignature Language="C#" Value="public interface IAsyncEnumerable&lt;out T&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAsyncEnumerable`1&lt;+ T&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAsyncEnumerable(Of Out T)" />
  <TypeSignature Language="F#" Value="type IAsyncEnumerable&lt;'T&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
    <AssemblyVersion>5.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="T">
      <Constraints>
        <ParameterAttribute>Covariant</ParameterAttribute>
      </Constraints>
    </TypeParameter>
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="T"><span data-ttu-id="48fef-101">Der Typ der aufzulistenden Objekte.</span><span class="sxs-lookup"><span data-stu-id="48fef-101">The type of objects to enumerate.</span></span></typeparam>
    <summary>
            <span data-ttu-id="48fef-102">Macht eine <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" /> der asynchronen Iteration durch eine Auflistung eines angegebenen Typs unterstützt.</span><span class="sxs-lookup"><span data-stu-id="48fef-102">Exposes an <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" /> which supports an asynchronous iteration over a collection of a specified type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetAsyncEnumerator">
      <MemberSignature Language="C#" Value="public Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;out T&gt; GetAsyncEnumerator ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.ServiceFabric.Data.IAsyncEnumerator`1&lt;!T&gt; GetAsyncEnumerator() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.ServiceFabric.Data.IAsyncEnumerable`1.GetAsyncEnumerator" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAsyncEnumerator () As IAsyncEnumerator(Of Out T)" />
      <MemberSignature Language="F#" Value="abstract member GetAsyncEnumerator : unit -&gt; Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;'T&gt;" Usage="iAsyncEnumerable.GetAsyncEnumerator " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.ServiceFabric.Data.Interfaces</AssemblyName>
        <AssemblyVersion>5.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.ServiceFabric.Data.IAsyncEnumerator&lt;T&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="48fef-103">Gibt eine <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" /> , asynchron die Auflistung durchläuft.</span><span class="sxs-lookup"><span data-stu-id="48fef-103">Returns an <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" /> that asynchronously iterates through the collection.</span></span>
            </summary>
        <returns><span data-ttu-id="48fef-104">Ein <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" /> , um asynchron Durchlaufen der Auflistung verwendet werden kann.</span><span class="sxs-lookup"><span data-stu-id="48fef-104">An <see cref="T:Microsoft.ServiceFabric.Data.IAsyncEnumerator`1" /> that can be used to asynchronously iterate through the collection.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>