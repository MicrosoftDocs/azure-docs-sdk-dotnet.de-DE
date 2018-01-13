<Type Name="IWithSrvRecordEntry&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntry&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSrvRecordEntry&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSrvRecordEntry`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntry`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSrvRecordEntry(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithSrvRecordEntry&lt;'ParentT&gt; = interface" />
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
            Die Stufe der SRV-Datensatzdefinition ermöglicht erste Service-Eintrag hinzufügen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithRecord">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntryOrAttachable&lt;ParentT&gt; WithRecord (string target, int port, int priority, int weight);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntryOrAttachable`1&lt;!ParentT&gt; WithRecord(string target, int32 port, int32 priority, int32 weight) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntry`1.WithRecord(System.String,System.Int32,System.Int32,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithRecord (target As String, port As Integer, priority As Integer, weight As Integer) As IWithSrvRecordEntryOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithRecord : string * int * int * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntryOrAttachable&lt;'ParentT&gt;" Usage="iWithSrvRecordEntry.WithRecord (target, port, priority, weight)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithSrvRecordEntryOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="target" Type="System.String" />
        <Parameter Name="port" Type="System.Int32" />
        <Parameter Name="priority" Type="System.Int32" />
        <Parameter Name="weight" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="target">Der kanonische Name des Zielhosts der Dienst ausgeführt wird.</param>
        <param name="port">Der Port, auf dem der Dienst begrenzt ist.</param>
        <param name="priority">Die Priorität der Zielhost senken dem Wert höher die Priorität.</param>
        <param name="weight">Die relative Gewichtung (bevorzugt), der die Datensätze mit der gleichen Priorität, die höher der Wert mehr die Voreinstellung.</param>
        <summary>
            Gibt einen Dienstdatensatz für einen Dienst an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>