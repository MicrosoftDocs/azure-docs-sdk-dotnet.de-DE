<Type Name="IWithARecordIPv4Address" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithARecordIPv4Address">
  <TypeSignature Language="C#" Value="public interface IWithARecordIPv4Address" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithARecordIPv4Address" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithARecordIPv4Address" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithARecordIPv4Address" />
  <TypeSignature Language="F#" Value="type IWithARecordIPv4Address = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der A-Eintrag festgelegt Update hinzufügen oder Entfernen eines Datensatzes zu ermöglichen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIPv4Address">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet WithIPv4Address (string ipv4Address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet WithIPv4Address(string ipv4Address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithARecordIPv4Address.WithIPv4Address(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPv4Address (ipv4Address As String) As IUpdateARecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithIPv4Address : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet" Usage="iWithARecordIPv4Address.WithIPv4Address ipv4Address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipv4Address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipv4Address">Eine IPv4-Adresse.</param>
        <summary>
            Erstellt einen A-Eintrag mit die angegebene IPv4-Adresse im Ressourceneintragssatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutIPv4Address">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet WithoutIPv4Address (string ipv4Address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet WithoutIPv4Address(string ipv4Address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithARecordIPv4Address.WithoutIPv4Address(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutIPv4Address (ipv4Address As String) As IUpdateARecordSet" />
      <MemberSignature Language="F#" Value="abstract member WithoutIPv4Address : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet" Usage="iWithARecordIPv4Address.WithoutIPv4Address ipv4Address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipv4Address" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipv4Address">Eine IPv4-Adresse.</param>
        <summary>
            Entfernt den A-Eintrag mit die angegebene IPv4-Adresse aus dem Datensatz Satz an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>