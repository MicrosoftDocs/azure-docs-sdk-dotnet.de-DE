<Type Name="IWithMXRecordMailExchange" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMXRecordMailExchange">
  <TypeSignature Language="C#" Value="public interface IWithMXRecordMailExchange" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMXRecordMailExchange" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMXRecordMailExchange" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMXRecordMailExchange" />
  <TypeSignature Language="F#" Value="type IWithMXRecordMailExchange = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="c0198-101">Die Phase des MX-Eintrags festgelegt Definition zum Hinzufügen oder Entfernen von MX-Eintrag zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="c0198-101">The stage of the MX record set definition allowing to add or remove MX record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMailExchange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet WithMailExchange (string mailExchangeHostName, int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet WithMailExchange(string mailExchangeHostName, int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMXRecordMailExchange.WithMailExchange(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMailExchange (mailExchangeHostName As String, priority As Integer) As IUpdateMXRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithMailExchange : string * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet" Usage="iWithMXRecordMailExchange.WithMailExchange (mailExchangeHostName, priority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mailExchangeHostName" Type="System.String" />
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="mailExchangeHostName"><span data-ttu-id="c0198-102">Der Hostname des Exchange-Mailservers.</span><span class="sxs-lookup"><span data-stu-id="c0198-102">The host name of the mail exchange server.</span></span></param>
        <param name="priority"><span data-ttu-id="c0198-103">Die Priorität für die Exchange-Mailhost senken dem Wert höher die Priorität.</span><span class="sxs-lookup"><span data-stu-id="c0198-103">The priority for the mail exchange host, lower the value higher the priority.</span></span></param>
        <summary>
            <span data-ttu-id="c0198-104">Erstellt und einen MX-Eintrag mit dem bereitgestellten e-Mail-Exchange-Server in dieser Datensatzgruppe Priorität zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="c0198-104">Creates and assigns priority to a MX record with the provided mail exchange server in this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0198-105">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="c0198-105">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMailExchange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet WithoutMailExchange (string mailExchangeHostName, int priority);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet WithoutMailExchange(string mailExchangeHostName, int32 priority) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMXRecordMailExchange.WithoutMailExchange(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMailExchange (mailExchangeHostName As String, priority As Integer) As IUpdateMXRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithoutMailExchange : string * int -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet" Usage="iWithMXRecordMailExchange.WithoutMailExchange (mailExchangeHostName, priority)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="mailExchangeHostName" Type="System.String" />
        <Parameter Name="priority" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="mailExchangeHostName"><span data-ttu-id="c0198-106">Der Hostname des Exchange-Mailservers.</span><span class="sxs-lookup"><span data-stu-id="c0198-106">The host name of the mail exchange server.</span></span></param>
        <param name="priority"><span data-ttu-id="c0198-107">Die Priorität für die Exchange-Mailhost senken dem Wert höher die Priorität.</span><span class="sxs-lookup"><span data-stu-id="c0198-107">The priority for the mail exchange host, lower the value higher the priority.</span></span></param>
        <summary>
            <span data-ttu-id="c0198-108">Entfernt MX-Eintrag mit den bereitgestellten e-Mail-Server und die Priorität von diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="c0198-108">Removes MX record with the provided mail exchange server and priority from this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c0198-109">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="c0198-109">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>