<Type Name="IWithRouteTable&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithRouteTable&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithRouteTable&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRouteTable`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithRouteTable`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRouteTable(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithRouteTable&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="a39dd-101">Der Typ des übergeordneten Netzwerks.</span><span class="sxs-lookup"><span data-stu-id="a39dd-101">The parent network type.</span></span></typeparam>
    <summary>
            <span data-ttu-id="a39dd-102">Die Phase der subnetzdefinition eines, an eine Routingtabelle mit dem Subnetz zuordnen können.</span><span class="sxs-lookup"><span data-stu-id="a39dd-102">The stage of a subnet definition allowing to specify a route table to associate with the subnet.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt; WithExistingRouteTable (Microsoft.Azure.Management.Network.Fluent.IRouteTable routeTable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach`1&lt;!ParentT&gt; WithExistingRouteTable(class Microsoft.Azure.Management.Network.Fluent.IRouteTable routeTable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithRouteTable`1.WithExistingRouteTable(Microsoft.Azure.Management.Network.Fluent.IRouteTable)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingRouteTable (routeTable As IRouteTable) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingRouteTable : Microsoft.Azure.Management.Network.Fluent.IRouteTable -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRouteTable.WithExistingRouteTable routeTable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="routeTable" Type="Microsoft.Azure.Management.Network.Fluent.IRouteTable" />
      </Parameters>
      <Docs>
        <param name="routeTable"><span data-ttu-id="a39dd-103">Eine vorhandene Routentabelle zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="a39dd-103">An existing route table to associate.</span></span></param>
        <summary>
            <span data-ttu-id="a39dd-104">Gibt eine vorhandene Routentabelle mit dem Subnetz zuordnen.</span><span class="sxs-lookup"><span data-stu-id="a39dd-104">Specifies an existing route table to associate with the subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a39dd-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="a39dd-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingRouteTable">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt; WithExistingRouteTable (string resourceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach`1&lt;!ParentT&gt; WithExistingRouteTable(string resourceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithRouteTable`1.WithExistingRouteTable(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingRouteTable (resourceId As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingRouteTable : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithRouteTable.WithExistingRouteTable resourceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="resourceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="resourceId"><span data-ttu-id="a39dd-106">Die Ressourcen-ID einer vorhandenen Tabelle für die Route.</span><span class="sxs-lookup"><span data-stu-id="a39dd-106">The resource ID of an existing route table.</span></span></param>
        <summary>
            <span data-ttu-id="a39dd-107">Gibt eine vorhandene Routentabelle mit dem Subnetz zuordnen.</span><span class="sxs-lookup"><span data-stu-id="a39dd-107">Specifies an existing route table to associate with the subnet.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="a39dd-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="a39dd-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>