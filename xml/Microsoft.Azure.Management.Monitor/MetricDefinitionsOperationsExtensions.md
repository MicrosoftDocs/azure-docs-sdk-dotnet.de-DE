<Type Name="MetricDefinitionsOperationsExtensions" FullName="Microsoft.Azure.Management.Monitor.MetricDefinitionsOperationsExtensions">
  <TypeSignature Language="C#" Value="public static class MetricDefinitionsOperationsExtensions" />
  <TypeSignature Language="ILAsm" Value=".class public auto ansi abstract sealed beforefieldinit MetricDefinitionsOperationsExtensions extends System.Object" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Monitor.MetricDefinitionsOperationsExtensions" />
  <TypeSignature Language="VB.NET" Value="Public Module MetricDefinitionsOperationsExtensions" />
  <TypeSignature Language="F#" Value="type MetricDefinitionsOperationsExtensions = class" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
    <AssemblyVersion>0.18.0.0</AssemblyVersion>
    <AssemblyVersion>0.18.1.0</AssemblyVersion>
  </AssemblyInfo>
  <Base>
    <BaseTypeName>System.Object</BaseTypeName>
  </Base>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="128d7-101">Erweiterungsmethoden für MetricDefinitionsOperations.</span><span class="sxs-lookup"><span data-stu-id="128d7-101">Extension methods for MetricDefinitionsOperations.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="List">
      <MemberSignature Language="C#" Value="public static System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt; List (this Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations operations, string resourceUri);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt; List(class Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations operations, string resourceUri) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.MetricDefinitionsOperationsExtensions.List(Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations,System.String)" />
      <MemberSignature Language="VB.NET" Value="&lt;Extension()&gt;&#xA;Public Function List (operations As IMetricDefinitionsOperations, resourceUri As String) As IEnumerable(Of MetricDefinition)" />
      <MemberSignature Language="F#" Value="static member List : Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations * string -&gt; seq&lt;Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt;" Usage="Microsoft.Azure.Management.Monitor.MetricDefinitionsOperationsExtensions.List (operations, resourceUri)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="128d7-102">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="128d7-102">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="128d7-103">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="128d7-103">The identifier of the resource.</span></span>
            </param>
        <summary>
            <span data-ttu-id="128d7-104">Listet die metrikdefinitionen für die Ressource an.</span><span class="sxs-lookup"><span data-stu-id="128d7-104">Lists the metric definitions for the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAsync">
      <MemberSignature Language="C#" Value="public static System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt;&gt; ListAsync (this Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations operations, string resourceUri, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public static hidebysig class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt;&gt; ListAsync(class Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations operations, string resourceUri, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Monitor.MetricDefinitionsOperationsExtensions.ListAsync(Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="static member ListAsync : Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;seq&lt;Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt;&gt;" Usage="Microsoft.Azure.Management.Monitor.MetricDefinitionsOperationsExtensions.ListAsync (operations, resourceUri, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Monitor</AssemblyName>
        <AssemblyVersion>0.18.0.0</AssemblyVersion>
        <AssemblyVersion>0.18.1.0</AssemblyVersion>
      </AssemblyInfo>
      <Attributes>
        <Attribute>
          <AttributeName>System.Runtime.CompilerServices.AsyncStateMachine(typeof(Microsoft.Azure.Management.Monitor.MetricDefinitionsOperationsExtensions/&lt;ListAsync&gt;d__1))</AttributeName>
        </Attribute>
      </Attributes>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Monitor.Models.MetricDefinition&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="operations" Type="Microsoft.Azure.Management.Monitor.IMetricDefinitionsOperations" RefType="this" />
        <Parameter Name="resourceUri" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="operations">
            <span data-ttu-id="128d7-105">Die Operations-Gruppe für diese Erweiterungsmethode.</span><span class="sxs-lookup"><span data-stu-id="128d7-105">The operations group for this extension method.</span></span>
            </param>
        <param name="resourceUri">
            <span data-ttu-id="128d7-106">Der Bezeichner der Ressource.</span><span class="sxs-lookup"><span data-stu-id="128d7-106">The identifier of the resource.</span></span>
            </param>
        <param name="cancellationToken">
            <span data-ttu-id="128d7-107">Das Abbruchtoken.</span><span class="sxs-lookup"><span data-stu-id="128d7-107">The cancellation token.</span></span>
            </param>
        <summary>
            <span data-ttu-id="128d7-108">Listet die metrikdefinitionen für die Ressource an.</span><span class="sxs-lookup"><span data-stu-id="128d7-108">Lists the metric definitions for the resource.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>