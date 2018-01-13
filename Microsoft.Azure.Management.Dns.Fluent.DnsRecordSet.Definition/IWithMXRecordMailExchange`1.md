<Type Name="IWithMXRecordMailExchange&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchange&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithMXRecordMailExchange&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMXRecordMailExchange`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchange`1" />
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
    <typeparam name="ParentT"><span data-ttu-id="ff8c2-101">Der Rückgabetyp der WithAttach.attach().</span><span class="sxs-lookup"><span data-stu-id="ff8c2-101">The return type of  WithAttach.attach().</span></span></typeparam>
    <summary>
            <span data-ttu-id="ff8c2-102">Legen Sie die Phase des MX-Eintrags Definition erste MX-Eintrag hinzufügen, sodass.</span><span class="sxs-lookup"><span data-stu-id="ff8c2-102">The stage of the MX record set definition allowing to add first MX record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMailExchange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchangeOrAttachable&lt;ParentT&gt; WithMailExchange (string mailExchangeHostName, int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchangeOrAttachable`1&lt;!ParentT&gt; WithMailExchange(string mailExchangeHostName, int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchange`1.WithMailExchange(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMailExchange (mailExchangeHostName As String, priority As Integer) As IWithMXRecordMailExchangeOrAttachable(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithMailExchange : string * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchangeOrAttachable&lt;'ParentT&gt;" Usage="iWithMXRecordMailExchange.WithMailExchange (mailExchangeHostName, priority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IWithMXRecordMailExchangeOrAttachable&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mailExchangeHostName" Type="System.String" />
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="mailExchangeHostName"><span data-ttu-id="ff8c2-103">Der Hostname des Exchange-Mailservers.</span><span class="sxs-lookup"><span data-stu-id="ff8c2-103">The host name of the mail exchange server.</span></span></param>
        <param name="priority"><span data-ttu-id="ff8c2-104">Die Priorität für die Exchange-Mailhost senken dem Wert höher die Priorität.</span><span class="sxs-lookup"><span data-stu-id="ff8c2-104">The priority for the mail exchange host, lower the value higher the priority.</span></span></param>
        <summary>
            <span data-ttu-id="ff8c2-105">Erstellt und einen MX-Eintrag mit dem bereitgestellten e-Mail-Exchange-Server in dieser Datensatzgruppe Priorität zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="ff8c2-105">Creates and assigns priority to a MX record with the provided mail exchange server in this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="ff8c2-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="ff8c2-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>