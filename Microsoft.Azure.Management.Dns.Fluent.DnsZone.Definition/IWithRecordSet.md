<Type Name="IWithRecordSet" FullName="Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet">
  <TypeSignature Language="C#" Value="public interface IWithRecordSet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithRecordSet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithRecordSet" />
  <TypeSignature Language="F#" Value="type IWithRecordSet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="10edf-101">Die Phase des DNS-zone Definition Ressourceneintragssatz angeben können.</span><span class="sxs-lookup"><span data-stu-id="10edf-101">The stage of the DNS zone definition allowing to specify record set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="DefineAaaaRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineAaaaRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IAaaaRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineAaaaRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineAaaaRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineAaaaRecordSet (name As String) As IAaaaRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineAaaaRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineAaaaRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IAaaaRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="10edf-102">Name der AAAA-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="10edf-102">Name of the AAAA record set.</span></span></param>
        <summary>
            <span data-ttu-id="10edf-103">Gibt die Definition einer AAAA-Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="10edf-103">Specifies definition of an AAAA record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="10edf-104">Die Phase, die Konfiguration für den AAAA-Ressourceneintragssatz darstellt.</span><span class="sxs-lookup"><span data-stu-id="10edf-104">The stage representing configuration for the AAAA record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineARecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineARecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IARecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineARecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineARecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineARecordSet (name As String) As IARecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineARecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineARecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IARecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="10edf-105">Name der A-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="10edf-105">Name of the A record set.</span></span></param>
        <summary>
            <span data-ttu-id="10edf-106">Gibt die Definition einer Datensatzgruppe ein.</span><span class="sxs-lookup"><span data-stu-id="10edf-106">Specifies definition of an A record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="10edf-107">Legen Sie die Phase, die Konfiguration für den A-Eintrag darstellt.</span><span class="sxs-lookup"><span data-stu-id="10edf-107">The stage representing configuration for the A record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineCNameRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ICNameRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineCNameRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineCNameRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineCNameRecordSet (name As String) As ICNameRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineCNameRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineCNameRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ICNameRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
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
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineMXRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IMXRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineMXRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineMXRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineMXRecordSet (name As String) As IMXRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineMXRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineMXRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IMXRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="10edf-108">Der Name des MX-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="10edf-108">Name of the MX record set.</span></span></param>
        <summary>
            <span data-ttu-id="10edf-109">Gibt einen MX-Ressourceneintragssatz Definition.</span><span class="sxs-lookup"><span data-stu-id="10edf-109">Specifies definition of a MX record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="10edf-110">Legen Sie die Phase, die Konfiguration für den MX-Eintrag darstellt.</span><span class="sxs-lookup"><span data-stu-id="10edf-110">The stage representing configuration for the MX record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineNSRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineNSRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.INSRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineNSRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineNSRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineNSRecordSet (name As String) As INSRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineNSRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineNSRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.INSRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="10edf-111">Name des NS Ressourceneintragssatz.</span><span class="sxs-lookup"><span data-stu-id="10edf-111">Name of the NS record set.</span></span></param>
        <summary>
            <span data-ttu-id="10edf-112">Gibt eine Datensatzgruppe NS-Definition.</span><span class="sxs-lookup"><span data-stu-id="10edf-112">Specifies definition of an NS record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="10edf-113">Die Phase, Konfiguration für die Datensatzgruppe NS darstellt.</span><span class="sxs-lookup"><span data-stu-id="10edf-113">The stage representing configuration for the NS record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefinePtrRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefinePtrRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IPtrRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefinePtrRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefinePtrRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefinePtrRecordSet (name As String) As IPtrRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefinePtrRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefinePtrRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.IPtrRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="10edf-114">Name der PTR-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="10edf-114">Name of the PTR record set.</span></span></param>
        <summary>
            <span data-ttu-id="10edf-115">Gibt einen PTR-Ressourceneintragssatz Definition.</span><span class="sxs-lookup"><span data-stu-id="10edf-115">Specifies definition of a PTR record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="10edf-116">Die Phase, die Konfiguration für den PTR-Ressourceneintragssatz darstellt.</span><span class="sxs-lookup"><span data-stu-id="10edf-116">The stage representing configuration for the PTR record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineSrvRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineSrvRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ISrvRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineSrvRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineSrvRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineSrvRecordSet (name As String) As ISrvRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineSrvRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineSrvRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ISrvRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="10edf-117">Der Name des SRV-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="10edf-117">The name of the SRV record set.</span></span></param>
        <summary>
            <span data-ttu-id="10edf-118">Gibt die Definition einer SRV-Datensatzgruppe an.</span><span class="sxs-lookup"><span data-stu-id="10edf-118">Specifies definition of a SRV record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="10edf-119">Die Phase, die Konfiguration für den SRV-Ressourceneintragssatz darstellt.</span><span class="sxs-lookup"><span data-stu-id="10edf-119">The stage representing configuration for the SRV record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="DefineTxtRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineTxtRecordSet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ITxtRecordSetBlank`1&lt;class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt; DefineTxtRecordSet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.DefineTxtRecordSet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function DefineTxtRecordSet (name As String) As ITxtRecordSetBlank(Of IWithCreate)" />
      <MemberSignature Language="F#" Value="abstract member DefineTxtRecordSet : string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;" Usage="iWithRecordSet.DefineTxtRecordSet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsRecordSet.Definition.ITxtRecordSetBlank&lt;Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="10edf-120">Der Name der TXT-Eintrag festgelegt.</span><span class="sxs-lookup"><span data-stu-id="10edf-120">The name of the TXT record set.</span></span></param>
        <summary>
            <span data-ttu-id="10edf-121">Gibt einen TXT-Ressourceneintragssatz Definition.</span><span class="sxs-lookup"><span data-stu-id="10edf-121">Specifies definition of a TXT record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="10edf-122">Legen Sie die Phase, die Konfiguration für den TXT-Eintrag darstellt.</span><span class="sxs-lookup"><span data-stu-id="10edf-122">The stage representing configuration for the TXT record set.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithCNameRecordSet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate WithCNameRecordSet (string name, string alias);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate WithCNameRecordSet(string name, string alias) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithRecordSet.WithCNameRecordSet(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithCNameRecordSet (name As String, alias As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithCNameRecordSet : string * string -&gt; Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate" Usage="iWithRecordSet.WithCNameRecordSet (name, alias)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Dns.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Dns.Fluent.DnsZone.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="alias" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="10edf-123">Der Name des CNAME-Eintrags festgelegt.</span><span class="sxs-lookup"><span data-stu-id="10edf-123">Name of the CNAME record set.</span></span></param>
        <param name="alias"><span data-ttu-id="10edf-124">Der Alias für den CNAME-Datensatz.</span><span class="sxs-lookup"><span data-stu-id="10edf-124">The CNAME record alias.</span></span></param>
        <summary>
            <span data-ttu-id="10edf-125">Gibt einen CNAME-Ressourceneintragssatz Definition.</span><span class="sxs-lookup"><span data-stu-id="10edf-125">Specifies definition of a CNAME record set.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="10edf-126">Die nächste Phase der DNS-Zone Definition.</span><span class="sxs-lookup"><span data-stu-id="10edf-126">The next stage of DNS zone definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>