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
            Eine app Plan Dienstdefinition ermöglicht Tarif festgelegt werden.
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
            Gibt die kostenlose Preisstufe für die app Service-Plan an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
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
        <param name="pricingTier">Die Preisstufe Ebene-Enumeration.</param>
        <summary>
            Gibt an, der Tarif für die app Service-Plan.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
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
            Gibt an, freigegebenen Tarif für die app Service-Plan.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>