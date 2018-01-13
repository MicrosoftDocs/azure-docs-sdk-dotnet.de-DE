<Type Name="IWithIPAddressRange" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithIPAddressRange">
  <TypeSignature Language="C#" Value="public interface IWithIPAddressRange" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIPAddressRange" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithIPAddressRange" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIPAddressRange" />
  <TypeSignature Language="F#" Value="type IWithIPAddressRange = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Firewallregel für SQL-Definition für den Server die IP-Startadresse fest.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithIPAddressRange">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithCreate WithIPAddressRange (string startIPAddress, string endIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithCreate WithIPAddressRange(string startIPAddress, string endIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithIPAddressRange.WithIPAddressRange(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPAddressRange (startIPAddress As String, endIPAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithIPAddressRange : string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithCreate" Usage="iWithIPAddressRange.WithIPAddressRange (startIPAddress, endIPAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startIPAddress" Type="System.String" />
        <Parameter Name="endIPAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIPAddress">Starten Sie IP-Adresse in IPv4-Format.</param>
        <param name="endIPAddress">Starten Sie IP-Adresse in IPv4-Format.</param>
        <summary>
            Legt die IP-Startadresse des SQLServer Firewallregel.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>