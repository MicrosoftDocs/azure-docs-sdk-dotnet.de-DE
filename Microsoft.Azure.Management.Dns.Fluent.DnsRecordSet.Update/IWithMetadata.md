<Type Name="IWithMetadata" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMetadata">
  <TypeSignature Language="C#" Value="public interface IWithMetadata" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithMetadata" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMetadata" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithMetadata" />
  <TypeSignature Language="F#" Value="type IWithMetadata = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Ein Update, sodass Metadaten, die für die Ressource nicht geändert werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithMetadata">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate WithMetadata (string key, string value);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate WithMetadata(string key, string value) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMetadata.WithMetadata(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithMetadata (key As String, value As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithMetadata : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate" Usage="iWithMetadata.WithMetadata (key, value)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
        <Parameter Name="value" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Der Schlüssel für die Metadaten.</param>
        <param name="value">Der Wert für die Metadaten.</param>
        <summary>
            Ressourceneintragssatz hinzugefügt Metadaten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMetadata">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate WithoutMetadata (string key);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate WithoutMetadata(string key) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IWithMetadata.WithoutMetadata(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMetadata (key As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMetadata : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate" Usage="iWithMetadata.WithoutMetadata key" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="key" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="key">Der Schlüssel des zu entfernenden Metadaten.</param>
        <summary>
            Entfernt eine Metadaten aus der Ressourceneintragssatz.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Recordset-Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>