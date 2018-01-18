<Type Name="IDnsZone" FullName="Microsoft.Azure.Management.Dns.Fluent.IDnsZone">
  <TypeSignature Language="C#" Value="public interface IDnsZone : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZoneManager,Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZoneManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IDnsZone implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsZoneManager, class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsZoneManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.IDnsZone" />
  <TypeSignature Language="VB.NET" Value="Public Interface IDnsZone&#xA;Implements IGroupableResource(Of IDnsZoneManager, ZoneInner), IHasInner(Of ZoneInner), IHasManager(Of IDnsZoneManager), IRefreshable(Of IDnsZone), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IDnsZone = interface&#xA;    interface IGroupableResource&lt;IDnsZoneManager, ZoneInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IDnsZoneManager&gt;&#xA;    interface IHasInner&lt;ZoneInner&gt;&#xA;    interface IRefreshable&lt;IDnsZone&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZoneManager,Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Dns.Fluent.Models.ZoneInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZoneManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsZone&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="3309c-101">Eine unveränderliche clientseitige Darstellung einer Azure-DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="3309c-101">An immutable client-side representation of an Azure DNS Zone.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="AaaaRecordSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.IAaaaRecordSets AaaaRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.IAaaaRecordSets AaaaRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.AaaaRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AaaaRecordSets As IAaaaRecordSets" />
      <MemberSignature Language="F#" Value="member this.AaaaRecordSets : Microsoft.Azure.Management.Dns.Fluent.IAaaaRecordSets" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.AaaaRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.IAaaaRecordSets</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-102">Ruft ab Einstiegspunkt zum Verwalten von Datensatzgruppen in dieser Zone, die AAAA (IPv6-Adresse) Datensätze enthält.</span><span class="sxs-lookup"><span data-stu-id="3309c-102">Gets entry point to manage record sets in this zone containing AAAA (IPv6 address) records.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ARecordSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.IARecordSets ARecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.IARecordSets ARecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.ARecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ARecordSets As IARecordSets" />
      <MemberSignature Language="F#" Value="member this.ARecordSets : Microsoft.Azure.Management.Dns.Fluent.IARecordSets" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.ARecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.IARecordSets</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-103">Ruft ab Einstiegspunkt zum Verwalten von Datensatzgruppen in dieser Zone, die eine (IPv4-Adresse) Datensätze enthält.</span><span class="sxs-lookup"><span data-stu-id="3309c-103">Gets entry point to manage record sets in this zone containing A (IPv4 address) records.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CNameRecordSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.ICNameRecordSets CNameRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.ICNameRecordSets CNameRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.CNameRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CNameRecordSets As ICNameRecordSets" />
      <MemberSignature Language="F#" Value="member this.CNameRecordSets : Microsoft.Azure.Management.Dns.Fluent.ICNameRecordSets" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.CNameRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.ICNameRecordSets</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-104">Ruft Einstiegspunkt zum Verwalten von Datensatzgruppen in dieser Zone mit CNAME-Eintrags (kanonischer Name) ab.</span><span class="sxs-lookup"><span data-stu-id="3309c-104">Gets entry point to manage record sets in this zone containing CNAME (canonical name) records.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ETag">
      <MemberSignature Language="C#" Value="public string ETag { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ETag" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.ETag" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ETag As String" />
      <MemberSignature Language="F#" Value="member this.ETag : string" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.ETag" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>To be added.</summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetSoaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.ISoaRecordSet GetSoaRecordSet ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.ISoaRecordSet GetSoaRecordSet() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.GetSoaRecordSet" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSoaRecordSet () As ISoaRecordSet" />
      <MemberSignature Language="F#" Value="abstract member GetSoaRecordSet : unit -&gt; Microsoft.Azure.Management.Dns.Fluent.ISoaRecordSet" Usage="iDnsZone.GetSoaRecordSet " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.ISoaRecordSet</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3309c-105">Die Datensatzgruppe mit SOA (Start of Authority,) Datensatz dieser DNS-Zone zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="3309c-105">The record set containing SOA (start of authority) record associated with this DNS zone.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ListRecordSets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt; ListRecordSets ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt; ListRecordSets() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.ListRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public Function ListRecordSets () As IEnumerable(Of IDnsRecordSet)" />
      <MemberSignature Language="F#" Value="abstract member ListRecordSets : unit -&gt; seq&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;" Usage="iDnsZone.ListRecordSets " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecordSets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt; ListRecordSets (int pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt; ListRecordSets(int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.ListRecordSets(System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListRecordSets (pageSize As Integer) As IEnumerable(Of IDnsRecordSet)" />
      <MemberSignature Language="F#" Value="abstract member ListRecordSets : int -&gt; seq&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;" Usage="iDnsZone.ListRecordSets pageSize" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="pageSize">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecordSets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt; ListRecordSets (string recordSetNameSuffix);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt; ListRecordSets(string recordSetNameSuffix) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.ListRecordSets(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListRecordSets (recordSetNameSuffix As String) As IEnumerable(Of IDnsRecordSet)" />
      <MemberSignature Language="F#" Value="abstract member ListRecordSets : string -&gt; seq&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;" Usage="iDnsZone.ListRecordSets recordSetNameSuffix" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="recordSetNameSuffix" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="recordSetNameSuffix">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListRecordSets">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt; ListRecordSets (string recordSetNameSuffix, int pageSize);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt; ListRecordSets(string recordSetNameSuffix, int32 pageSize) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.ListRecordSets(System.String,System.Int32)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListRecordSets (recordSetNameSuffix As String, pageSize As Integer) As IEnumerable(Of IDnsRecordSet)" />
      <MemberSignature Language="F#" Value="abstract member ListRecordSets : string * int -&gt; seq&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;" Usage="iDnsZone.ListRecordSets (recordSetNameSuffix, pageSize)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Dns.Fluent.IDnsRecordSet&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="recordSetNameSuffix" Type="System.String" />
        <Parameter Name="pageSize" Type="System.Int32" />
      </Parameters>
      <Docs>
        <param name="recordSetNameSuffix">To be added.</param>
        <param name="pageSize">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxNumberOfRecordSets">
      <MemberSignature Language="C#" Value="public long MaxNumberOfRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 MaxNumberOfRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.MaxNumberOfRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxNumberOfRecordSets As Long" />
      <MemberSignature Language="F#" Value="member this.MaxNumberOfRecordSets : int64" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.MaxNumberOfRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-106">Ruft die maximale Anzahl von Datensatzgruppen, die in dieser Zone erstellt werden können.</span><span class="sxs-lookup"><span data-stu-id="3309c-106">Gets the maximum number of record sets that can be created in this zone.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MXRecordSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.IMXRecordSets MXRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.IMXRecordSets MXRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.MXRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MXRecordSets As IMXRecordSets" />
      <MemberSignature Language="F#" Value="member this.MXRecordSets : Microsoft.Azure.Management.Dns.Fluent.IMXRecordSets" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.MXRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.IMXRecordSets</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-107">Ruft ab Einstiegspunkt zum Verwalten von Datensatzgruppen in dieser Zone, die MX (Mail Exchange) Datensätze enthält.</span><span class="sxs-lookup"><span data-stu-id="3309c-107">Gets entry point to manage record sets in this zone containing MX (mail exchange) records.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; NameServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; NameServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.NameServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameServers As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NameServers : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.NameServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-108">Ruft die Namenserver für diese Zone zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="3309c-108">Gets name servers assigned for this zone.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NSRecordSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.INSRecordSets NSRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.INSRecordSets NSRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.NSRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NSRecordSets As INSRecordSets" />
      <MemberSignature Language="F#" Value="member this.NSRecordSets : Microsoft.Azure.Management.Dns.Fluent.INSRecordSets" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.NSRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.INSRecordSets</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-109">Ruft ab Einstiegspunkt für Datensatzgruppen in dieser Zone, enthält die Namenservereinträge für (Namenserver) zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="3309c-109">Gets entry point to manage record sets in this zone containing NS (name server) records.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfRecordSets">
      <MemberSignature Language="C#" Value="public long NumberOfRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int64 NumberOfRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.NumberOfRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfRecordSets As Long" />
      <MemberSignature Language="F#" Value="member this.NumberOfRecordSets : int64" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.NumberOfRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int64</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-110">Ruft die aktuelle Anzahl der Datensätze in dieser Zone an.</span><span class="sxs-lookup"><span data-stu-id="3309c-110">Gets the current number of record sets in this zone.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PtrRecordSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.IPtrRecordSets PtrRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.IPtrRecordSets PtrRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.PtrRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PtrRecordSets As IPtrRecordSets" />
      <MemberSignature Language="F#" Value="member this.PtrRecordSets : Microsoft.Azure.Management.Dns.Fluent.IPtrRecordSets" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.PtrRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.IPtrRecordSets</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-111">Ruft ab Einstiegspunkt zum Verwalten von Datensatzgruppen in dieser Zone, PTR (Zeiger) Datensätze enthält.</span><span class="sxs-lookup"><span data-stu-id="3309c-111">Gets entry point to manage record sets in this zone containing PTR (pointer) records.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SrvRecordSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.ISrvRecordSets SrvRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.ISrvRecordSets SrvRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.SrvRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SrvRecordSets As ISrvRecordSets" />
      <MemberSignature Language="F#" Value="member this.SrvRecordSets : Microsoft.Azure.Management.Dns.Fluent.ISrvRecordSets" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.SrvRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.ISrvRecordSets</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-112">Ruft ab Einstiegspunkt zum Verwalten von Datensatzgruppen in dieser Zone, SRV (Service) Datensätze enthält.</span><span class="sxs-lookup"><span data-stu-id="3309c-112">Gets entry point to manage record sets in this zone containing SRV (service) records.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TxtRecordSets">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.ITxtRecordSets TxtRecordSets { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Dns.Fluent.ITxtRecordSets TxtRecordSets" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Dns.Fluent.IDnsZone.TxtRecordSets" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TxtRecordSets As ITxtRecordSets" />
      <MemberSignature Language="F#" Value="member this.TxtRecordSets : Microsoft.Azure.Management.Dns.Fluent.ITxtRecordSets" Usage="Microsoft.Azure.Management.Dns.Fluent.IDnsZone.TxtRecordSets" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.ITxtRecordSets</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="3309c-113">Ruft ab Einstiegspunkt zum Verwalten von Datensatzgruppen in dieser Zone, TXT (Text) Datensätze enthält.</span><span class="sxs-lookup"><span data-stu-id="3309c-113">Gets entry point to manage record sets in this zone containing TXT (text) records.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>