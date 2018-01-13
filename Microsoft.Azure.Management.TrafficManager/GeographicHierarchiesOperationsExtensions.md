<Type Name="GeographicHierarchiesOperationsExtensions" FullName="Microsoft.Azure.Management.TrafficManager.GeographicHierarchiesOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class GeographicHierarchiesOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit GeographicHierarchiesOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.GeographicHierarchiesOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module GeographicHierarchiesOperationsExtensions" />
  <TypeSignature Language="F#" Value="type GeographicHierarchiesOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
    <AssemblyVersion>2.0.0.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="9c231-101">Erweiterungsmethoden für GeographicHierarchiesOperations.</span><span class="sxs-lookup"><span data-stu-id="9c231-101">Extension methods for GeographicHierarchiesOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetDefault">
      <MemberSignature Language="C#" Value="public static Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy GetDefault (this Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations operations);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy GetDefault(class Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations operations) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.GeographicHierarchiesOperationsExtensions.GetDefault(Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function GetDefault (operations As IGeographicHierarchiesOperations) As TrafficManagerGeographicHierarchy" />
      <MemberSignature Language="F#" Value="static member GetDefault : Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations -&gt; Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy" Usage="Microsoft.Azure.Management.TrafficManager.GeographicHierarchiesOperationsExtensions.GetDefault operations" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations" RefType="this" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c231-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c231-102">The operations group for this extension method.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c231-103">Ruft die standardmäßige geografische Hierarchie, die von der geografischen datenverkehrrouting-Methode verwendet.</span><span class="sxs-lookup"><span data-stu-id="9c231-103">Gets the default Geographic Hierarchy used by the Geographic traffic routing method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetDefaultAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy&gt; GetDefaultAsync (this Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations operations, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy&gt; GetDefaultAsync(class Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations operations, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.TrafficManager.GeographicHierarchiesOperationsExtensions.GetDefaultAsync(Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member GetDefaultAsync : Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy&gt;" Usage="Microsoft.Azure.Management.TrafficManager.GeographicHierarchiesOperationsExtensions.GetDefaultAsync (operations, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager</AssemblyName>
        <AssemblyVersion>2.0.0.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.TrafficManager.GeographicHierarchiesOperationsExtensions/&lt;GetDefaultAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.TrafficManager.Models.TrafficManagerGeographicHierarchy&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.TrafficManager.IGeographicHierarchiesOperations" RefType="this" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="9c231-104">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="9c231-104">The operations group for this extension method.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="9c231-105">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="9c231-105">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="9c231-106">Ruft die standardmäßige geografische Hierarchie, die von der geografischen datenverkehrrouting-Methode verwendet.</span><span class="sxs-lookup"><span data-stu-id="9c231-106">Gets the default Geographic Hierarchy used by the Geographic traffic routing method.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>