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
            Die Phase des CName-Eintrags festgelegt Definition zum Hinzufügen oder Entfernen von CName-Eintrag zu ermöglichen.
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
        <param name="targetDomainName">Der Ziel-Domänenname.</param>
        <summary>
            Entfernt den CName-Eintrag mit dem angegebenen kanonischen Namen von diesen Datensatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
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
        <param name="targetDomainName">Der Ziel-Domänenname.</param>
        <summary>
            Erstellt einen CName-Eintrag mit dem angegebenen kanonischen Namen in diesen Datensatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>