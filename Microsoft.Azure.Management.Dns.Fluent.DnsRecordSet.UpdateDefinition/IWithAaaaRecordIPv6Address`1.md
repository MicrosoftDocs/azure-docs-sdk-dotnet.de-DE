<Type Name="IWithAaaaRecordIPv6Address&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAaaaRecordIPv6Address&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithAaaaRecordIPv6Address&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAaaaRecordIPv6Address`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAaaaRecordIPv6Address`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAaaaRecordIPv6Address(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithAaaaRecordIPv6Address&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Der Rückgabetyp der WithAttach.attach().</typeparam>
    <summary>
            Die Phase der AAAA-Eintrag festgelegt Definition ermöglicht erste AAAA-Eintrag hinzufügen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIPv6Address">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAaaaRecordIPv6AddressOrAttachable&lt;ParentT&gt; WithIPv6Address (string ipv6Address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAaaaRecordIPv6AddressOrAttachable`1&lt;!ParentT&gt; WithIPv6Address(string ipv6Address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAaaaRecordIPv6Address`1.WithIPv6Address(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPv6Address (ipv6Address As String) As IWithAaaaRecordIPv6AddressOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithIPv6Address : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAaaaRecordIPv6AddressOrAttachable&lt;'ParentT&gt;" Usage="iWithAaaaRecordIPv6Address.WithIPv6Address ipv6Address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithAaaaRecordIPv6AddressOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipv6Address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipv6Address">Die IPv6-Adresse.</param>
        <summary>
            Erstellt ein (AAAA)-Ressourceneintrag mit die angegebene IPv6-Adresse in diesen Datensatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>