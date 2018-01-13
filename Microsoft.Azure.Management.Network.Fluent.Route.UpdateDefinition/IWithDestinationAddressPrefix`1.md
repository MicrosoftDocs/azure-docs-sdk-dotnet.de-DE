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
    <typeparam name="ParentT">Der Rückgabetyp der WithAttach.attach().</typeparam>
    <summary>
            Die Phase einer Route-Definition, die an das Ziel-Adresspräfix ermöglicht.
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
        <param name="cidr">Ein Adresspräfix, die in der CIDR-Schreibweise ausgedrückt wird.</param>
        <summary>
            Gibt das Zieladresspräfix, um die Route zu übernehmen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>