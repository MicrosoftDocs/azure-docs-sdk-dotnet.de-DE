<Type Name="IWithDestinationAddressPrefix&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithDestinationAddressPrefix&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDestinationAddressPrefix&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDestinationAddressPrefix`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithDestinationAddressPrefix`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDestinationAddressPrefix(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDestinationAddressPrefix&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="20534-101">Der Rückgabetyp der WithAttach.attach().</span><span class="sxs-lookup"><span data-stu-id="20534-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="20534-102">Die Phase einer Route-Definition, die an das Ziel-Adresspräfix ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="20534-102">The stage of a route definition allowing to specify the destination address prefix.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType&lt;ParentT&gt; WithDestinationAddressPrefix (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType`1&lt;!ParentT&gt; WithDestinationAddressPrefix(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithDestinationAddressPrefix`1.WithDestinationAddressPrefix(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDestinationAddressPrefix (cidr As String) As IWithNextHopType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDestinationAddressPrefix : string -&gt; Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType&lt;'ParentT&gt;" Usage="iWithDestinationAddressPrefix.WithDestinationAddressPrefix cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Route.UpdateDefinition.IWithNextHopType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr"><span data-ttu-id="20534-103">Ein Adresspräfix, die in der CIDR-Schreibweise ausgedrückt wird.</span><span class="sxs-lookup"><span data-stu-id="20534-103">An address prefix expressed in the CIDR notation.</span></span></param>
        <summary>
            <span data-ttu-id="20534-104">Gibt das Zieladresspräfix, um die Route zu übernehmen.</span><span class="sxs-lookup"><span data-stu-id="20534-104">Specifies the destination address prefix to apply the route to.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="20534-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="20534-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>