<Type Name="IPublishingProfile" FullName="Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile">
  <TypeSignature Language="C#" Value="public interface IPublishingProfile : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IPublishingProfile implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile" />
  <TypeSignature Language="VB.NET" Value="Public Interface IPublishingProfile&#xA;Implements IBeta" />
  <TypeSignature Language="F#" Value="type IPublishingProfile = interface&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="abd86-101">Endpunkte und Anmeldeinformationen für die Veröffentlichung in einer Web-app.</span><span class="sxs-lookup"><span data-stu-id="abd86-101">Endpoints and credentials for publishing to a web app.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="abd86-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="abd86-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="FtpPassword">
      <MemberSignature Language="C#" Value="public string FtpPassword { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FtpPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.FtpPassword" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FtpPassword As String" />
      <MemberSignature Language="F#" Value="member this.FtpPassword : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.FtpPassword" />
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
            <span data-ttu-id="abd86-103">Ruft das für FTP-Publishing verwendete Kennwort ab.</span><span class="sxs-lookup"><span data-stu-id="abd86-103">Gets the password used for FTP publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FtpUrl">
      <MemberSignature Language="C#" Value="public string FtpUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FtpUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.FtpUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FtpUrl As String" />
      <MemberSignature Language="F#" Value="member this.FtpUrl : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.FtpUrl" />
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
            <span data-ttu-id="abd86-104">Ruft die Url für die FTP-Veröffentlichung mit ftp: / / und den Stammordner.</span><span class="sxs-lookup"><span data-stu-id="abd86-104">Gets the url for FTP publishing, with ftp:// and the root folder.</span></span>
            <span data-ttu-id="abd86-105">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="abd86-105">E.g.</span></span> <span data-ttu-id="abd86-106">FTP://FTP.contoso.com/Site/wwwroot.</span><span class="sxs-lookup"><span data-stu-id="abd86-106">ftp://ftp.contoso.com/site/wwwroot.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FtpUsername">
      <MemberSignature Language="C#" Value="public string FtpUsername { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FtpUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.FtpUsername" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FtpUsername As String" />
      <MemberSignature Language="F#" Value="member this.FtpUsername : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.FtpUsername" />
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
            <span data-ttu-id="abd86-107">Ruft den Benutzernamen für die FTP-Publishing verwendet.</span><span class="sxs-lookup"><span data-stu-id="abd86-107">Gets the username used for FTP publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GitPassword">
      <MemberSignature Language="C#" Value="public string GitPassword { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GitPassword" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.GitPassword" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GitPassword As String" />
      <MemberSignature Language="F#" Value="member this.GitPassword : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.GitPassword" />
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
            <span data-ttu-id="abd86-108">Ruft das Kennwort für Git-Veröffentlichung ab.</span><span class="sxs-lookup"><span data-stu-id="abd86-108">Gets the password used for Git publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GitUrl">
      <MemberSignature Language="C#" Value="public string GitUrl { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GitUrl" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.GitUrl" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GitUrl As String" />
      <MemberSignature Language="F#" Value="member this.GitUrl : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.GitUrl" />
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
            <span data-ttu-id="abd86-109">Ruft die Url für die FTP-Veröffentlichung mit https:// im Vorfeld ab.</span><span class="sxs-lookup"><span data-stu-id="abd86-109">Gets the url for FTP publishing, with https:// upfront.</span></span>
            <span data-ttu-id="abd86-110">Beispiel:</span><span class="sxs-lookup"><span data-stu-id="abd86-110">E.g.</span></span> <span data-ttu-id="abd86-111">Https://contoso.com:443/myRepo.Git.</span><span class="sxs-lookup"><span data-stu-id="abd86-111">https://contoso.com:443/myRepo.git.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GitUsername">
      <MemberSignature Language="C#" Value="public string GitUsername { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string GitUsername" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.GitUsername" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property GitUsername As String" />
      <MemberSignature Language="F#" Value="member this.GitUsername : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IPublishingProfile.GitUsername" />
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
            <span data-ttu-id="abd86-112">Ruft den Benutzernamen für Git-Veröffentlichung verwendet.</span><span class="sxs-lookup"><span data-stu-id="abd86-112">Gets the username used for Git publishing.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>