<Type Name="IWithAddressPrefix&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAddressPrefix&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAddressPrefix&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddressPrefix`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAddressPrefix`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddressPrefix(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAddressPrefix&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Der übergeordnete Typ.</typeparam>
    <summary>
            Die Phase der subnetzdefinition ermöglicht den Adressraum für das Subnetz an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAddressPrefix">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt; WithAddressPrefix (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach`1&lt;!ParentT&gt; WithAddressPrefix(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAddressPrefix`1.WithAddressPrefix(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAddressPrefix (cidr As String) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAddressPrefix : string -&gt; Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;'ParentT&gt;" Usage="iWithAddressPrefix.WithAddressPrefix cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Subnet.Definition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr">Die IP-Adresse Speicherplatz Präfix mithilfe der CIDR-Notation.</param>
        <summary>
            Gibt den IP-Adressraum des Subnetzes innerhalb des Adressraums des Netzwerks an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>