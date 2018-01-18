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
            <span data-ttu-id="85593-101">Die Definition einer Web-app ermöglicht Docker Bildquelle angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="85593-101">A web app definition allowing docker image source to be specified.</span></span>
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
        <param name="runtimeStack"><span data-ttu-id="85593-102">Die Common Language Runtime-Stapel, die auf das Abbild installiert.</span><span class="sxs-lookup"><span data-stu-id="85593-102">The runtime stack installed on the image.</span></span></param>
        <summary>
            <span data-ttu-id="85593-103">Gibt an, die Docker Container-Image in einem integriert werden.</span><span class="sxs-lookup"><span data-stu-id="85593-103">Specifies the docker container image to be a built in one.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="85593-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="85593-104">The next stage of the definition.</span></span></return>
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
        <param name="imageAndTag"><span data-ttu-id="85593-105">Bild- und ein optionales Tag (z. B. ": Bildtag').</span><span class="sxs-lookup"><span data-stu-id="85593-105">Image and optional tag (eg 'image:tag').</span></span></param>
        <summary>
            <span data-ttu-id="85593-106">Gibt an, die Docker Container-Image, um eine von Docker Hub sein.</span><span class="sxs-lookup"><span data-stu-id="85593-106">Specifies the docker container image to be one from Docker Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="85593-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="85593-107">The next stage of the definition.</span></span></return>
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
        <param name="imageAndTag"><span data-ttu-id="85593-108">Bild- und ein optionales Tag (z. B. ": Bildtag').</span><span class="sxs-lookup"><span data-stu-id="85593-108">Image and optional tag (eg 'image:tag').</span></span></param>
        <param name="serverUrl"><span data-ttu-id="85593-109">Die URL mit dem privaten Registrierungsserver.</span><span class="sxs-lookup"><span data-stu-id="85593-109">The URL to the private registry server.</span></span></param>
        <summary>
            <span data-ttu-id="85593-110">Gibt an, die Docker Container-Abbild um eine aus einem privaten Registrierung sein.</span><span class="sxs-lookup"><span data-stu-id="85593-110">Specifies the docker container image to be one from a private registry.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="85593-111">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="85593-111">The next stage of the definition.</span></span></return>
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
        <param name="imageAndTag"><span data-ttu-id="85593-112">Bild- und ein optionales Tag (z. B. ": Bildtag').</span><span class="sxs-lookup"><span data-stu-id="85593-112">Image and optional tag (eg 'image:tag').</span></span></param>
        <summary>
            <span data-ttu-id="85593-113">Gibt an, die Docker Container-Image, um eine von Docker Hub sein.</span><span class="sxs-lookup"><span data-stu-id="85593-113">Specifies the docker container image to be one from Docker Hub.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="85593-114">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="85593-114">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>