<Type Name="OperationsExtensions" FullName="Microsoft.Azure.Management.EventGrid.OperationsExtensions">
  <TypeSignature Language="C#" Value="public static class OperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit OperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.EventGrid.OperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module OperationsExtensions" />
  <TypeSignature Language="F#" Value="type OperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
    <AssemblyVersion>1.0.0.0</AssemblyVersion>
    <AssemblyVersion>1.1.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="edf09-101">Erweiterungsmethoden für Vorgänge.</span><span class="sxs-lookup"><span data-stu-id="edf09-101">Extension methods for Operations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Operation&gt; List (this Microsoft.Azure.Management.EventGrid.IOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Operation&gt; List(class Microsoft.Azure.Management.EventGrid.IOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.OperationsExtensions.List(Microsoft.Azure.Management.EventGrid.IOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IOperations) As IEnumerable(Of Operation)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.EventGrid.IOperations -&gt; seq&lt;Microsoft.Azure.Management.EventGrid.Models.Operation&gt;" Usage="Microsoft.Azure.Management.EventGrid.OperationsExtensions.List operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Operation&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edf09-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="edf09-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edf09-103">Auflisten von Vorgängen verfügbar</span><span class="sxs-lookup"><span data-stu-id="edf09-103">List available operations</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="edf09-104">Liste der verfügbaren Vorgänge vom Ressourcenanbieter Microsoft.EventGrid unterstützt</span><span class="sxs-lookup"><span data-stu-id="edf09-104">List the available operations supported by the Microsoft.EventGrid resource provider</span></span>
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Operation&gt;&gt; ListAsync (this Microsoft.Azure.Management.EventGrid.IOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.EventGrid.Models.Operation&gt;&gt; ListAsync(class Microsoft.Azure.Management.EventGrid.IOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.EventGrid.OperationsExtensions.ListAsync(Microsoft.Azure.Management.EventGrid.IOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.EventGrid.IOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.EventGrid.Models.Operation&gt;&gt;" Usage="Microsoft.Azure.Management.EventGrid.OperationsExtensions.ListAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.EventGrid</AssemblyName>
        <AssemblyVersion>1.0.0.0</AssemblyVersion>
        <AssemblyVersion>1.1.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.EventGrid.OperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.EventGrid.Models.Operation&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.EventGrid.IOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="edf09-105">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="edf09-105">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="edf09-106">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="edf09-106">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="edf09-107">Auflisten von Vorgängen verfügbar</span><span class="sxs-lookup"><span data-stu-id="edf09-107">List available operations</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>
            <span data-ttu-id="edf09-108">Liste der verfügbaren Vorgänge vom Ressourcenanbieter Microsoft.EventGrid unterstützt</span><span class="sxs-lookup"><span data-stu-id="edf09-108">List the available operations supported by the Microsoft.EventGrid resource provider</span></span>
            </remarks>
      </Docs>
    </Member>
  </Members>
</Type>