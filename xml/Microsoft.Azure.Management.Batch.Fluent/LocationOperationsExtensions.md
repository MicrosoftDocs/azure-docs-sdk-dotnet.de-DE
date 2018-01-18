<Type Name="LocationOperationsExtensions" FullName="Microsoft.Azure.Management.Batch.Fluent.LocationOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class LocationOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit LocationOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Batch.Fluent.LocationOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module LocationOperationsExtensions" />
  <TypeSignature Language="F#" Value="type LocationOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="718c5-101">Erweiterungsmethoden für LocationOperations.</span><span class="sxs-lookup"><span data-stu-id="718c5-101">Extension methods for LocationOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetQuotasAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner&gt; GetQuotasAsync (this Microsoft.Azure.Management.Batch.Fluent.ILocationOperations operations, string locationName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner&gt; GetQuotasAsync(class Microsoft.Azure.Management.Batch.Fluent.ILocationOperations operations, string locationName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Batch.Fluent.LocationOperationsExtensions.GetQuotasAsync(Microsoft.Azure.Management.Batch.Fluent.ILocationOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetQuotasAsync : Microsoft.Azure.Management.Batch.Fluent.ILocationOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner&gt;" Usage="Microsoft.Azure.Management.Batch.Fluent.LocationOperationsExtensions.GetQuotasAsync (operations, locationName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Batch.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Batch.Fluent.LocationOperationsExtensions/&lt;GetQuotasAsync&gt;d__0))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Batch.Fluent.Models.BatchLocationQuotaInner&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Batch.Fluent.ILocationOperations" RefType="this" />
        <Parameter Name="locationName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="718c5-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="718c5-102">The operations group for this extension method.</span></span>
            </param>
        <param name="locationName">
            <span data-ttu-id="718c5-103">Die gewünschte Region für die Kontingente.</span><span class="sxs-lookup"><span data-stu-id="718c5-103">The desired region for the quotas.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="718c5-104">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="718c5-104">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="718c5-105">Ruft die Batch-Dienst-Kontingente für das angegebene Abonnement am angegebenen Speicherort ab.</span><span class="sxs-lookup"><span data-stu-id="718c5-105">Gets the Batch service quotas for the specified subscription at the given location.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>