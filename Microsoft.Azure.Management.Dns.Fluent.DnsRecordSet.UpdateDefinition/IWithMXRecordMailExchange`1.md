<Type Name="IWithMXRecordMailExchange&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithMXRecordMailExchange&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithMXRecordMailExchange&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMXRecordMailExchange`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithMXRecordMailExchange`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMXRecordMailExchange(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithMXRecordMailExchange&lt;'ParentT&gt; = interface" />
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
            Legen Sie die Phase des MX-Eintrags Definition erste MX-Eintrag hinzufügen, sodass.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMailExchange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithMXRecordMailExchangeOrAttachable&lt;ParentT&gt; WithMailExchange (string mailExchangeHostName, int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithMXRecordMailExchangeOrAttachable`1&lt;!ParentT&gt; WithMailExchange(string mailExchangeHostName, int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithMXRecordMailExchange`1.WithMailExchange(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMailExchange (mailExchangeHostName As String, priority As Integer) As IWithMXRecordMailExchangeOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMailExchange : string * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithMXRecordMailExchangeOrAttachable&lt;'ParentT&gt;" Usage="iWithMXRecordMailExchange.WithMailExchange (mailExchangeHostName, priority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IWithMXRecordMailExchangeOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mailExchangeHostName" Type="System.String" />
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="mailExchangeHostName">Der Hostname des Exchange-Mailservers.</param>
        <param name="priority">Die Priorität für die Exchange-Mailhost senken dem Wert höher die Priorität.</param>
        <summary>
            Erstellt und einen MX-Eintrag mit dem bereitgestellten e-Mail-Exchange-Server in dieser Datensatzgruppe Priorität zugewiesen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>