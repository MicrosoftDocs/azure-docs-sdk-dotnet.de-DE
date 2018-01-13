<Type Name="INetworkSecurityRule" FullName="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule">
  <TypeSignature Language="C#" Value="public interface INetworkSecurityRule : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract INetworkSecurityRule implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule" />
  <TypeSignature Language="VB.NET" Value="Public Interface INetworkSecurityRule&#xA;Implements IChildResource(Of INetworkSecurityGroup), IHasInner(Of SecurityRuleInner), IHasParent(Of INetworkSecurityGroup)" />
  <TypeSignature Language="F#" Value="type INetworkSecurityRule = interface&#xA;    interface IHasInner&lt;SecurityRuleInner&gt;&#xA;    interface IChildResource&lt;INetworkSecurityGroup&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;INetworkSecurityGroup&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.Models.SecurityRuleInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine netzwerksicherheitsregel in einer Netzwerksicherheitsgruppe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Access">
      <MemberSignature Language="C#" Value="public string Access { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Access" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.Access" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Access As String" />
      <MemberSignature Language="F#" Value="member this.Access : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.Access" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Typ des Zugriffs, der die Regel erzwingt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Description">
      <MemberSignature Language="C#" Value="public string Description { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Description" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.Description" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Description As String" />
      <MemberSignature Language="F#" Value="member this.Description : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.Description" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die benutzerdefinierte Beschreibung der Sicherheitsregel.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationAddressPrefix">
      <MemberSignature Language="C#" Value="public string DestinationAddressPrefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.DestinationAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DestinationAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.DestinationAddressPrefix : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.DestinationAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Ziel-Adresspräfix, die die Regel gilt, ausgedrückt mithilfe der CIDR-Notation im Format: "###. ###. ###. ### / ##", und "" bedeutet "alle".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DestinationPortRange">
      <MemberSignature Language="C#" Value="public string DestinationPortRange { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DestinationPortRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.DestinationPortRange" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DestinationPortRange As String" />
      <MemberSignature Language="F#" Value="member this.DestinationPortRange : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.DestinationPortRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ziel-Portbereich, der die Regel gilt, im Format "## ##", wobei "" bedeutet, dass alle.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Direction">
      <MemberSignature Language="C#" Value="public string Direction { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Direction" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.Direction" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Direction As String" />
      <MemberSignature Language="F#" Value="member this.Direction : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.Direction" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Richtung des Netzwerkdatenverkehrs, für die netzwerksicherheitsregel gilt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Priority">
      <MemberSignature Language="C#" Value="public int Priority { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Priority" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.Priority" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Priority As Integer" />
      <MemberSignature Language="F#" Value="member this.Priority : int" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.Priority" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Prioritätsnummer gegen diese Regel basierend auf den diese Regel angewendet wird relativ zum die Prioritätsnummer von anderen Regeln, die für diese Netzwerksicherheitsgruppe angegeben.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Protocol">
      <MemberSignature Language="C#" Value="public string Protocol { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Protocol" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.Protocol" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Protocol As String" />
      <MemberSignature Language="F#" Value="member this.Protocol : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.Protocol" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Netzwerkprotokoll, dem die Regel gilt.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourceAddressPrefix">
      <MemberSignature Language="C#" Value="public string SourceAddressPrefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourceAddressPrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.SourceAddressPrefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourceAddressPrefix As String" />
      <MemberSignature Language="F#" Value="member this.SourceAddressPrefix : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.SourceAddressPrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Quelle Adresspräfix, die die Regel gilt, ausgedrückt mithilfe der CIDR-Notation im Format: "###. ###. ###. ### / ##", und "" bedeutet "alle".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SourcePortRange">
      <MemberSignature Language="C#" Value="public string SourcePortRange { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SourcePortRange" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.SourcePortRange" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SourcePortRange As String" />
      <MemberSignature Language="F#" Value="member this.SourcePortRange : string" Usage="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityRule.SourcePortRange" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Quellportbereich, die die Regel gilt, im Format "## ##", wobei "" bedeutet "alle".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>