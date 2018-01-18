<Type Name="IWithPtrRecordTargetDomainName" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithPtrRecordTargetDomainName">
  <TypeSignature Language="C#" Value="public interface IWithPtrRecordTargetDomainName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPtrRecordTargetDomainName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithPtrRecordTargetDomainName" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPtrRecordTargetDomainName" />
  <TypeSignature Language="F#" Value="type IWithPtrRecordTargetDomainName = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="e6af5-101">Die Phase des CName-Eintrags festgelegt Definition zum Hinzufügen oder Entfernen von CName-Eintrag zu ermöglichen.</span><span class="sxs-lookup"><span data-stu-id="e6af5-101">The stage of the CName record set definition allowing to add or remove CName record.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithoutTargetDomainName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet WithoutTargetDomainName (string targetDomainName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet WithoutTargetDomainName(string targetDomainName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithPtrRecordTargetDomainName.WithoutTargetDomainName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTargetDomainName (targetDomainName As String) As IUpdatePtrRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithoutTargetDomainName : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet" Usage="iWithPtrRecordTargetDomainName.WithoutTargetDomainName targetDomainName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetDomainName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetDomainName"><span data-ttu-id="e6af5-102">Der Ziel-Domänenname.</span><span class="sxs-lookup"><span data-stu-id="e6af5-102">The target domain name.</span></span></param>
        <summary>
            <span data-ttu-id="e6af5-103">Entfernt den CName-Eintrag mit dem angegebenen kanonischen Namen von diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="e6af5-103">Removes the CName record with the provided canonical name from this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e6af5-104">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="e6af5-104">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithTargetDomainName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet WithTargetDomainName (string targetDomainName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet WithTargetDomainName(string targetDomainName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithPtrRecordTargetDomainName.WithTargetDomainName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithTargetDomainName (targetDomainName As String) As IUpdatePtrRecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithTargetDomainName : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet" Usage="iWithPtrRecordTargetDomainName.WithTargetDomainName targetDomainName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="targetDomainName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="targetDomainName"><span data-ttu-id="e6af5-105">Der Ziel-Domänenname.</span><span class="sxs-lookup"><span data-stu-id="e6af5-105">The target domain name.</span></span></param>
        <summary>
            <span data-ttu-id="e6af5-106">Erstellt einen CName-Eintrag mit dem angegebenen kanonischen Namen in diesen Datensatz.</span><span class="sxs-lookup"><span data-stu-id="e6af5-106">Creates a CName record with the provided canonical name in this record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="e6af5-107">Die nächste Phase des Recordset-Updates.</span><span class="sxs-lookup"><span data-stu-id="e6af5-107">The next stage of the record set update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>