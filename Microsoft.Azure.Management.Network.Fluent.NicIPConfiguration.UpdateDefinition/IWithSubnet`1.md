<Type Name="IWithSubnet&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithSubnet&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSubnet&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithSubnet`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithSubnet&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Der Rückgabetyp des endgültigen Attachable.attach().</typeparam>
    <summary>
            Die Stufe der Netzwerk-IP-Konfiguration Schnittstellendefinition taktmonitoren Subnetz angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt; WithSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP`1&lt;!ParentT&gt; WithSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithSubnet`1.WithSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (name As String) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithSubnet.WithSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.UpdateDefinition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Subnetzname.</param>
        <summary>
            Ordnen Sie die IP-Konfiguration der Netzwerkschnittstelle mit einem Subnetz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>