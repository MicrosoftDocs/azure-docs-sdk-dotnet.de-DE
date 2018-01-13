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
            <span data-ttu-id="dcc72-101">Die Firewallregel für SQL-Definition für den Server die IP-Startadresse fest.</span><span class="sxs-lookup"><span data-stu-id="dcc72-101">The SQL Firewall Rule definition to set the starting IP Address for the server.</span></span>
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
        <param name="startIPAddress"><span data-ttu-id="dcc72-102">Starten Sie IP-Adresse in IPv4-Format.</span><span class="sxs-lookup"><span data-stu-id="dcc72-102">Starting IP address in IPv4 format.</span></span></param>
        <param name="endIPAddress"><span data-ttu-id="dcc72-103">Starten Sie IP-Adresse in IPv4-Format.</span><span class="sxs-lookup"><span data-stu-id="dcc72-103">Starting IP address in IPv4 format.</span></span></param>
        <summary>
            <span data-ttu-id="dcc72-104">Legt die IP-Startadresse des SQLServer Firewallregel.</span><span class="sxs-lookup"><span data-stu-id="dcc72-104">Sets the starting IP address of SQL server's firewall rule.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="dcc72-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="dcc72-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>