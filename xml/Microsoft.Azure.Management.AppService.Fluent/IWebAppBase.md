<Type Name="IWebAppBase" FullName="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase">
  <TypeSignature Language="C#" Value="public interface IWebAppBase : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWebAppBase implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWebAppBase&#xA;Implements IBeta, IGroupableResource(Of IAppServiceManager, SiteInner), IHasInner(Of SiteInner), IHasManager(Of IAppServiceManager)" />
  <TypeSignature Language="F#" Value="type IWebAppBase = interface&#xA;    interface IBeta&#xA;    interface IHasName&#xA;    interface IGroupableResource&lt;IAppServiceManager, SiteInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasInner&lt;SiteInner&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.SiteInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="66e82-101">Eine unveränderliche clientseitige Darstellung einer Bereitstellung oder Azure-Web-App-Slots.</span><span class="sxs-lookup"><span data-stu-id="66e82-101">An immutable client-side representation of an Azure Web App or deployment slot.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="66e82-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="66e82-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="AlwaysOn">
      <MemberSignature Language="C#" Value="public bool AlwaysOn { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool AlwaysOn" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AlwaysOn" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AlwaysOn As Boolean" />
      <MemberSignature Language="F#" Value="member this.AlwaysOn : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AlwaysOn" />
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
            <span data-ttu-id="66e82-103">Ruft ab, wenn die Web-app immer eingeschaltet ist.</span><span class="sxs-lookup"><span data-stu-id="66e82-103">Gets if the web app is always on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplySlotConfigurations">
      <MemberSignature Language="C#" Value="public void ApplySlotConfigurations (string slotName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ApplySlotConfigurations(string slotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ApplySlotConfigurations(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub ApplySlotConfigurations (slotName As String)" />
      <MemberSignature Language="F#" Value="abstract member ApplySlotConfigurations : string -&gt; unit" Usage="iWebAppBase.ApplySlotConfigurations slotName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="slotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="slotName"><span data-ttu-id="66e82-104">Der zielslot anzuwendende Konfigurationen aus.</span><span class="sxs-lookup"><span data-stu-id="66e82-104">The target slot to apply configurations from.</span></span></param>
        <summary>
            <span data-ttu-id="66e82-105">Anwenden des Slots (oder persistente) Konfigurationen aus dem angegebenen Slot auf der aktuellen Aktivität.</span><span class="sxs-lookup"><span data-stu-id="66e82-105">Apply the slot (or sticky) configurations from the specified slot to the current one.</span></span> <span data-ttu-id="66e82-106">Dies ist nützlich für "Swap-Preview".</span><span class="sxs-lookup"><span data-stu-id="66e82-106">This is useful for "Swap with Preview".</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ApplySlotConfigurationsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ApplySlotConfigurationsAsync (string slotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ApplySlotConfigurationsAsync(string slotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ApplySlotConfigurationsAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ApplySlotConfigurationsAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.ApplySlotConfigurationsAsync (slotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="slotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="slotName"><span data-ttu-id="66e82-107">Der zielslot anzuwendende Konfigurationen aus.</span><span class="sxs-lookup"><span data-stu-id="66e82-107">The target slot to apply configurations from.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="66e82-108">Anwenden des Slots (oder persistente) Konfigurationen aus dem angegebenen Slot auf der aktuellen Aktivität.</span><span class="sxs-lookup"><span data-stu-id="66e82-108">Apply the slot (or sticky) configurations from the specified slot to the current one.</span></span> <span data-ttu-id="66e82-109">Dies ist nützlich für "Swap-Preview".</span><span class="sxs-lookup"><span data-stu-id="66e82-109">This is useful for "Swap with Preview".</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-110">Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="66e82-110">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="AppServicePlanId">
      <MemberSignature Language="C#" Value="public string AppServicePlanId { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AppServicePlanId" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AppServicePlanId" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AppServicePlanId As String" />
      <MemberSignature Language="F#" Value="member this.AppServicePlanId : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AppServicePlanId" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-111">Ruft die Ressourcen-ID der app Service-Plan ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-111">Gets The resource ID of the app service plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AutoSwapSlotName">
      <MemberSignature Language="C#" Value="public string AutoSwapSlotName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string AutoSwapSlotName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AutoSwapSlotName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AutoSwapSlotName As String" />
      <MemberSignature Language="F#" Value="member this.AutoSwapSlotName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AutoSwapSlotName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-112">Ruft den automatischen Austausch Slot-Name.</span><span class="sxs-lookup"><span data-stu-id="66e82-112">Gets the auto swap slot name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="AvailabilityState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState AvailabilityState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState AvailabilityState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AvailabilityState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property AvailabilityState As SiteAvailabilityState" />
      <MemberSignature Language="F#" Value="member this.AvailabilityState : Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.AvailabilityState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.SiteAvailabilityState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-113">Ruft den Verfügbarkeitsstatus für Management-Informationen für die Web-app ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-113">Gets management information availability state for the web app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientAffinityEnabled">
      <MemberSignature Language="C#" Value="public bool ClientAffinityEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ClientAffinityEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ClientAffinityEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientAffinityEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ClientAffinityEnabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ClientAffinityEnabled" />
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
            <span data-ttu-id="66e82-114">Ruft laden die Clientaffinität aktiviert wird beim Lastenausgleich von HTTP-Anforderung für mehrere Instanzen der Web-app.</span><span class="sxs-lookup"><span data-stu-id="66e82-114">Gets if the client affinity is enabled when load balancing http request for multiple instances of the web app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ClientCertEnabled">
      <MemberSignature Language="C#" Value="public bool ClientCertEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ClientCertEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ClientCertEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ClientCertEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.ClientCertEnabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ClientCertEnabled" />
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
            <span data-ttu-id="66e82-115">Ruft ab, wenn das Clientzertifikat für die Web-app aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="66e82-115">Gets if the client certificate is enabled for the web app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="CloningInfo">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo CloningInfo { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo CloningInfo" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.CloningInfo" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CloningInfo As CloningInfo" />
      <MemberSignature Language="F#" Value="member this.CloningInfo : Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.CloningInfo" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.CloningInfo</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-116">Ruft Informationen zu gibt an, ob die Web-app von einem anderen geklont wird.</span><span class="sxs-lookup"><span data-stu-id="66e82-116">Gets information about whether the web app is cloned from another.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ContainerSize">
      <MemberSignature Language="C#" Value="public int ContainerSize { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 ContainerSize" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ContainerSize" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ContainerSize As Integer" />
      <MemberSignature Language="F#" Value="member this.ContainerSize : int" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ContainerSize" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-117">Ruft die Größe eines Containers Funktion ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-117">Gets size of a function container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultDocuments">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; DefaultDocuments { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; DefaultDocuments" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.DefaultDocuments" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultDocuments As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.DefaultDocuments : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.DefaultDocuments" />
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
            <span data-ttu-id="66e82-118">Ruft die Standarddokumente ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-118">Gets the default documents.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DefaultHostName">
      <MemberSignature Language="C#" Value="public string DefaultHostName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string DefaultHostName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.DefaultHostName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property DefaultHostName As String" />
      <MemberSignature Language="F#" Value="member this.DefaultHostName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.DefaultHostName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-119">Ruft die Standard-Hostname der Web-app.</span><span class="sxs-lookup"><span data-stu-id="66e82-119">Gets default hostname of the web app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deploy">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebDeployment.Definition.IWithPackageUri Deploy ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebDeployment.Definition.IWithPackageUri Deploy() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Deploy" />
      <MemberSignature Language="VB.NET" Value="Public Function Deploy () As IWithPackageUri" />
      <MemberSignature Language="F#" Value="abstract member Deploy : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.WebDeployment.Definition.IWithPackageUri" Usage="iWebAppBase.Deploy " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebDeployment.Definition.IWithPackageUri</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Enabled">
      <MemberSignature Language="C#" Value="public bool Enabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Enabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Enabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Enabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.Enabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Enabled" />
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
            <span data-ttu-id="66e82-120">Ruft "true", wenn die Website aktiviert ist. andernfalls "false".</span><span class="sxs-lookup"><span data-stu-id="66e82-120">Gets true if the site is enabled; otherwise, false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="EnabledHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; EnabledHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; EnabledHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.EnabledHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property EnabledHostNames As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.EnabledHostNames : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.EnabledHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-121">Ruft die Hostnamen für die Web-app, die aktiviert sind.</span><span class="sxs-lookup"><span data-stu-id="66e82-121">Gets host names for the web app that are enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GatewaySiteName">
      <MemberSignature Language="C#" Value="public string GatewaySiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GatewaySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GatewaySiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GatewaySiteName As String" />
      <MemberSignature Language="F#" Value="member this.GatewaySiteName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GatewaySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-122">Ruft ab, der Gateway-app, die WebApp zugeordnet haben.</span><span class="sxs-lookup"><span data-stu-id="66e82-122">Gets name of gateway app associated with web app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppSettings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt; GetAppSettings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt; GetAppSettings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetAppSettings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAppSettings () As IReadOnlyDictionary(Of String, IAppSetting)" />
      <MemberSignature Language="F#" Value="abstract member GetAppSettings : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;" Usage="iWebAppBase.GetAppSettings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAppSettingsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;&gt; GetAppSettingsAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;&gt; GetAppSettingsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetAppSettingsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAppSettingsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;&gt;" Usage="iWebAppBase.GetAppSettingsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IAppSetting&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationConfig">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication GetAuthenticationConfig ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication GetAuthenticationConfig() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetAuthenticationConfig" />
      <MemberSignature Language="VB.NET" Value="Public Function GetAuthenticationConfig () As IWebAppAuthentication" />
      <MemberSignature Language="F#" Value="abstract member GetAuthenticationConfig : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication" Usage="iWebAppBase.GetAuthenticationConfig " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetAuthenticationConfigAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication&gt; GetAuthenticationConfigAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication&gt; GetAuthenticationConfigAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetAuthenticationConfigAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetAuthenticationConfigAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication&gt;" Usage="iWebAppBase.GetAuthenticationConfigAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppAuthentication&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConnectionStrings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt; GetConnectionStrings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt; GetConnectionStrings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetConnectionStrings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetConnectionStrings () As IReadOnlyDictionary(Of String, IConnectionString)" />
      <MemberSignature Language="F#" Value="abstract member GetConnectionStrings : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;" Usage="iWebAppBase.GetConnectionStrings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetConnectionStringsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;&gt; GetConnectionStringsAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;&gt; GetConnectionStringsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetConnectionStringsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetConnectionStringsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;&gt;" Usage="iWebAppBase.GetConnectionStringsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IConnectionString&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetHostNameBindings">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt; GetHostNameBindings ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt; GetHostNameBindings() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetHostNameBindings" />
      <MemberSignature Language="VB.NET" Value="Public Function GetHostNameBindings () As IReadOnlyDictionary(Of String, IHostNameBinding)" />
      <MemberSignature Language="F#" Value="abstract member GetHostNameBindings : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;" Usage="iWebAppBase.GetHostNameBindings " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-123">Die Zuordnung von Hostnamen und der hostnamensbindungen.</span><span class="sxs-lookup"><span data-stu-id="66e82-123">The mapping from host names and the host name bindings.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetHostNameBindingsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;&gt; GetHostNameBindingsAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;&gt; GetHostNameBindingsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetHostNameBindingsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetHostNameBindingsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;&gt;" Usage="iWebAppBase.GetHostNameBindingsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.IHostNameBinding&gt;&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-124">Die Zuordnung von Hostnamen und der hostnamensbindungen.</span><span class="sxs-lookup"><span data-stu-id="66e82-124">The mapping from host names and the host name bindings.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile GetPublishingProfile ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile GetPublishingProfile() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetPublishingProfile" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPublishingProfile () As IPublishingProfile" />
      <MemberSignature Language="F#" Value="abstract member GetPublishingProfile : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile" Usage="iWebAppBase.GetPublishingProfile " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-125">Die URL und die Anmeldeinformationen für die Veröffentlichung über FTP oder Git.</span><span class="sxs-lookup"><span data-stu-id="66e82-125">The URL and credentials for publishing through FTP or Git.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetPublishingProfileAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile&gt; GetPublishingProfileAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile&gt; GetPublishingProfileAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetPublishingProfileAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetPublishingProfileAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile&gt;" Usage="iWebAppBase.GetPublishingProfileAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-126">Die URL und die Anmeldeinformationen für die Veröffentlichung über FTP oder Git.</span><span class="sxs-lookup"><span data-stu-id="66e82-126">The URL and credentials for publishing through FTP or Git.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl GetSourceControl ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl GetSourceControl() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetSourceControl" />
      <MemberSignature Language="VB.NET" Value="Public Function GetSourceControl () As IWebAppSourceControl" />
      <MemberSignature Language="F#" Value="abstract member GetSourceControl : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl" Usage="iWebAppBase.GetSourceControl " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-127">Die Quellinformationen des Steuerelements für die Web-app.</span><span class="sxs-lookup"><span data-stu-id="66e82-127">The source control information for the web app.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="GetSourceControlAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl&gt; GetSourceControlAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl&gt; GetSourceControlAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.GetSourceControlAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member GetSourceControlAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl&gt;" Usage="iWebAppBase.GetSourceControlAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task&lt;Microsoft.Azure.Management.AppService.Fluent.IWebAppSourceControl&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-128">Die Quellinformationen des Steuerelements für die Web-app.</span><span class="sxs-lookup"><span data-stu-id="66e82-128">The source control information for the web app.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="HostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; HostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; HostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNames As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-129">Ruft die Hostnamen Web-app zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="66e82-129">Gets hostnames associated with web app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNamesDisabled">
      <MemberSignature Language="C#" Value="public bool HostNamesDisabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool HostNamesDisabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNamesDisabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNamesDisabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.HostNamesDisabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNamesDisabled" />
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
            <span data-ttu-id="66e82-130">Ruft den öffentlichen Hostnamen sind deaktiviert, die Web-app.</span><span class="sxs-lookup"><span data-stu-id="66e82-130">Gets if the public hostnames are disabled the web app.</span></span>
            <span data-ttu-id="66e82-131">Wenn Set auf "true" die app nur über API Management-Prozesses zugegriffen werden kann ist.</span><span class="sxs-lookup"><span data-stu-id="66e82-131">If set to true the app is only accessible via API Management process.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNameSslStates">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; HostNameSslStates { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt; HostNameSslStates" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNameSslStates" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNameSslStates As IReadOnlyDictionary(Of String, HostNameSslState)" />
      <MemberSignature Language="F#" Value="member this.HostNameSslStates : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.HostNameSslStates" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.AppService.Fluent.Models.HostNameSslState&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-132">Ruft die Liste der SSL-Status verwendet, um die SSL-Bindungen für den Hostnamen des Standorts zu verwalten.</span><span class="sxs-lookup"><span data-stu-id="66e82-132">Gets list of SSL states used to manage the SSL bindings for site's hostnames.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsDefaultContainer">
      <MemberSignature Language="C#" Value="public bool IsDefaultContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsDefaultContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.IsDefaultContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsDefaultContainer As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsDefaultContainer : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.IsDefaultContainer" />
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
            <span data-ttu-id="66e82-133">Ruft Standort ist ein Standardcontainer.</span><span class="sxs-lookup"><span data-stu-id="66e82-133">Gets site is a default container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsPremiumApp">
      <MemberSignature Language="C#" Value="public bool IsPremiumApp { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsPremiumApp" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.IsPremiumApp" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsPremiumApp As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsPremiumApp : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.IsPremiumApp" />
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
            <span data-ttu-id="66e82-134">Ruft ab, ob die Web-app als eine Premium-app bereitgestellt wird.</span><span class="sxs-lookup"><span data-stu-id="66e82-134">Gets whether web app is deployed as a premium app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaContainer">
      <MemberSignature Language="C#" Value="public string JavaContainer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaContainer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaContainer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JavaContainer As String" />
      <MemberSignature Language="F#" Value="member this.JavaContainer : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaContainer" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-135">Ruft die Java-Container ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-135">Gets Java container.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaContainerVersion">
      <MemberSignature Language="C#" Value="public string JavaContainerVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string JavaContainerVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaContainerVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JavaContainerVersion As String" />
      <MemberSignature Language="F#" Value="member this.JavaContainerVersion : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaContainerVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-136">Ruft die Version des Java ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-136">Gets Java container version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="JavaVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.JavaVersion JavaVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.JavaVersion JavaVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property JavaVersion As JavaVersion" />
      <MemberSignature Language="F#" Value="member this.JavaVersion : Microsoft.Azure.Management.AppService.Fluent.JavaVersion" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.JavaVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.JavaVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-137">Ruft die Java-Version ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-137">Gets Java version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LastModifiedTime">
      <MemberSignature Language="C#" Value="public DateTime LastModifiedTime { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime LastModifiedTime" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.LastModifiedTime" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LastModifiedTime As DateTime" />
      <MemberSignature Language="F#" Value="member this.LastModifiedTime : DateTime" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.LastModifiedTime" />
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
            <span data-ttu-id="66e82-138">Ruft die letzte Änderung Web-app in UTC angegeben wurde.</span><span class="sxs-lookup"><span data-stu-id="66e82-138">Gets Last time web app was modified in UTC.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="LinuxFxVersion">
      <MemberSignature Language="C#" Value="public string LinuxFxVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string LinuxFxVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.LinuxFxVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property LinuxFxVersion As String" />
      <MemberSignature Language="F#" Value="member this.LinuxFxVersion : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.LinuxFxVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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
    <Member MemberName="ManagedPipelineMode">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode ManagedPipelineMode { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode ManagedPipelineMode" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ManagedPipelineMode" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ManagedPipelineMode As ManagedPipelineMode" />
      <MemberSignature Language="F#" Value="member this.ManagedPipelineMode : Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ManagedPipelineMode" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.ManagedPipelineMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-139">Ruft der verwaltete Pipelinemodus.</span><span class="sxs-lookup"><span data-stu-id="66e82-139">Gets managed pipeline mode.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MicroService">
      <MemberSignature Language="C#" Value="public string MicroService { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string MicroService" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.MicroService" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MicroService As String" />
      <MemberSignature Language="F#" Value="member this.MicroService : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.MicroService" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-140">Ruft den Namen der Micro-Dienst.</span><span class="sxs-lookup"><span data-stu-id="66e82-140">Gets the micro-service name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NetFrameworkVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion NetFrameworkVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion NetFrameworkVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.NetFrameworkVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetFrameworkVersion As NetFrameworkVersion" />
      <MemberSignature Language="F#" Value="member this.NetFrameworkVersion : Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.NetFrameworkVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.NetFrameworkVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-141">Ruft die .NET Framework-Version ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-141">Gets the .NET Framework version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NodeVersion">
      <MemberSignature Language="C#" Value="public string NodeVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string NodeVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.NodeVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NodeVersion As String" />
      <MemberSignature Language="F#" Value="member this.NodeVersion : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.NodeVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-142">Ruft die Version von Node.JS ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-142">Gets the version of Node.JS.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatingSystem">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.OperatingSystem OperatingSystem { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.OperatingSystem OperatingSystem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.OperatingSystem" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperatingSystem As OperatingSystem" />
      <MemberSignature Language="F#" Value="member this.OperatingSystem : Microsoft.Azure.Management.AppService.Fluent.OperatingSystem" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.OperatingSystem" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.OperatingSystem</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-143">Ruft das Betriebssystem, auf das die Web-app ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="66e82-143">Gets the operating system the web app is running on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OutboundIPAddresses">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; OutboundIPAddresses { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; OutboundIPAddresses" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.OutboundIPAddresses" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OutboundIPAddresses As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.OutboundIPAddresses : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.OutboundIPAddresses" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-144">Ruft die Liste der IP-Adressen, die diese Web-app für ausgehende Verbindungen verwendet.</span><span class="sxs-lookup"><span data-stu-id="66e82-144">Gets list of IP addresses that this web app uses for outbound connections.</span></span> <span data-ttu-id="66e82-145">Diese können verwendet werden, beim Konfigurieren von Firewallregeln für Datenbanken, die diese Web-App zugegriffen.</span><span class="sxs-lookup"><span data-stu-id="66e82-145">Those can be used when configuring firewall rules for databases accessed by this web app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PhpVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.PhpVersion PhpVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.PhpVersion PhpVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PhpVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PhpVersion As PhpVersion" />
      <MemberSignature Language="F#" Value="member this.PhpVersion : Microsoft.Azure.Management.AppService.Fluent.PhpVersion" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PhpVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.PhpVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-146">Ruft die Version von PHP ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-146">Gets the version of PHP.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PlatformArchitecture">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture PlatformArchitecture { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture PlatformArchitecture" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PlatformArchitecture" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PlatformArchitecture As PlatformArchitecture" />
      <MemberSignature Language="F#" Value="member this.PlatformArchitecture : Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PlatformArchitecture" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.PlatformArchitecture</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-147">Ruft die Architektur der Plattform, entweder 32 Bit (x86)- oder 64-Bit-(x64) ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-147">Gets the architecture of the platform, either 32 bit (x86) or 64 bit (x64).</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PythonVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.PythonVersion PythonVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.PythonVersion PythonVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PythonVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PythonVersion As PythonVersion" />
      <MemberSignature Language="F#" Value="member this.PythonVersion : Microsoft.Azure.Management.AppService.Fluent.PythonVersion" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.PythonVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.PythonVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-148">Ruft die Version von Python.</span><span class="sxs-lookup"><span data-stu-id="66e82-148">Gets the version of Python.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteDebuggingEnabled">
      <MemberSignature Language="C#" Value="public bool RemoteDebuggingEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool RemoteDebuggingEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RemoteDebuggingEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteDebuggingEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.RemoteDebuggingEnabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RemoteDebuggingEnabled" />
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
            <span data-ttu-id="66e82-149">Ruft ab, wenn die remote Eebugging aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="66e82-149">Gets if the remote eebugging is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RemoteDebuggingVersion">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion RemoteDebuggingVersion { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion RemoteDebuggingVersion" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RemoteDebuggingVersion" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RemoteDebuggingVersion As RemoteVisualStudioVersion" />
      <MemberSignature Language="F#" Value="member this.RemoteDebuggingVersion : Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RemoteDebuggingVersion" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.RemoteVisualStudioVersion</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-150">Ruft die Version für remote Debuggen.</span><span class="sxs-lookup"><span data-stu-id="66e82-150">Gets the remote debugging version.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RepositorySiteName">
      <MemberSignature Language="C#" Value="public string RepositorySiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string RepositorySiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RepositorySiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property RepositorySiteName As String" />
      <MemberSignature Language="F#" Value="member this.RepositorySiteName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RepositorySiteName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-151">Ruft die Namen der Repository-Website ab.</span><span class="sxs-lookup"><span data-stu-id="66e82-151">Gets name of repository site.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetSlotConfigurations">
      <MemberSignature Language="C#" Value="public void ResetSlotConfigurations ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void ResetSlotConfigurations() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ResetSlotConfigurations" />
      <MemberSignature Language="VB.NET" Value="Public Sub ResetSlotConfigurations ()" />
      <MemberSignature Language="F#" Value="abstract member ResetSlotConfigurations : unit -&gt; unit" Usage="iWebAppBase.ResetSlotConfigurations " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66e82-152">Der Slot auf seiner ursprünglichen Konfigurationen zurückgesetzt.</span><span class="sxs-lookup"><span data-stu-id="66e82-152">Reset the slot to its original configurations.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ResetSlotConfigurationsAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ResetSlotConfigurationsAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ResetSlotConfigurationsAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ResetSlotConfigurationsAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ResetSlotConfigurationsAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.ResetSlotConfigurationsAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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
            <span data-ttu-id="66e82-153">Der Slot auf seiner ursprünglichen Konfigurationen zurückgesetzt.</span><span class="sxs-lookup"><span data-stu-id="66e82-153">Reset the slot to its original configurations.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-154">Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="66e82-154">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public void Restart ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Restart() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Restart" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restart ()" />
      <MemberSignature Language="F#" Value="abstract member Restart : unit -&gt; unit" Usage="iWebAppBase.Restart " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66e82-155">Neustart der Web-app oder Bereitstellung-Slot.</span><span class="sxs-lookup"><span data-stu-id="66e82-155">Restarts the web app or deployment slot.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.RestartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.RestartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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
            <span data-ttu-id="66e82-156">Neustart der Web-app oder Bereitstellung-Slot.</span><span class="sxs-lookup"><span data-stu-id="66e82-156">Restarts the web app or deployment slot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-157">Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="66e82-157">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="ScmSiteAlsoStopped">
      <MemberSignature Language="C#" Value="public bool ScmSiteAlsoStopped { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool ScmSiteAlsoStopped" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ScmSiteAlsoStopped" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ScmSiteAlsoStopped As Boolean" />
      <MemberSignature Language="F#" Value="member this.ScmSiteAlsoStopped : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.ScmSiteAlsoStopped" />
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
            <span data-ttu-id="66e82-158">Ruft ab, ob SCM (KUDU) Site beendet werden soll, wenn die Web-app beendet wird.</span><span class="sxs-lookup"><span data-stu-id="66e82-158">Gets whether to stop SCM (KUDU) site when the web app is stopped.</span></span> <span data-ttu-id="66e82-159">Die Standardeinstellung ist "false".</span><span class="sxs-lookup"><span data-stu-id="66e82-159">Default is false.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Start() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Start" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start ()" />
      <MemberSignature Language="F#" Value="abstract member Start : unit -&gt; unit" Usage="iWebAppBase.Start " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66e82-160">Startet die Web-app oder Bereitstellung-Slot.</span><span class="sxs-lookup"><span data-stu-id="66e82-160">Starts the web app or deployment slot.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.StartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.StartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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
            <span data-ttu-id="66e82-161">Startet die Web-app oder Bereitstellung-Slot.</span><span class="sxs-lookup"><span data-stu-id="66e82-161">Starts the web app or deployment slot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-162">Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="66e82-162">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="State">
      <MemberSignature Language="C#" Value="public string State { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string State" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.State" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property State As String" />
      <MemberSignature Language="F#" Value="member this.State : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.State" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-163">Ruft den Status der Web-app.</span><span class="sxs-lookup"><span data-stu-id="66e82-163">Gets state of the web app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Stop">
      <MemberSignature Language="C#" Value="public void Stop ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Stop() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Stop" />
      <MemberSignature Language="VB.NET" Value="Public Sub Stop ()" />
      <MemberSignature Language="F#" Value="abstract member Stop : unit -&gt; unit" Usage="iWebAppBase.Stop " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="66e82-164">Beendet die Web-app oder Bereitstellung-Slot.</span><span class="sxs-lookup"><span data-stu-id="66e82-164">Stops the web app or deployment slot.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StopAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StopAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StopAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.StopAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StopAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.StopAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
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
            <span data-ttu-id="66e82-165">Beendet die Web-app oder Bereitstellung-Slot.</span><span class="sxs-lookup"><span data-stu-id="66e82-165">Stops the web app or deployment slot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-166">Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="66e82-166">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="Swap">
      <MemberSignature Language="C#" Value="public void Swap (string slotName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Swap(string slotName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.Swap(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub Swap (slotName As String)" />
      <MemberSignature Language="F#" Value="abstract member Swap : string -&gt; unit" Usage="iWebAppBase.Swap slotName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="slotName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="slotName">
            <span data-ttu-id="66e82-167">der zielslot für den Tauschvorgang.</span><span class="sxs-lookup"><span data-stu-id="66e82-167">The target slot to swap with.</span></span> <span data-ttu-id="66e82-168">Verwenden Sie "Produktion" für den produktionsslot zu übergeben.</span><span class="sxs-lookup"><span data-stu-id="66e82-168">Use 'production' for the production slot.</span></span>
            </param>
        <summary>
            <span data-ttu-id="66e82-169">Vertauscht die app, die in der aktuellen web-app / slot mit der app, die im angegebenen Slot ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="66e82-169">Swaps the app running in the current web app / slot with the app running in the specified slot.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SwapAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task SwapAsync (string slotName, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task SwapAsync(string slotName, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.SwapAsync(System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member SwapAsync : string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.SwapAsync (slotName, cancellationToken)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="slotName" Type="System.String" />
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="slotName">
            <span data-ttu-id="66e82-170">der zielslot für den Tauschvorgang.</span><span class="sxs-lookup"><span data-stu-id="66e82-170">The target slot to swap with.</span></span> <span data-ttu-id="66e82-171">Verwenden Sie "Produktion" für den produktionsslot zu übergeben.</span><span class="sxs-lookup"><span data-stu-id="66e82-171">Use 'production' for the production slot.</span></span>
            </param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="66e82-172">Vertauscht die app, die in der aktuellen web-app / slot mit der app, die im angegebenen Slot ausgeführt.</span><span class="sxs-lookup"><span data-stu-id="66e82-172">Swaps the app running in the current web app / slot with the app running in the specified slot.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-173">Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="66e82-173">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="TargetSwapSlot">
      <MemberSignature Language="C#" Value="public string TargetSwapSlot { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string TargetSwapSlot" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.TargetSwapSlot" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TargetSwapSlot As String" />
      <MemberSignature Language="F#" Value="member this.TargetSwapSlot : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.TargetSwapSlot" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-174">Ruft ab, welchen Slot in diese app auslagern.</span><span class="sxs-lookup"><span data-stu-id="66e82-174">Gets which slot this app will swap into.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="TrafficManagerHostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.ISet&lt;string&gt; TrafficManagerHostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.ISet`1&lt;string&gt; TrafficManagerHostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.TrafficManagerHostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property TrafficManagerHostNames As ISet(Of String)" />
      <MemberSignature Language="F#" Value="member this.TrafficManagerHostNames : System.Collections.Generic.ISet&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.TrafficManagerHostNames" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.ISet&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-175">Ruft die Liste von Azure Traffic Manager-Hostnamen WebApp zugeordnet haben.</span><span class="sxs-lookup"><span data-stu-id="66e82-175">Gets list of Azure Traffic manager host names associated with web app.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UsageState">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.UsageState UsageState { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.Models.UsageState UsageState" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.UsageState" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UsageState As UsageState" />
      <MemberSignature Language="F#" Value="member this.UsageState : Microsoft.Azure.Management.AppService.Fluent.Models.UsageState" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.UsageState" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.UsageState</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="66e82-176">Ruft ab, Status, der angibt, ob die Web-app die quotenauslastung überschritten hat.</span><span class="sxs-lookup"><span data-stu-id="66e82-176">Gets state indicating whether web app has exceeded its quota usage.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnership">
      <MemberSignature Language="C#" Value="public void VerifyDomainOwnership (string certificateOrderName, string domainVerificationToken);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void VerifyDomainOwnership(string certificateOrderName, string domainVerificationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.VerifyDomainOwnership(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Sub VerifyDomainOwnership (certificateOrderName As String, domainVerificationToken As String)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnership : string * string -&gt; unit" Usage="iWebAppBase.VerifyDomainOwnership (certificateOrderName, domainVerificationToken)" />
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
        <param name="certificateOrderName"><span data-ttu-id="66e82-177">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="66e82-177">The name of the certificate order.</span></span></param>
        <param name="domainVerificationToken"><span data-ttu-id="66e82-178">Die Domäne Überprüfung-Token für die Zertifikat-Bestellung.</span><span class="sxs-lookup"><span data-stu-id="66e82-178">The domain verification token for the certificate order.</span></span></param>
        <summary>
            <span data-ttu-id="66e82-179">Stellt sicher, dass der Besitz der Domäne für eine Bestellung Zertifikat, indem Sie einen Hostnamen, der Domäne überprüfen diese Web-app gebunden ist.</span><span class="sxs-lookup"><span data-stu-id="66e82-179">Verifies the ownership of the domain for a certificate order by verifying a hostname of the domain is bound to this web app.</span></span>
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VerifyDomainOwnershipAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task VerifyDomainOwnershipAsync (string certificateOrderName, string domainVerificationToken, System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task VerifyDomainOwnershipAsync(string certificateOrderName, string domainVerificationToken, valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.VerifyDomainOwnershipAsync(System.String,System.String,System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member VerifyDomainOwnershipAsync : string * string * System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iWebAppBase.VerifyDomainOwnershipAsync (certificateOrderName, domainVerificationToken, cancellationToken)" />
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
        <param name="certificateOrderName"><span data-ttu-id="66e82-180">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="66e82-180">The name of the certificate order.</span></span></param>
        <param name="domainVerificationToken"><span data-ttu-id="66e82-181">Die Domäne Überprüfung-Token für die Zertifikat-Bestellung.</span><span class="sxs-lookup"><span data-stu-id="66e82-181">The domain verification token for the certificate order.</span></span></param>
        <param name="cancellationToken">To be added.</param>
        <summary>
            <span data-ttu-id="66e82-182">Stellt sicher, dass der Besitz der Domäne für eine Bestellung Zertifikat, indem Sie einen Hostnamen, der Domäne überprüfen diese Web-app gebunden ist.</span><span class="sxs-lookup"><span data-stu-id="66e82-182">Verifies the ownership of the domain for a certificate order by verifying a hostname of the domain is bound to this web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="66e82-183">Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</span><span class="sxs-lookup"><span data-stu-id="66e82-183">A representation of the deferred computation of this call.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WebSocketsEnabled">
      <MemberSignature Language="C#" Value="public bool WebSocketsEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool WebSocketsEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.WebSocketsEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property WebSocketsEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.WebSocketsEnabled : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IWebAppBase.WebSocketsEnabled" />
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
            <span data-ttu-id="66e82-184">Ruft ab, wenn die WebSocket aktiviert ist.</span><span class="sxs-lookup"><span data-stu-id="66e82-184">Gets if web socket is enabled.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>