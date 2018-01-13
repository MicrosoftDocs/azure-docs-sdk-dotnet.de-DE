<Type Name="IWithPricingTier" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPricingTier">
  <TypeSignature Language="C#" Value="public interface IWithPricingTier" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPricingTier" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPricingTier" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPricingTier" />
  <TypeSignature Language="F#" Value="type IWithPricingTier = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="3f302-101">Eine app Plan Dienstdefinition ermöglicht Tarif festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="3f302-101">An app service plan definition allowing pricing tier to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFreePricingTier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate WithFreePricingTier ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate WithFreePricingTier() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPricingTier.WithFreePricingTier" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFreePricingTier () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithFreePricingTier : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate" Usage="iWithPricingTier.WithFreePricingTier " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3f302-102">Gibt die kostenlose Preisstufe für die app Service-Plan an.</span><span class="sxs-lookup"><span data-stu-id="3f302-102">Specifies free pricing tier for the app service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3f302-103">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="3f302-103">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPricingTier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithOperatingSystem WithPricingTier (Microsoft.Azure.Management.AppService.Fluent.PricingTier pricingTier);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithOperatingSystem WithPricingTier(class Microsoft.Azure.Management.AppService.Fluent.PricingTier pricingTier) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPricingTier.WithPricingTier(Microsoft.Azure.Management.AppService.Fluent.PricingTier)" />
      <MemberSignature Language="F#" Value="abstract member WithPricingTier : Microsoft.Azure.Management.AppService.Fluent.PricingTier -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithOperatingSystem" Usage="iWithPricingTier.WithPricingTier pricingTier" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithOperatingSystem</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pricingTier" Type="Microsoft.Azure.Management.AppService.Fluent.PricingTier" />
      </Parameters>
      <Docs>
        <param name="pricingTier"><span data-ttu-id="3f302-104">Die Preisstufe Ebene-Enumeration.</span><span class="sxs-lookup"><span data-stu-id="3f302-104">The pricing tier enum.</span></span></param>
        <summary>
            <span data-ttu-id="3f302-105">Gibt an, der Tarif für die app Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="3f302-105">Specifies the pricing tier for the app service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3f302-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="3f302-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSharedPricingTier">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate WithSharedPricingTier ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate WithSharedPricingTier() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithPricingTier.WithSharedPricingTier" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSharedPricingTier () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSharedPricingTier : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate" Usage="iWithPricingTier.WithSharedPricingTier " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServicePlan.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            <span data-ttu-id="3f302-107">Gibt an, freigegebenen Tarif für die app Service-Plan.</span><span class="sxs-lookup"><span data-stu-id="3f302-107">Specifies shared pricing tier for the app service plan.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="3f302-108">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="3f302-108">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>