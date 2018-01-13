<Type Name="IWithNSRecordNameServer" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithNSRecordNameServer">
  <TypeSignature Language="C#" Value="public interface IWithNSRecordNameServer" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNSRecordNameServer" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithNSRecordNameServer" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNSRecordNameServer" />
  <TypeSignature Language="F#" Value="type IWithNSRecordNameServer = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="6d850-101">Die Phase der NS Ressourceneintragssatz Definition Möglichkeit zum Hinzufügen oder Entfernen einer Namenservereintrag.</span><span class="sxs-lookup"><span data-stu-id="6d850-101">The stage of the NS record set definition allowing to add or remove a NS record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNameServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet WithNameServer (string nameServerHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet WithNameServer(string nameServerHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithNSRecordNameServer.WithNameServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNameServer (nameServerHostName As String) As IUpdateNSRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithNameServer : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet" Usage="iWithNSRecordNameServer.WithNameServer nameServerHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameServerHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameServerHostName"><span data-ttu-id="6d850-102">Der Server den Hostnamen.</span><span class="sxs-lookup"><span data-stu-id="6d850-102">The name server host name.</span></span></param>
        <summary>
            <span data-ttu-id="6d850-103">Erstellt einen Namenservereintrag mit dem Namenserver bereitgestellten in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="6d850-103">Creates a NS record with the provided name server in this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6d850-104">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="6d850-104">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutNameServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet WithoutNameServer (string nameServerHostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet WithoutNameServer(string nameServerHostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithNSRecordNameServer.WithoutNameServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutNameServer (nameServerHostName As String) As IUpdateNSRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithoutNameServer : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet" Usage="iWithNSRecordNameServer.WithoutNameServer nameServerHostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="nameServerHostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="nameServerHostName"><span data-ttu-id="6d850-105">Der Server den Hostnamen.</span><span class="sxs-lookup"><span data-stu-id="6d850-105">The name server host name.</span></span></param>
        <summary>
            <span data-ttu-id="6d850-106">Rmoves NS-Datensatz mit dem angegebenen Namenserver aus dieser Datensatz festgelegt.</span><span class="sxs-lookup"><span data-stu-id="6d850-106">Rmoves a NS record with the provided name server from this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="6d850-107">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="6d850-107">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>