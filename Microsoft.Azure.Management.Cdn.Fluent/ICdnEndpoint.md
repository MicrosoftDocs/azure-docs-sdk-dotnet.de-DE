<Type Name="ICdnEndpoint" FullName="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint">
  <TypeSignature Language="C#" Value="public interface ICdnEndpoint : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint,Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ICdnEndpoint implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource`2&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint, class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint" />
  <TypeSignature Language="VB.NET" Value="Public Interface ICdnEndpoint&#xA;Implements IChildResource(Of ICdnProfile), IExternalChildResource(Of ICdnEndpoint, ICdnProfile), IHasInner(Of EndpointInner), IHasParent(Of ICdnProfile), IRefreshable(Of ICdnEndpoint)" />
  <TypeSignature Language="F#" Value="type ICdnEndpoint = interface&#xA;    interface IExternalChildResource&lt;ICdnEndpoint, ICdnProfile&gt;&#xA;    interface IChildResource&lt;ICdnProfile&gt;&#xA;    interface IHasName&#xA;    interface IIndexable&#xA;    interface IHasParent&lt;ICdnProfile&gt;&#xA;    interface IRefreshable&lt;ICdnEndpoint&gt;&#xA;    interface IHasInner&lt;EndpointInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IChildResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IExternalChildResource&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint,Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.EndpointInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasParent&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung eines Azure-CDN-Endpunkts.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="ContentTypesToCompress">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; ContentTypesToCompress { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; ContentTypesToCompress" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ContentTypesToCompress" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContentTypesToCompress As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.ContentTypesToCompress : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ContentTypesToCompress" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der Inhaltstypen komprimiert werden soll.
            </summary>
        <value>To be added.</value>
        <remarks>
            Ruft ab (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="CustomDomains">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; CustomDomains { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; CustomDomains" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.CustomDomains" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CustomDomains As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.CustomDomains : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.CustomDomains" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der benutzerdefinierten Domänen, die diesem Endpunkt zugeordneten ab.
            </summary>
        <value>To be added.</value>
        <remarks>
            Ruft ab (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
      </Docs>
    </Member>
    <Member MemberName="GeoFilters">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; GeoFilters { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt; GeoFilters" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.GeoFilters" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GeoFilters As IReadOnlyList(Of GeoFilter)" />
      <MemberSignature Language="F#" Value="member this.GeoFilters : System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.GeoFilters" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.GeoFilter&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Liste der geografischen Filter ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostName">
      <MemberSignature Language="C#" Value="public string HostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string HostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostName As String" />
      <MemberSignature Language="F#" Value="member this.HostName : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Endpunkt-Hostnamen ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpPort">
      <MemberSignature Language="C#" Value="public int HttpPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HttpPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpPort As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpPort : int" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HttpPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die HTTP-Port-Wert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HttpsPort">
      <MemberSignature Language="C#" Value="public int HttpsPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 HttpsPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HttpsPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HttpsPort As Integer" />
      <MemberSignature Language="F#" Value="member this.HttpsPort : int" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.HttpsPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die HTTPS-Port-Wert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsCompressionEnabled">
      <MemberSignature Language="C#" Value="public bool IsCompressionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsCompressionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsCompressionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsCompressionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsCompressionEnabled : bool" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsCompressionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn inhaltskomprimierung aktiviert, andernfalls "false ist".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHttpAllowed">
      <MemberSignature Language="C#" Value="public bool IsHttpAllowed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsHttpAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsHttpAllowed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsHttpAllowed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsHttpAllowed : bool" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsHttpAllowed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn HTTP-Datenverkehr zulässig ist, andernfalls "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsHttpsAllowed">
      <MemberSignature Language="C#" Value="public bool IsHttpsAllowed { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsHttpsAllowed" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsHttpsAllowed" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsHttpsAllowed As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsHttpsAllowed : bool" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.IsHttpsAllowed" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn die HTTPS-Datenverkehr zugelassen wird, andernfalls "false".
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListResourceUsage">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt; ListResourceUsage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt; ListResourceUsage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ListResourceUsage" />
      <MemberSignature Language="VB.NET" Value="Public Function ListResourceUsage () As IEnumerable(Of ResourceUsage)" />
      <MemberSignature Language="F#" Value="abstract member ListResourceUsage : unit -&gt; seq&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt;" Usage="iCdnEndpoint.ListResourceUsage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Cdn.Fluent.Models.ResourceUsage&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Hier wird überprüft, ob das Kontingent und die Nutzung von geografische filtern und benutzerdefinierte Domänen unter den aktuellen Endpunkt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Liste der Kontingente und Ihre Verwendungen von geografische filtern und benutzerdefinierte Domänen unter den aktuellen Endpunkt.</return>
      </Docs>
    </Member>
    <Member MemberName="LoadContent">
      <MemberSignature Language="C#" Value="public void LoadContent (System.Collections.Generic.ISet&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void LoadContent(class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.LoadContent(System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub LoadContent (contentPaths As ISet(Of String))" />
      <MemberSignature Language="F#" Value="abstract member LoadContent : System.Collections.Generic.ISet&lt;string&gt; -&gt; unit" Usage="iCdnEndpoint.LoadContent contentPaths" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LoadContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task LoadContentAsync (System.Collections.Generic.ISet&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task LoadContentAsync(class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.LoadContentAsync(System.Collections.Generic.ISet{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member LoadContentAsync : System.Collections.Generic.ISet&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnEndpoint.LoadContentAsync (contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OptimizationType">
      <MemberSignature Language="C#" Value="public string OptimizationType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OptimizationType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OptimizationType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OptimizationType As String" />
      <MemberSignature Language="F#" Value="member this.OptimizationType : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OptimizationType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die optimierungstyp ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginHostHeader">
      <MemberSignature Language="C#" Value="public string OriginHostHeader { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginHostHeader" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginHostHeader" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OriginHostHeader As String" />
      <MemberSignature Language="F#" Value="member this.OriginHostHeader : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginHostHeader" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die ursprungshostheader ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginHostName">
      <MemberSignature Language="C#" Value="public string OriginHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OriginHostName As String" />
      <MemberSignature Language="F#" Value="member this.OriginHostName : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Hostname des Ursprungs ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OriginPath">
      <MemberSignature Language="C#" Value="public string OriginPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OriginPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OriginPath As String" />
      <MemberSignature Language="F#" Value="member this.OriginPath : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.OriginPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Ursprungspfad ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ProvisioningState">
      <MemberSignature Language="C#" Value="public string ProvisioningState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ProvisioningState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ProvisioningState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ProvisioningState As String" />
      <MemberSignature Language="F#" Value="member this.ProvisioningState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ProvisioningState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft der Bereitstellungsstatus Endpunkt ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeContent">
      <MemberSignature Language="C#" Value="public void PurgeContent (System.Collections.Generic.ISet&lt;string&gt; contentPaths);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PurgeContent(class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.PurgeContent(System.Collections.Generic.ISet{System.String})" />
      <MemberSignature Language="VB.NET" Value="Public Sub PurgeContent (contentPaths As ISet(Of String))" />
      <MemberSignature Language="F#" Value="abstract member PurgeContent : System.Collections.Generic.ISet&lt;string&gt; -&gt; unit" Usage="iCdnEndpoint.PurgeContent contentPaths" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
      </Parameters>
      <Docs>
        <param name="contentPaths">To be added.</param>
        <summary>To be added.</summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PurgeContentAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PurgeContentAsync (System.Collections.Generic.ISet&lt;string&gt; contentPaths, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PurgeContentAsync(class System.Collections.Generic.ISet`1&lt;string&gt; contentPaths, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.PurgeContentAsync(System.Collections.Generic.ISet{System.String},System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PurgeContentAsync : System.Collections.Generic.ISet&lt;string&gt; * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnEndpoint.PurgeContentAsync (contentPaths, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="contentPaths" Type="System.Collections.Generic.ISet&lt;System.String&gt;" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="contentPaths">To be added.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="QueryStringCachingBehavior">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior QueryStringCachingBehavior { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior QueryStringCachingBehavior" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.QueryStringCachingBehavior" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property QueryStringCachingBehavior As QueryStringCachingBehavior" />
      <MemberSignature Language="F#" Value="member this.QueryStringCachingBehavior : Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.QueryStringCachingBehavior" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.Models.QueryStringCachingBehavior</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft einer Abfragezeichenfolge, die Verhalten beim Zwischenspeichern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResourceState">
      <MemberSignature Language="C#" Value="public string ResourceState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ResourceState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ResourceState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ResourceState As String" />
      <MemberSignature Language="F#" Value="member this.ResourceState : string" Usage="Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ResourceState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Endpunktstatus ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Start() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.Start" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start ()" />
      <MemberSignature Language="F#" Value="abstract member Start : unit -&gt; unit" Usage="iCdnEndpoint.Start " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Wird den CDN-Endpunkt gestartet, wenn er beendet wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.StartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnEndpoint.StartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Startet den CDN-Endpunkt asynchron ausgeführt wird, wenn er beendet wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public void Stop ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Stop() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.Stop" />
      <MemberSignature Language="VB.NET" Value="Public Sub Stop ()" />
      <MemberSignature Language="F#" Value="abstract member Stop : unit -&gt; unit" Usage="iCdnEndpoint.Stop " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Beendet den CDN-Endpunkt an, wenn er ausgeführt wird.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StopAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.StopAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iCdnEndpoint.StopAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Den CDN-Endpunkt beendet asynchron ausgeführt wird, wenn er ausgeführt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
    <Member MemberName="ValidateCustomDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult ValidateCustomDomain (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult ValidateCustomDomain(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ValidateCustomDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ValidateCustomDomain (hostName As String) As CustomDomainValidationResult" />
      <MemberSignature Language="F#" Value="abstract member ValidateCustomDomain : string -&gt; Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult" Usage="iCdnEndpoint.ValidateCustomDomain hostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">Der Hostname, der einen Domänennamen, der die benutzerdefinierte Domäne sein muss.</param>
        <summary>
            Überprüft eine benutzerdefinierte Domäne-Zuordnung, um sicherzustellen, dass es die richtige CNAME im DNS für den aktuellen Endpunkt zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Das Ergebnis der Aktion bei Erfolg.</return>
      </Docs>
    </Member>
    <Member MemberName="ValidateCustomDomainAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt; ValidateCustomDomainAsync (string hostName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt; ValidateCustomDomainAsync(string hostName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Cdn.Fluent.ICdnEndpoint.ValidateCustomDomainAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ValidateCustomDomainAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt;" Usage="iCdnEndpoint.ValidateCustomDomainAsync (hostName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Cdn.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.Cdn.Fluent.CustomDomainValidationResult&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="hostName">Der Hostname, der einen Domänennamen, der die benutzerdefinierte Domäne sein muss.</param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Überprüft eine benutzerdefinierte Domäne-Zuordnung, um sicherzustellen, dass es die richtige CNAME im DNS für den aktuellen Endpunkt asynchron zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Observable-Objekt des Ergebnisses.</return>
      </Docs>
    </Member>
  </Members>
</Type>