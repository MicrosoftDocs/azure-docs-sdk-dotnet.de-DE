<Type Name="IBlank" FullName="Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IBlank">
  <TypeSignature Language="C#" Value="public interface IBlank : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.INewAppServicePlanWithGroup&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IBlank implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion`1&lt;class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.INewAppServicePlanWithGroup&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IBlank" />
  <TypeSignature Language="VB.NET" Value="Public Interface IBlank&#xA;Implements IDefinitionWithRegion(Of INewAppServicePlanWithGroup)" />
  <TypeSignature Language="F#" Value="type IBlank = interface&#xA;    interface IDefinitionWithRegion&lt;INewAppServicePlanWithGroup&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithRegion&lt;Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.INewAppServicePlanWithGroup&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="d0740-101">Die erste Phase der Definition des Web-app.</span><span class="sxs-lookup"><span data-stu-id="d0740-101">The first stage of the web app definition.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingLinuxPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingLinuxPlanWithGroup WithExistingLinuxPlan (Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingLinuxPlanWithGroup WithExistingLinuxPlan(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IBlank.WithExistingLinuxPlan(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingLinuxPlan (appServicePlan As IAppServicePlan) As IExistingLinuxPlanWithGroup" />
      <MemberSignature Language="F#" Value="abstract member WithExistingLinuxPlan : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingLinuxPlanWithGroup" Usage="iBlank.WithExistingLinuxPlan appServicePlan" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingLinuxPlanWithGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan" />
      </Parameters>
      <Docs>
        <param name="appServicePlan"><span data-ttu-id="d0740-102">Die vorhandenen app Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="d0740-102">The existing app service plan.</span></span></param>
        <summary>
            <span data-ttu-id="d0740-103">Verwendet einen vorhandenen app Service-Plan für die Web-app.</span><span class="sxs-lookup"><span data-stu-id="d0740-103">Uses an existing app service plan for the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d0740-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="d0740-104">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithExistingWindowsPlan">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup WithExistingWindowsPlan (Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan appServicePlan);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup WithExistingWindowsPlan(class Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan appServicePlan) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IBlank.WithExistingWindowsPlan(Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingWindowsPlan (appServicePlan As IAppServicePlan) As IExistingWindowsPlanWithGroup" />
      <MemberSignature Language="F#" Value="abstract member WithExistingWindowsPlan : Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup" Usage="iBlank.WithExistingWindowsPlan appServicePlan" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IExistingWindowsPlanWithGroup</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="appServicePlan" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServicePlan" />
      </Parameters>
      <Docs>
        <param name="appServicePlan"><span data-ttu-id="d0740-105">Die vorhandenen app Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="d0740-105">The existing app service plan.</span></span></param>
        <summary>
            <span data-ttu-id="d0740-106">Verwendet einen vorhandenen app Service-Plan für die Web-app.</span><span class="sxs-lookup"><span data-stu-id="d0740-106">Uses an existing app service plan for the web app.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="d0740-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="d0740-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>