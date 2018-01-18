<Type Name="IWithRecordSet" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet">
  <TypeSignature Language="C#" Value="public interface IWithRecordSet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRecordSet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRecordSet" />
  <TypeSignature Language="F#" Value="type IWithRecordSet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="d7351-101">Die Phase der DNS-Zone Update ermöglichen Ressourceneintragssatz angeben.</span><span class="sxs-lookup"><span data-stu-id="d7351-101">The stage of the DNS zone update allowing to specify record set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAaaaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineAaaaRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IAaaaRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineAaaaRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineAaaaRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAaaaRecordSet (name As String) As IAaaaRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineAaaaRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineAaaaRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-102">Name der AAAA-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-102">Name of the AAAA record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-103">Gibt die Definition eines AAAA legen Sie die DNS-Zone zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d7351-103">Specifies definition of an AAAA record set to be attached to the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-104">Die Phase, die Konfiguration für den AAAA-Ressourceneintragssatz darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-104">The stage representing configuration for the AAAA record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineARecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineARecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IARecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineARecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineARecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineARecordSet (name As String) As IARecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineARecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineARecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-105">Name der A-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-105">Name of the A record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-106">Gibt die Definition eines A-Eintrags, legen Sie die DNS-Zone zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d7351-106">Specifies definition of an A record set to be attached to the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-107">Legen Sie die Phase, die Konfiguration für den A-Eintrag darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-107">The stage representing configuration for the A record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineCNameRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ICNameRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineCNameRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineCNameRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineCNameRecordSet (name As String) As ICNameRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineCNameRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineCNameRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefineMXRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineMXRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IMXRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineMXRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineMXRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineMXRecordSet (name As String) As IMXRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineMXRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineMXRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-108">Der Name des MX-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-108">Name of the MX record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-109">Gibt die Definition einen MX-Eintrag, legen Sie die DNS-Zone zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d7351-109">Specifies definition of a MX record set to be attached to the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-110">Legen Sie die Phase, die Konfiguration für den MX-Eintrag darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-110">The stage representing configuration for the MX record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineNSRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineNSRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.INSRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineNSRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineNSRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNSRecordSet (name As String) As INSRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNSRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineNSRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-111">Name des NS Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="d7351-111">Name of the NS record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-112">Gibt die Definition ein Namenservereintrag legen Sie die DNS-Zone zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d7351-112">Specifies definition of an NS record set to be attached to the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-113">Die Phase, Konfiguration für die Datensatzgruppe NS darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-113">The stage representing configuration for the NS record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefinePtrRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefinePtrRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IPtrRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefinePtrRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefinePtrRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefinePtrRecordSet (name As String) As IPtrRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefinePtrRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefinePtrRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-114">Name der PTR-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-114">Name of the PTR record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-115">Gibt die Definition einen PTR-Eintrag, legen Sie die DNS-Zone zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d7351-115">Specifies definition of a PTR record set to be attached to the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-116">Die Phase, die Konfiguration für den PTR-Ressourceneintragssatz darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-116">The stage representing configuration for the PTR record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineSrvRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineSrvRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ISrvRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineSrvRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineSrvRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSrvRecordSet (name As String) As ISrvRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSrvRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineSrvRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-117">Der Name des SRV-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-117">The name of the SRV record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-118">Gibt die Definition für eine SRV-Datensatzgruppe an die DNS-Zone angefügt werden.</span><span class="sxs-lookup"><span data-stu-id="d7351-118">Specifies definition of a SRV record set to be attached to the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-119">Die Phase, die Konfiguration für den SRV-Ressourceneintragssatz darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-119">The stage representing configuration for the SRV record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineTxtRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineTxtRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ITxtRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt; DefineTxtRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.DefineTxtRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineTxtRecordSet (name As String) As ITxtRecordSetBlank(Of IUpdate)" />
      <MemberSignature Language="F#" Value="abstract member DefineTxtRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;" Usage="iWithRecordSet.DefineTxtRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateDefinition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-120">Der Name der TXT-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-120">The name of the TXT record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-121">Gibt die Definition einen TXT-Eintrag, legen Sie die DNS-Zone zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d7351-121">Specifies definition of a TXT record set to be attached to the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-122">Legen Sie die Phase, die Konfiguration für den TXT-Eintrag darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-122">The stage representing configuration for the TXT record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateAaaaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet UpdateAaaaRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet UpdateAaaaRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateAaaaRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateAaaaRecordSet (name As String) As IUpdateAaaaRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateAaaaRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet" Usage="iWithRecordSet.UpdateAaaaRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateAaaaRecordSet.IUpdateAaaaRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-123">Name der AAAA-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-123">Name of the AAAA record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-124">Startet die Beschreibung eines Updates aus einem vorhandenen AAAA-Datensatz in dieser DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-124">Begins the description of an update of an existing AAAA record set in this DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-125">Die Phase, die Konfiguration für den AAAA-Ressourceneintragssatz darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-125">The stage representing configuration for the AAAA record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateARecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet UpdateARecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet UpdateARecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateARecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateARecordSet (name As String) As IUpdateARecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateARecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet" Usage="iWithRecordSet.UpdateARecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateARecordSet.IUpdateARecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-126">Name der A-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-126">Name of the A record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-127">Startet die Beschreibung des ein Update einer vorhandenen eine Datensatzgruppe in dieser DNS-Zone.</span><span class="sxs-lookup"><span data-stu-id="d7351-127">Begins the description of an update of an existing A record set in this DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-128">Legen Sie die Phase, die Konfiguration für den A-Eintrag darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-128">The stage representing configuration for the A record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateCNameRecordSet.IUpdateCNameRecordSet UpdateCNameRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateCNameRecordSet.IUpdateCNameRecordSet UpdateCNameRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateCNameRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateCNameRecordSet (name As String) As IUpdateCNameRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateCNameRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateCNameRecordSet.IUpdateCNameRecordSet" Usage="iWithRecordSet.UpdateCNameRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateCNameRecordSet.IUpdateCNameRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateMXRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet UpdateMXRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet UpdateMXRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateMXRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateMXRecordSet (name As String) As IUpdateMXRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateMXRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet" Usage="iWithRecordSet.UpdateMXRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateMXRecordSet.IUpdateMXRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-129">Der Name des MX-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-129">Name of the MX record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-130">Startet die Beschreibung eines Updates für eine vorhandene MX-Eintrag in dieser DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-130">Begins the description of an update of an existing MX record set in this DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-131">Legen Sie die Phase, die Konfiguration für den MX-Eintrag darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-131">The stage representing configuration for the MX record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateNSRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet UpdateNSRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet UpdateNSRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateNSRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateNSRecordSet (name As String) As IUpdateNSRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateNSRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet" Usage="iWithRecordSet.UpdateNSRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateNSRecordSet.IUpdateNSRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-132">Name des NS Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="d7351-132">Name of the NS record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-133">Startet die Beschreibung eines Updates von einem vorhandenen NS-Datensatz in dieser DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-133">Begins the description of an update of an existing NS record set in this DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-134">Die Phase, Konfiguration für die Datensatzgruppe NS darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-134">The stage representing configuration for the NS record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdatePtrRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet UpdatePtrRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet UpdatePtrRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdatePtrRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdatePtrRecordSet (name As String) As IUpdatePtrRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdatePtrRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet" Usage="iWithRecordSet.UpdatePtrRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdatePtrRecordSet.IUpdatePtrRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-135">Name der PTR-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-135">Name of the PTR record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-136">Startet die Beschreibung eines Updates von einem vorhandenen PTR-Eintrag in dieser DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-136">Begins the description of an update of an existing PTR record set in this DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-137">Die Phase, die Konfiguration für den PTR-Ressourceneintragssatz darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-137">The stage representing configuration for the PTR record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateSoaRecord">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord UpdateSoaRecord ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord UpdateSoaRecord() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateSoaRecord" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSoaRecord () As IUpdateSoaRecord" />
      <MemberSignature Language="F#" Value="abstract member UpdateSoaRecord : unit -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord" Usage="iWithRecordSet.UpdateSoaRecord " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSoaRecord.IUpdateSoaRecord</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="d7351-138">Ruft die Phase, die Konfiguration für den TXT-Ressourceneintragssatz darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-138">Gets the stage representing configuration for the TXT record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpdateSrvRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet UpdateSrvRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet UpdateSrvRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateSrvRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateSrvRecordSet (name As String) As IUpdateSrvRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateSrvRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet" Usage="iWithRecordSet.UpdateSrvRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateSrvRecordSet.IUpdateSrvRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-139">Der Name des SRV-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-139">The name of the SRV record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-140">Startet die Beschreibung eines Updates einen vorhandenen SRV-Eintrag in dieser DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-140">Begins the description of an update of an existing SRV record set in this DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-141">Die Phase, die Konfiguration für den SRV-Ressourceneintragssatz darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-141">The stage representing configuration for the SRV record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="UpdateTxtRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateTxtRecordSet.IUpdateTxtRecordSet UpdateTxtRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateTxtRecordSet.IUpdateTxtRecordSet UpdateTxtRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.UpdateTxtRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function UpdateTxtRecordSet (name As String) As IUpdateTxtRecordSet" />
      <MemberSignature Language="F#" Value="abstract member UpdateTxtRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateTxtRecordSet.IUpdateTxtRecordSet" Usage="iWithRecordSet.UpdateTxtRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.UpdateTxtRecordSet.IUpdateTxtRecordSet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-142">Der Name der TXT-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-142">The name of the TXT record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-143">Startet die Beschreibung eines Updates von einem vorhandenen TXT-Eintrag in dieser DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-143">Begins the description of an update of an existing TXT record set in this DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-144">Legen Sie die Phase, die Konfiguration für den TXT-Eintrag darstellt.</span><span class="sxs-lookup"><span data-stu-id="d7351-144">The stage representing configuration for the TXT record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithCNameRecordSet (string name, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithCNameRecordSet(string name, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithCNameRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCNameRecordSet (name As String, alias As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithCNameRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithCNameRecordSet (name, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-145">Der Name des CNAME-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-145">Name of the CNAME record set.</span></span></param>
        <param name="alias"><span data-ttu-id="d7351-146">Der Alias für den CNAME-Datensatz.</span><span class="sxs-lookup"><span data-stu-id="d7351-146">The CNAME record alias.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-147">Gibt die Definition einen CNAME-Eintrag, legen Sie die DNS-Zone zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="d7351-147">Specifies definition of a CNAME record set to be attached to the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-148">Die nächste Phase der DNS-Zone Definition.</span><span class="sxs-lookup"><span data-stu-id="d7351-148">The next stage of DNS zone definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAaaaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutAaaaRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutAaaaRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutAaaaRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAaaaRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAaaaRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutAaaaRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-149">Name der AAAA-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-149">Name of the AAAA record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-150">Entfernt einen AAAA-Datensatz in der DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-150">Removes a AAAA record set in the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-151">Die nächste Phase der DNS-Zone aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d7351-151">The next stage of DNS zone update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAaaaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutAaaaRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutAaaaRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutAaaaRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAaaaRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAaaaRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutAaaaRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutARecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutARecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutARecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutARecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutARecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutARecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutARecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-152">Name der A-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-152">Name of the A record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-153">Entfernt einen A-Datensatz in der DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-153">Removes a A record set in the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-154">Die nächste Phase der DNS-Zone aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d7351-154">The next stage of DNS zone update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutARecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutARecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutARecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutARecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutARecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutARecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutARecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutCNameRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutCNameRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutCNameRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutCNameRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutCNameRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutCNameRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-155">Der Name des CNAME-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-155">Name of the CNAME record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-156">Entfernt einen CNAME-Eintrag in der DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-156">Removes a CNAME record set in the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-157">Die nächste Phase der DNS-Zone aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d7351-157">The next stage of DNS zone update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutCNameRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutCNameRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutCNameRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutCNameRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutCNameRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutCNameRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutMXRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutMXRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutMXRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutMXRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMXRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMXRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutMXRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-158">Der Name des MX-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-158">Name of the MX record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-159">Entfernt einen MX-Eintrag in der DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-159">Removes a MX record set in the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-160">Die nächste Phase der DNS-Zone aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d7351-160">The next stage of DNS zone update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutMXRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutMXRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutMXRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutMXRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutMXRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutMXRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutMXRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutNSRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutNSRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutNSRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutNSRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutNSRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutNSRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutNSRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-161">Name des NS Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="d7351-161">Name of the NS record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-162">Entfernt einen Namenservereintrag in der DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-162">Removes a NS record set in the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-163">Die nächste Phase der DNS-Zone aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d7351-163">The next stage of DNS zone update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutNSRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutNSRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutNSRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutNSRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutNSRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutNSRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutNSRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutPtrRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutPtrRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutPtrRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutPtrRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPtrRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPtrRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutPtrRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-164">Name der PTR-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-164">Name of the PTR record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-165">Entfernt einen PTR-Eintrag in der DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-165">Removes a PTR record set in the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-166">Die nächste Phase der DNS-Zone aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d7351-166">The next stage of DNS zone update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPtrRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutPtrRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutPtrRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutPtrRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPtrRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutPtrRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutPtrRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutSrvRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutSrvRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutSrvRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutSrvRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSrvRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSrvRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutSrvRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-167">Der Name des SRV-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-167">Name of the SRV record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-168">Entfernt einen SRV-Datensatz in der DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-168">Removes a SRV record set in the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-169">Die nächste Phase der DNS-Zone aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d7351-169">The next stage of DNS zone update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSrvRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutSrvRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutSrvRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutSrvRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSrvRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSrvRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutSrvRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="WithoutTxtRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutTxtRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutTxtRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutTxtRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTxtRecordSet (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutTxtRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutTxtRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="d7351-170">Name der TXT-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-170">Name of the TXT record set.</span></span></param>
        <summary>
            <span data-ttu-id="d7351-171">Entfernt einen TXT-Eintrag in der DNS-Zone festgelegt.</span><span class="sxs-lookup"><span data-stu-id="d7351-171">Removes a TXT record set in the DNS zone.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d7351-172">Die nächste Phase der DNS-Zone aktualisieren.</span><span class="sxs-lookup"><span data-stu-id="d7351-172">The next stage of DNS zone update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutTxtRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutTxtRecordSet (string name, string eTagValue);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate WithoutTxtRecordSet(string name, string eTagValue) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IWithRecordSet.WithoutTxtRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutTxtRecordSet (name As String, eTagValue As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutTxtRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate" Usage="iWithRecordSet.WithoutTxtRecordSet (name, eTagValue)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="eTagValue" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">To be added.</param>
        <param name="eTagValue">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>