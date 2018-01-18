<Type Name="ISqlFirewallRule" FullName="Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule">
  <TypeSignature Language="C#" Value="public interface ISqlFirewallRule : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ISqlFirewallRule implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface ISqlFirewallRule&#xA;Implements IHasInner(Of ServerFirewallRuleInner), IHasManager(Of ISqlManager), IIndependentChild(Of ISqlManager), IRefreshable(Of ISqlFirewallRule), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ISqlFirewallRule = interface&#xA;    interface IIndependentChild&lt;ISqlManager&gt;&#xA;    interface IHasName&#xA;    interface IHasId&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;ISqlManager&gt;&#xA;    interface IRefreshable&lt;ISqlFirewallRule&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;&#xA;    interface IHasInner&lt;ServerFirewallRuleInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Sql.Fluent.Models.ServerFirewallRuleInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IIndependentChild&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Sql.Fluent.SqlFirewallRule.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="2407e-101">Eine unveränderliche clientseitige Darstellung einer Azure SQL Server-FirewallRule.</span><span class="sxs-lookup"><span data-stu-id="2407e-101">An immutable client-side representation of an Azure SQL Server FirewallRule.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Delete">
      <MemberSignature Language="C#" Value="public void Delete ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Delete() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.Delete" />
      <MemberSignature Language="VB.NET" Value="Public Sub Delete ()" />
      <MemberSignature Language="F#" Value="abstract member Delete : unit -&gt; unit" Usage="iSqlFirewallRule.Delete " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="2407e-102">Löscht die Firewall-Regel an.</span><span class="sxs-lookup"><span data-stu-id="2407e-102">Deletes the firewall rule.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EndIPAddress">
      <MemberSignature Language="C#" Value="public string EndIPAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string EndIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.EndIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EndIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.EndIPAddress : string" Usage="Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.EndIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2407e-103">Ruft die End-IP-Adresse (IPv4-Format) der Azure SQL Server-Firewallregel ab.</span><span class="sxs-lookup"><span data-stu-id="2407e-103">Gets the end IP address (in IPv4 format) of the Azure SQL Server Firewall Rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Kind">
      <MemberSignature Language="C#" Value="public string Kind { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Kind" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.Kind" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Kind As String" />
      <MemberSignature Language="F#" Value="member this.Kind : string" Usage="Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.Kind" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2407e-104">Ruft die Art von SQL Server, die diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="2407e-104">Gets kind of SQL Server that contains this firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Region">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region Region { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region Region" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.Region" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Region As Region" />
      <MemberSignature Language="F#" Value="member this.Region : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region" Usage="Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.Region" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Region</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2407e-105">Ruft die Region des SQL Server, die diese Firewallregel enthält.</span><span class="sxs-lookup"><span data-stu-id="2407e-105">Gets region of SQL Server that contains this firewall rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SqlServerName">
      <MemberSignature Language="C#" Value="public string SqlServerName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SqlServerName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.SqlServerName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SqlServerName As String" />
      <MemberSignature Language="F#" Value="member this.SqlServerName : string" Usage="Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.SqlServerName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2407e-106">Ruft den Namen des SQL-Servers, zu dem diese Firewallregel gehört.</span><span class="sxs-lookup"><span data-stu-id="2407e-106">Gets name of the SQL Server to which this firewall rule belongs.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartIPAddress">
      <MemberSignature Language="C#" Value="public string StartIPAddress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string StartIPAddress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.StartIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StartIPAddress As String" />
      <MemberSignature Language="F#" Value="member this.StartIPAddress : string" Usage="Microsoft.Azure.Management.Sql.Fluent.ISqlFirewallRule.StartIPAddress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Sql.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="2407e-107">Ruft die erste IP-Adresse (im IPv4-Format) der Azure SQL Server-Firewallregel ab.</span><span class="sxs-lookup"><span data-stu-id="2407e-107">Gets the start IP address (in IPv4 format) of the Azure SQL Server Firewall Rule.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>