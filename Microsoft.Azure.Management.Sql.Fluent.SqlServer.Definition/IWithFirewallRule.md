<Type Name="IWithFirewallRule" FullName="Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithFirewallRule">
  <TypeSignature Language="C#" Value="public interface IWithFirewallRule" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithFirewallRule" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithFirewallRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithFirewallRule" />
  <TypeSignature Language="F#" Value="type IWithFirewallRule = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine SQL Server-Definition für die Firewall-Regel angeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewFirewallRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewFirewallRule (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewFirewallRule(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithFirewallRule.WithNewFirewallRule(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewFirewallRule (ipAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewFirewallRule : string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate" Usage="iWithFirewallRule.WithNewFirewallRule ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">IP-Adresse der Firewallregel.</param>
        <summary>
            Erstellt neue Firewallregel auf dem SQL Server.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Nächste Phase der SQL Server-Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewFirewallRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewFirewallRule (string startIPAddress, string endIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewFirewallRule(string startIPAddress, string endIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithFirewallRule.WithNewFirewallRule(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewFirewallRule (startIPAddress As String, endIPAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewFirewallRule : string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate" Usage="iWithFirewallRule.WithNewFirewallRule (startIPAddress, endIPAddress)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startIPAddress" Type="System.String" />
        <Parameter Name="endIPAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIPAddress">Starten Sie die IP-Adresse der Firewallregel.</param>
        <param name="endIPAddress">IP-Endadresse der Firewallregel.</param>
        <summary>
            Erstellt neue Firewallregel auf dem SQL Server.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Nächste Phase der SQL Server-Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewFirewallRule">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewFirewallRule (string startIPAddress, string endIPAddress, string firewallRuleName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate WithNewFirewallRule(string startIPAddress, string endIPAddress, string firewallRuleName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithFirewallRule.WithNewFirewallRule(System.String,System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewFirewallRule (startIPAddress As String, endIPAddress As String, firewallRuleName As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewFirewallRule : string * string * string -&gt; Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate" Usage="iWithFirewallRule.WithNewFirewallRule (startIPAddress, endIPAddress, firewallRuleName)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Sql.Fluent.SqlServer.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="startIPAddress" Type="System.String" />
        <Parameter Name="endIPAddress" Type="System.String" />
        <Parameter Name="firewallRuleName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="startIPAddress">Starten Sie die IP-Adresse der Firewallregel.</param>
        <param name="endIPAddress">IP-Endadresse der Firewallregel.</param>
        <param name="firewallRuleName">Der Name der Firewallregel.</param>
        <summary>
            Erstellt neue Firewallregel auf dem SQL Server.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Nächste Phase der SQL Server-Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>