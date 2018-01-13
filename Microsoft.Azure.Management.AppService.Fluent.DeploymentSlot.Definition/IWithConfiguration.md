<Type Name="IWithConfiguration" FullName="Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration">
  <TypeSignature Language="C#" Value="public interface IWithConfiguration" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithConfiguration" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithConfiguration" />
  <TypeSignature Language="F#" Value="type IWithConfiguration = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Slot Bereitstellungsdefinition ermöglicht die Konfiguration von Klonen angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithBrandNewConfiguration">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithBrandNewConfiguration ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithBrandNewConfiguration() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration.WithBrandNewConfiguration" />
      <MemberSignature Language="VB.NET" Value="Public Function WithBrandNewConfiguration () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithBrandNewConfiguration : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate" Usage="iWithConfiguration.WithBrandNewConfiguration " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Den bereitstellungsslot erstellt mit brandneuen Standortkonfigurationen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithConfigurationFromDeploymentSlot">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromDeploymentSlot (Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot deploymentSlot);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromDeploymentSlot(class Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot deploymentSlot) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration.WithConfigurationFromDeploymentSlot(Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConfigurationFromDeploymentSlot (deploymentSlot As IDeploymentSlot) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithConfigurationFromDeploymentSlot : Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot -&gt; Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate" Usage="iWithConfiguration.WithConfigurationFromDeploymentSlot deploymentSlot" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="deploymentSlot" Type="Microsoft.Azure.Management.AppService.Fluent.IDeploymentSlot" />
      </Parameters>
      <Docs>
        <param name="deploymentSlot">Der bereitstellungsslot So kopieren Sie die Konfigurationen aus.</param>
        <summary>
            Die Standortkonfigurationen kopiert aus einer angegebenen bereitstellungsslot.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithConfigurationFromParent">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromParent ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromParent() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration.WithConfigurationFromParent" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConfigurationFromParent () As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithConfigurationFromParent : unit -&gt; Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate" Usage="iWithConfiguration.WithConfigurationFromParent " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Kopiert die Standortkonfigurationen aus der Web-app bereitstellungsslot angehört.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithConfigurationFromWebApp">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromWebApp (Microsoft.Azure.Management.AppService.Fluent.IWebApp webApp);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate WithConfigurationFromWebApp(class Microsoft.Azure.Management.AppService.Fluent.IWebApp webApp) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithConfiguration.WithConfigurationFromWebApp(Microsoft.Azure.Management.AppService.Fluent.IWebApp)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithConfigurationFromWebApp (webApp As IWebApp) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithConfigurationFromWebApp : Microsoft.Azure.Management.AppService.Fluent.IWebApp -&gt; Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate" Usage="iWithConfiguration.WithConfigurationFromWebApp webApp" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.DeploymentSlot.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="webApp" Type="Microsoft.Azure.Management.AppService.Fluent.IWebApp" />
      </Parameters>
      <Docs>
        <param name="webApp">So kopieren Sie die Konfigurationen von Web-app.</param>
        <summary>
            Kopiert die Standortkonfigurationen von einem bestimmten Web-app.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>