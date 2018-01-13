<Type Name="IAppServicePlan" FullName="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan">
  <TypeSignature Language="C#" Value="public interface IAppServicePlan : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Update.IUpdate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServicePlan implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Update.IUpdate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServicePlan&#xA;Implements IBeta, IGroupableResource(Of IAppServiceManager, AppServicePlanInner), IHasInner(Of AppServicePlanInner), IHasManager(Of IAppServiceManager), IRefreshable(Of IAppServicePlan), IUpdatable(Of IUpdate)" />
  <TypeSignature Language="F#" Value="type IAppServicePlan = interface&#xA;    interface IBeta&#xA;    interface IGroupableResource&lt;IAppServiceManager, AppServicePlanInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasInner&lt;AppServicePlanInner&gt;&#xA;    interface IRefreshable&lt;IAppServicePlan&gt;&#xA;    interface IUpdatable&lt;IUpdate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.AppServicePlanInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Update.IUpdate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="c5f3f-101">Eine unveränderliche clientseitige Darstellung ein Azure App Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="c5f3f-101">An immutable client-side representation of an Azure App service plan.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="c5f3f-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="c5f3f-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public int Capacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capacity As Integer" />
      <MemberSignature Language="F#" Value="member this.Capacity : int" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.Capacity" />
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
            <span data-ttu-id="c5f3f-103">Ruft die maximale Anzahl von Instanzen, die zugewiesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="c5f3f-103">Gets maximum number of instances that can be assigned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="MaxInstances">
      <MemberSignature Language="C#" Value="public int MaxInstances { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 MaxInstances" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.MaxInstances" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property MaxInstances As Integer" />
      <MemberSignature Language="F#" Value="member this.MaxInstances : int" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.MaxInstances" />
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
            <span data-ttu-id="c5f3f-104">Ruft die maximale Anzahl von Instanzen, die zugewiesen werden kann.</span><span class="sxs-lookup"><span data-stu-id="c5f3f-104">Gets maximum number of instances that can be assigned.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="NumberOfWebApps">
      <MemberSignature Language="C#" Value="public int NumberOfWebApps { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 NumberOfWebApps" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.NumberOfWebApps" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NumberOfWebApps As Integer" />
      <MemberSignature Language="F#" Value="member this.NumberOfWebApps : int" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.NumberOfWebApps" />
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
            <span data-ttu-id="c5f3f-105">Ruft die Anzahl der Web-apps diese App Service-Plan zugewiesen.</span><span class="sxs-lookup"><span data-stu-id="c5f3f-105">Gets number of web apps assigned to this App Service Plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OperatingSystem">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.OperatingSystem OperatingSystem { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.AppService.Fluent.OperatingSystem OperatingSystem" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.OperatingSystem" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OperatingSystem As OperatingSystem" />
      <MemberSignature Language="F#" Value="member this.OperatingSystem : Microsoft.Azure.Management.AppService.Fluent.OperatingSystem" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.OperatingSystem" />
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
            <span data-ttu-id="c5f3f-106">Ruft das Betriebssystem, auf das die Web-app ausgeführt wird.</span><span class="sxs-lookup"><span data-stu-id="c5f3f-106">Gets the operating system the web app is running on.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PerSiteScaling">
      <MemberSignature Language="C#" Value="public bool PerSiteScaling { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool PerSiteScaling" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.PerSiteScaling" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PerSiteScaling As Boolean" />
      <MemberSignature Language="F#" Value="member this.PerSiteScaling : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.PerSiteScaling" />
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
            <span data-ttu-id="c5f3f-107">Ruft ab, wenn apps diese App Service-Plan zugewiesen unabhängig skaliert werden können.</span><span class="sxs-lookup"><span data-stu-id="c5f3f-107">Gets if apps assigned to this App Service Plan can be scaled independently.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PricingTier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.PricingTier PricingTier { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.PricingTier PricingTier" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.PricingTier" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PricingTier As PricingTier" />
      <MemberSignature Language="F#" Value="member this.PricingTier : Microsoft.Azure.Management.AppService.Fluent.PricingTier" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan.PricingTier" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.PricingTier</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="c5f3f-108">Ruft die Ebene Preisinformationen des App Service-Plan ab.</span><span class="sxs-lookup"><span data-stu-id="c5f3f-108">Gets the pricing tier information of the App Service Plan.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>