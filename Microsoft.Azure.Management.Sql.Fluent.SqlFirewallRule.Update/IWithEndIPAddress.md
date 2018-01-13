<Type Name="IWithEndIPAddress" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Update.IWithEndIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithEndIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithEndIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Update.IWithEndIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithEndIPAddress" />
  <TypeSignature Language="F#" Value="type IWithEndIPAddress = interface" />
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
    <Member MemberName="WithEndIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Update.IUpdate WithEndIPAddress (string endIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Update.IUpdate WithEndIPAddress(string endIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Update.IWithEndIPAddress.WithEndIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithEndIPAddress (endIPAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithEndIPAddress : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Update.IUpdate" Usage="iWithEndIPAddress.WithEndIPAddress endIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="endIPAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="endIPAddress">End-IP-Adresse in IPv4-Format.</param>
        <summary>
            Legt die IP-Endadresse der Firewallregel für SQL-Server an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>