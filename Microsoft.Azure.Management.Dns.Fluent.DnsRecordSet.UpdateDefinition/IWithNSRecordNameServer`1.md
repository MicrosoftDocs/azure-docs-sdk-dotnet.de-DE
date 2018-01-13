<Type Name="IWithNSRecordNameServer&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithNSRecordNameServer&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNSRecordNameServer&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNSRecordNameServer`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithNSRecordNameServer`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNSRecordNameServer(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNSRecordNameServer&lt;'ParentT&gt; = interface" />
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
            Die Phase der NS Ressourceneintragssatz Definition ermöglichen einen NS-Eintrag hinzuzufügen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNameServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithNSRecordNameServerOrAttachable&lt;ParentT&gt; WithNameServer (string nameServerHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithNSRecordNameServerOrAttachable`1&lt;!ParentT&gt; WithNameServer(string nameServerHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithNSRecordNameServer`1.WithNameServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNameServer (nameServerHostName As String) As IWithNSRecordNameServerOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNameServer : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithNSRecordNameServerOrAttachable&lt;'ParentT&gt;" Usage="iWithNSRecordNameServer.WithNameServer nameServerHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithNSRecordNameServerOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameServerHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameServerHostName">Der Server den Hostnamen.</param>
        <summary>
            Erstellt einen Namenservereintrag mit dem Namenserver bereitgestellten in diesen Datensatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>