<Type Name="IBatchRequest&lt;TResponse&gt;" FullName="Microsoft.Azure.Batch.Protocol.IBatchRequest&lt;TResponse&gt;">
  <TypeSignature Language="C#" Value="public interface IBatchRequest&lt;TResponse&gt; : Microsoft.Azure.Batch.Protocol.IBatchRequest" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBatchRequest`1&lt;TResponse&gt; implements class Microsoft.Azure.Batch.Protocol.IBatchRequest" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Batch.Protocol.IBatchRequest`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBatchRequest(Of TResponse)&#xA;Implements IBatchRequest" />
  <TypeSignature Language="F#" Value="type IBatchRequest&lt;'Response&gt; = interface&#xA;    interface IBatchRequest" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
    <AssemblyVersion>7.1.0.0</AssemblyVersion>
    <AssemblyVersion>8.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="TResponse" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Batch.Protocol.IBatchRequest</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="TResponse"><span data-ttu-id="9abb3-101">Der Typ der Antwort vom Batch-Dienst zurückgegeben werden soll.</span><span class="sxs-lookup"><span data-stu-id="9abb3-101">The type of the response returned by the Batch service.</span></span></typeparam>
    <summary>
            <span data-ttu-id="9abb3-102">Stellt eine Anforderung an den Batch-Dienst mit einer bestimmten Antworttyp.</span><span class="sxs-lookup"><span data-stu-id="9abb3-102">Represents a request to the Batch Service with a particular response type.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ExecuteRequestAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;TResponse&gt; ExecuteRequestAsync ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;!TResponse&gt; ExecuteRequestAsync() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Batch.Protocol.IBatchRequest`1.ExecuteRequestAsync" />
      <MemberSignature Language="VB.NET" Value="Public Function ExecuteRequestAsync () As Task(Of TResponse)" />
      <MemberSignature Language="F#" Value="abstract member ExecuteRequestAsync : unit -&gt; System.Threading.Tasks.Task&lt;'Response&gt;" Usage="iBatchRequest.ExecuteRequestAsync " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Batch</AssemblyName>
        <AssemblyVersion>7.1.0.0</AssemblyVersion>
        <AssemblyVersion>8.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;TResponse&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="9abb3-103">Führt die Anforderung.</span><span class="sxs-lookup"><span data-stu-id="9abb3-103">Executes the request.</span></span>
            </summary>
        <returns><span data-ttu-id="9abb3-104">Einen asynchronen Vorgang des Rückgabetyps <typeparamref name="TResponse" />.</span><span class="sxs-lookup"><span data-stu-id="9abb3-104">An asynchronous operation of return type <typeparamref name="TResponse" />.</span></span></returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>