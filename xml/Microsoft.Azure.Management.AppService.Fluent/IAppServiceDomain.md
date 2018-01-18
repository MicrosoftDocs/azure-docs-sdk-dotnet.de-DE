<Type Name="IAppServiceDomain" FullName="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain">
  <TypeSignature Language="C#" Value="public interface IAppServiceDomain : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServiceDomain implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServiceDomain&#xA;Implements IBeta, IGroupableResource(Of IAppServiceManager, DomainInner), IHasInner(Of DomainInner), IHasManager(Of IAppServiceManager), IRefreshable(Of IAppServiceDomain), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IAppServiceDomain = interface&#xA;    interface IBeta&#xA;    interface IGroupableResource&lt;IAppServiceManager, DomainInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasInner&lt;DomainInner&gt;&#xA;    interface IRefreshable&lt;IAppServiceDomain&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.DomainInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.AppServiceDomain.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d98bf-101">Eine unveränderliche clientseitige Darstellung einer Domäne.</span><span class="sxs-lookup"><span data-stu-id="d98bf-101">An immutable client-side representation of a domain.</span></span>
            <span data-ttu-id="d98bf-102">Domänen in Azure sind von 3rd Party Domain-Anbieter erworben haben.</span><span class="sxs-lookup"><span data-stu-id="d98bf-102">Domains in Azure are purchased from 3rd party domain providers.</span></span> <span data-ttu-id="d98bf-103">Durch Aufrufen von Creatable.create() oder Creatable.createAsync() stimmen Sie die Verträge in AppServiceDomains.listAgreements(String) aufgeführt.</span><span class="sxs-lookup"><span data-stu-id="d98bf-103">By calling Creatable.create() or  Creatable.createAsync() you agree to the agreements listed in  AppServiceDomains.listAgreements(String).</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="d98bf-104">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="d98bf-104">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AdminContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact AdminContact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact AdminContact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.AdminContact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AdminContact As Contact" />
      <MemberSignature Language="F#" Value="member this.AdminContact : Microsoft.Azure.Management.AppService.Fluent.Models.Contact" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.AdminContact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-105">Ruft die Kontaktinformationen für Administrator ab.</span><span class="sxs-lookup"><span data-stu-id="d98bf-105">Gets admin contact information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoRenew">
      <MemberSignature Language="C#" Value="public bool AutoRenew { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AutoRenew" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.AutoRenew" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoRenew As Boolean" />
      <MemberSignature Language="F#" Value="member this.AutoRenew : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.AutoRenew" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-106">Ruft "true", wenn die Domäne wird automatisch erneuert.</span><span class="sxs-lookup"><span data-stu-id="d98bf-106">Gets true if domain will renewed automatically.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="BillingContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact BillingContact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact BillingContact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.BillingContact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property BillingContact As Contact" />
      <MemberSignature Language="F#" Value="member this.BillingContact : Microsoft.Azure.Management.AppService.Fluent.Models.Contact" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.BillingContact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-107">Ruft die Kontaktinformationen Abrechnung.</span><span class="sxs-lookup"><span data-stu-id="d98bf-107">Gets billing contact information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Consent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent Consent { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent Consent" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.Consent" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Consent As DomainPurchaseConsent" />
      <MemberSignature Language="F#" Value="member this.Consent : Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.Consent" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.DomainPurchaseConsent</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-108">Ruft die Zustimmung rechtsgültigen Vertrag ab.</span><span class="sxs-lookup"><span data-stu-id="d98bf-108">Gets legal agreement consent.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CreatedTime">
      <MemberSignature Language="C#" Value="public DateTime CreatedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime CreatedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.CreatedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CreatedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.CreatedTime : DateTime" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.CreatedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-109">Ruft die Domäne Erstellungszeitstempel ab.</span><span class="sxs-lookup"><span data-stu-id="d98bf-109">Gets domain creation timestamp.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationTime">
      <MemberSignature Language="C#" Value="public DateTime ExpirationTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpirationTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ExpirationTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpirationTime : DateTime" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ExpirationTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-110">Ruft die Ablaufzeit Zeitstempel Domäne ab.</span><span class="sxs-lookup"><span data-stu-id="d98bf-110">Gets domain expiration timestamp.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastRenewedTime">
      <MemberSignature Language="C#" Value="public DateTime LastRenewedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastRenewedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.LastRenewedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastRenewedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastRenewedTime : DateTime" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.LastRenewedTime" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.DateTime</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-111">Ruft die Zeitstempel ab, wenn die Domäne zuletzt erneuert wurde.</span><span class="sxs-lookup"><span data-stu-id="d98bf-111">Gets timestamp when the domain was renewed last time.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ManagedHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt; ManagedHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt; ManagedHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ManagedHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ManagedHostNames As IReadOnlyDictionary(Of String, HostName)" />
      <MemberSignature Language="F#" Value="member this.ManagedHostNames : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ManagedHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.Models.HostName&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-112">Ruft alle Hostnamen abgeleitet aus der Domäne und Azure-Ressourcen zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="d98bf-112">Gets all hostnames derived from the domain and assigned to Azure resources.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NameServers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; NameServers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; NameServers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.NameServers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NameServers As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.NameServers : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.NameServers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-113">Ruft die Namenservern ab.</span><span class="sxs-lookup"><span data-stu-id="d98bf-113">Gets name servers.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Privacy">
      <MemberSignature Language="C#" Value="public bool Privacy { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Privacy" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.Privacy" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Privacy As Boolean" />
      <MemberSignature Language="F#" Value="member this.Privacy : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.Privacy" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-114">Ruft "true", wenn die Domäne Datenschutz für diese Domäne aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="d98bf-114">Gets true if domain privacy is enabled for this domain.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReadyForDnsRecordManagement">
      <MemberSignature Language="C#" Value="public bool ReadyForDnsRecordManagement { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ReadyForDnsRecordManagement" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ReadyForDnsRecordManagement" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ReadyForDnsRecordManagement As Boolean" />
      <MemberSignature Language="F#" Value="member this.ReadyForDnsRecordManagement : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.ReadyForDnsRecordManagement" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-115">Ruft "true", wenn Azure Web Apps diese Domäne zuweisen kann.</span><span class="sxs-lookup"><span data-stu-id="d98bf-115">Gets true if Azure can assign this domain to Web Apps.</span></span> <span data-ttu-id="d98bf-116">Dieser Wert ist "true", wenn die Domäne der Registrierungsstatus ist aktiv, und es Namenserver, die Azure programmgesteuerten Zugriff auf gehostet wird.</span><span class="sxs-lookup"><span data-stu-id="d98bf-116">This value will be true if domain registration status is active and it is hosted on name servers Azure has programmatic access to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrantContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact RegistrantContact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact RegistrantContact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.RegistrantContact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegistrantContact As Contact" />
      <MemberSignature Language="F#" Value="member this.RegistrantContact : Microsoft.Azure.Management.AppService.Fluent.Models.Contact" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.RegistrantContact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-117">Ruft Registrant-Kontaktinformationen.</span><span class="sxs-lookup"><span data-stu-id="d98bf-117">Gets registrant contact information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RegistrationStatus">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus RegistrationStatus { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus RegistrationStatus" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.RegistrationStatus" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RegistrationStatus As DomainStatus" />
      <MemberSignature Language="F#" Value="member this.RegistrationStatus : Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.RegistrationStatus" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.DomainStatus</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-118">Ruft die Domäne Registrierungsstatus ab.</span><span class="sxs-lookup"><span data-stu-id="d98bf-118">Gets domain registration status.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TechContact">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.Contact TechContact { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.Contact TechContact" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.TechContact" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TechContact As Contact" />
      <MemberSignature Language="F#" Value="member this.TechContact : Microsoft.Azure.Management.AppService.Fluent.Models.Contact" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.TechContact" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.Contact</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="d98bf-119">Ruft die technischen Kontaktinformationen ab.</span><span class="sxs-lookup"><span data-stu-id="d98bf-119">Gets technical contact information.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnership">
      <MemberSignature Language="C#" Value="public void VerifyDomainOwnership (string certificateOrderName, string domainVerificationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void VerifyDomainOwnership(string certificateOrderName, string domainVerificationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.VerifyDomainOwnership(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub VerifyDomainOwnership (certificateOrderName As String, domainVerificationToken As String)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnership : string * string -&gt; unit" Usage="iAppServiceDomain.VerifyDomainOwnership (certificateOrderName, domainVerificationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="domainVerificationToken" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateOrderName"><span data-ttu-id="d98bf-120">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="d98bf-120">The name of the certificate order.</span></span></param>
        <param name="domainVerificationToken"><span data-ttu-id="d98bf-121">Die Domäne Überprüfung-Token für die Zertifikat-Bestellung.</span><span class="sxs-lookup"><span data-stu-id="d98bf-121">The domain verification token for the certificate order.</span></span></param>
        <summary>
            <span data-ttu-id="d98bf-122">Überprüft den Besitz der Domäne, für eine zertifikatreihenfolge mit dieser Domäne gebunden.</span><span class="sxs-lookup"><span data-stu-id="d98bf-122">Verifies the ownership of the domain for a certificate order bound to this domain.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task VerifyDomainOwnershipAsync (string certificateOrderName, string domainVerificationToken, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task VerifyDomainOwnershipAsync(string certificateOrderName, string domainVerificationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain.VerifyDomainOwnershipAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnershipAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iAppServiceDomain.VerifyDomainOwnershipAsync (certificateOrderName, domainVerificationToken, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrderName" Type="System.String" />
        <Parameter Name="domainVerificationToken" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="certificateOrderName"><span data-ttu-id="d98bf-123">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="d98bf-123">The name of the certificate order.</span></span></param>
        <param name="domainVerificationToken"><span data-ttu-id="d98bf-124">Die Domäne Überprüfung-Token für die Zertifikat-Bestellung.</span><span class="sxs-lookup"><span data-stu-id="d98bf-124">The domain verification token for the certificate order.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="d98bf-125">Überprüft den Besitz der Domäne, für eine zertifikatreihenfolge mit dieser Domäne gebunden.</span><span class="sxs-lookup"><span data-stu-id="d98bf-125">Verifies the ownership of the domain for a certificate order bound to this domain.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d98bf-126">Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="d98bf-126">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>