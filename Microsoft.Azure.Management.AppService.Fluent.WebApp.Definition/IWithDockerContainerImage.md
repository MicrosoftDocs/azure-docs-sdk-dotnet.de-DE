<Type Name="IWithDockerContainerImage" FullName="Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithDockerContainerImage">
  <TypeSignature Language="C#" Value="public interface IWithDockerContainerImage" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDockerContainerImage" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithDockerContainerImage" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDockerContainerImage" />
  <TypeSignature Language="F#" Value="type IWithDockerContainerImage = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Definition einer Web-app ermöglicht Docker Bildquelle angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithBuiltInImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithBuiltInImage (Microsoft.Azure.Management.AppService.Fluent.RuntimeStack runtimeStack);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate WithBuiltInImage(class Microsoft.Azure.Management.AppService.Fluent.RuntimeStack runtimeStack) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithDockerContainerImage.WithBuiltInImage(Microsoft.Azure.Management.AppService.Fluent.RuntimeStack)" />
      <MemberSignature Language="F#" Value="abstract member WithBuiltInImage : Microsoft.Azure.Management.AppService.Fluent.RuntimeStack -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate" Usage="iWithDockerContainerImage.WithBuiltInImage runtimeStack" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="runtimeStack" Type="Microsoft.Azure.Management.AppService.Fluent.RuntimeStack" />
      </Parameters>
      <Docs>
        <param name="runtimeStack">Die Common Language Runtime-Stapel, die auf das Abbild installiert.</param>
        <summary>
            Gibt an, die Docker Container-Image in einem integriert werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateDockerHubImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials WithPrivateDockerHubImage (string imageAndTag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials WithPrivateDockerHubImage(string imageAndTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithDockerContainerImage.WithPrivateDockerHubImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateDockerHubImage (imageAndTag As String) As IWithCredentials" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateDockerHubImage : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials" Usage="iWithDockerContainerImage.WithPrivateDockerHubImage imageAndTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageAndTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageAndTag">Bild- und ein optionales Tag (z. B. ": Bildtag').</param>
        <summary>
            Gibt an, die Docker Container-Image, um eine von Docker Hub sein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPrivateRegistryImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials WithPrivateRegistryImage (string imageAndTag, string serverUrl);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials WithPrivateRegistryImage(string imageAndTag, string serverUrl) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithDockerContainerImage.WithPrivateRegistryImage(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrivateRegistryImage (imageAndTag As String, serverUrl As String) As IWithCredentials" />
      <MemberSignature Language="F#" Value="abstract member WithPrivateRegistryImage : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials" Usage="iWithDockerContainerImage.WithPrivateRegistryImage (imageAndTag, serverUrl)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithCredentials</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageAndTag" Type="System.String" />
        <Parameter Name="serverUrl" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageAndTag">Bild- und ein optionales Tag (z. B. ": Bildtag').</param>
        <param name="serverUrl">Die URL mit dem privaten Registrierungsserver.</param>
        <summary>
            Gibt an, die Docker Container-Abbild um eine aus einem privaten Registrierung sein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPublicDockerHubImage">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand WithPublicDockerHubImage (string imageAndTag);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand WithPublicDockerHubImage(string imageAndTag) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithDockerContainerImage.WithPublicDockerHubImage(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPublicDockerHubImage (imageAndTag As String) As IWithStartUpCommand" />
      <MemberSignature Language="F#" Value="abstract member WithPublicDockerHubImage : string -&gt; Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand" Usage="iWithDockerContainerImage.WithPublicDockerHubImage imageAndTag" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.WebApp.Definition.IWithStartUpCommand</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="imageAndTag" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="imageAndTag">Bild- und ein optionales Tag (z. B. ": Bildtag').</param>
        <summary>
            Gibt an, die Docker Container-Image, um eine von Docker Hub sein.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>