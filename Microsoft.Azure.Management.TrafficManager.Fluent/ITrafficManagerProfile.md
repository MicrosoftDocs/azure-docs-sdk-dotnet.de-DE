<Type Name="ITrafficManagerProfile" FullName="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile">
  <TypeSignature Language="C#" Value="public interface ITrafficManagerProfile : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager,Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract ITrafficManagerProfile implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager, class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile" />
  <TypeSignature Language="VB.NET" Value="Public Interface ITrafficManagerProfile&#xA;Implements IGroupableResource(Of ITrafficManager, ProfileInner), IHasInner(Of ProfileInner), IHasManager(Of ITrafficManager), IRefreshable(Of ITrafficManagerProfile), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type ITrafficManagerProfile = interface&#xA;    interface IGroupableResource&lt;ITrafficManager, ProfileInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;ITrafficManager&gt;&#xA;    interface IHasInner&lt;ProfileInner&gt;&#xA;    interface IRefreshable&lt;ITrafficManagerProfile&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager,Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.TrafficManager.Fluent.Models.ProfileInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.TrafficManager.Fluent.TrafficManagerProfile.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung einer Azure Traffic Manager-Profil.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AzureEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint&gt; AzureEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint&gt; AzureEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.AzureEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AzureEndpoints As IReadOnlyDictionary(Of String, ITrafficManagerAzureEndpoint)" />
      <MemberSignature Language="F#" Value="member this.AzureEndpoints : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.AzureEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerAzureEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Azure-Endpunkte in der Traffic Manager-Profil mit dem Namen indiziert ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DnsLabel">
      <MemberSignature Language="C#" Value="public string DnsLabel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DnsLabel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.DnsLabel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DnsLabel As String" />
      <MemberSignature Language="F#" Value="member this.DnsLabel : string" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.DnsLabel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den relativen DNS-Namen des Traffic Manager-Profils.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExternalEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint&gt; ExternalEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint&gt; ExternalEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.ExternalEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExternalEndpoints As IReadOnlyDictionary(Of String, ITrafficManagerExternalEndpoint)" />
      <MemberSignature Language="F#" Value="member this.ExternalEndpoints : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.ExternalEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerExternalEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Externe Endpunkte in der Traffic Manager-Profil mit dem Namen indiziert abgerufen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Fqdn">
      <MemberSignature Language="C#" Value="public string Fqdn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Fqdn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.Fqdn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Fqdn As String" />
      <MemberSignature Language="F#" Value="member this.Fqdn : string" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.Fqdn" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den vollqualifizierten Domänennamen (FQDN) des Traffic Manager-Profils ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsEnabled">
      <MemberSignature Language="C#" Value="public bool IsEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.IsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsEnabled : bool" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.IsEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn das Traffic Manager-Profil wird aktiviert, false, wenn aktiviert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitoringPath">
      <MemberSignature Language="C#" Value="public string MonitoringPath { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MonitoringPath" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitoringPath" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MonitoringPath As String" />
      <MemberSignature Language="F#" Value="member this.MonitoringPath : string" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitoringPath" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Pfad, der überwacht wird, um die Integrität von Traffic Manager-Profil-Endpunkten zu überprüfen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitoringPort">
      <MemberSignature Language="C#" Value="public long MonitoringPort { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MonitoringPort" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitoringPort" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MonitoringPort As Long" />
      <MemberSignature Language="F#" Value="member this.MonitoringPort : int64" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitoringPort" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Port, der überwacht wird, um die Integrität von Traffic Manager-Profil-Endpunkten zu überprüfen.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MonitorStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.ProfileMonitorStatus MonitorStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.ProfileMonitorStatus MonitorStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitorStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MonitorStatus As ProfileMonitorStatus" />
      <MemberSignature Language="F#" Value="member this.MonitorStatus : Microsoft.Azure.Management.TrafficManager.Fluent.ProfileMonitorStatus" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.MonitorStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.ProfileMonitorStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Monitor Profilstatus der Kombination der Endpunkt Monitor Statuswerte für alle Endpunkte im Profil ist und der konfigurierten Profilstatus ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NestedProfileEndpoints">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint&gt; NestedProfileEndpoints { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint&gt; NestedProfileEndpoints" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.NestedProfileEndpoints" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NestedProfileEndpoints As IReadOnlyDictionary(Of String, ITrafficManagerNestedProfileEndpoint)" />
      <MemberSignature Language="F#" Value="member this.NestedProfileEndpoints : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint&gt;" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.NestedProfileEndpoints" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerNestedProfileEndpoint&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft geschachtelte Traffic Manager-Profil Endpunkte in diesem Traffic Manager-Profil mit dem Namen indiziert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TimeToLive">
      <MemberSignature Language="C#" Value="public long TimeToLive { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 TimeToLive" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.TimeToLive" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TimeToLive As Long" />
      <MemberSignature Language="F#" Value="member this.TimeToLive : int64" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.TimeToLive" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den DNS-Gültigkeitsdauer (TTL), in Sekunden an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficRoutingMethod">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod TrafficRoutingMethod { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod TrafficRoutingMethod" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.TrafficRoutingMethod" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficRoutingMethod As TrafficRoutingMethod" />
      <MemberSignature Language="F#" Value="member this.TrafficRoutingMethod : Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod" Usage="Microsoft.Azure.Management.TrafficManager.Fluent.ITrafficManagerProfile.TrafficRoutingMethod" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.TrafficManager.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.TrafficManager.Fluent.TrafficRoutingMethod</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Routingmethode zum Weiterleiten von Datenverkehr zu Traffic Manager-Profil-Endpunkten verwendet.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>