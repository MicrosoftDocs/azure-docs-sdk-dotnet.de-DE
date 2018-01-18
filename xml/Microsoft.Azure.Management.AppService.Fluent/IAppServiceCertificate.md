<Type Name="IAppServiceCertificate" FullName="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate">
  <TypeSignature Language="C#" Value="public interface IAppServiceCertificate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IAppServiceCertificate implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager, class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IAppServiceCertificate&#xA;Implements IBeta, IGroupableResource(Of IAppServiceManager, CertificateInner), IHasInner(Of CertificateInner), IHasManager(Of IAppServiceManager), IRefreshable(Of IAppServiceCertificate)" />
  <TypeSignature Language="F#" Value="type IAppServiceCertificate = interface&#xA;    interface IBeta&#xA;    interface IGroupableResource&lt;IAppServiceManager, CertificateInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IAppServiceManager&gt;&#xA;    interface IHasInner&lt;CertificateInner&gt;&#xA;    interface IRefreshable&lt;IAppServiceCertificate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager,Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.AppService.Fluent.Models.CertificateInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="e17b1-101">Eine unveränderliche clientseitige Darstellung eines Azure app Service-Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="e17b1-101">An immutable client-side representation of an Azure app service certificate.</span></span>
            </summary>
    <remarks>
            <span data-ttu-id="e17b1-102">(Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).</span><span class="sxs-lookup"><span data-stu-id="e17b1-102">(Beta: This functionality is in preview and as such is subject to change in non-backwards compatible ways in future releases, including removal, regardless of any compatibility expectations set by the containing library version number.).</span></span>
            </remarks>
  </Docs>
  <Members>
    <Member MemberName="CertificateBlob">
      <MemberSignature Language="C#" Value="public string CertificateBlob { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string CertificateBlob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.CertificateBlob" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property CertificateBlob As String" />
      <MemberSignature Language="F#" Value="member this.CertificateBlob : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.CertificateBlob" />
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
            <span data-ttu-id="e17b1-103">Ruft ab, das die Rohdatenbytes, die der CER-Datei.</span><span class="sxs-lookup"><span data-stu-id="e17b1-103">Gets the raw bytes of .cer file.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ExpirationDate">
      <MemberSignature Language="C#" Value="public DateTime ExpirationDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime ExpirationDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.ExpirationDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ExpirationDate As DateTime" />
      <MemberSignature Language="F#" Value="member this.ExpirationDate : DateTime" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.ExpirationDate" />
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
            <span data-ttu-id="e17b1-104">Ruft das Datum des Zertifikats Expriration ab.</span><span class="sxs-lookup"><span data-stu-id="e17b1-104">Gets the certificate expriration date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="FriendlyName">
      <MemberSignature Language="C#" Value="public string FriendlyName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string FriendlyName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.FriendlyName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property FriendlyName As String" />
      <MemberSignature Language="F#" Value="member this.FriendlyName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.FriendlyName" />
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
            <span data-ttu-id="e17b1-105">Ruft den Anzeigenamen des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="e17b1-105">Gets the friendly name of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostingEnvironmentProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile HostingEnvironmentProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile HostingEnvironmentProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.HostingEnvironmentProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostingEnvironmentProfile As HostingEnvironmentProfile" />
      <MemberSignature Language="F#" Value="member this.HostingEnvironmentProfile : Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.HostingEnvironmentProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.Models.HostingEnvironmentProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e17b1-106">Ruft die Spezifikation für die App Service-Umgebung für das Zertifikat zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="e17b1-106">Gets the specification for the App Service Environment to use for the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="HostNames">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; HostNames { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; HostNames" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.HostNames" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property HostNames As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.HostNames : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.HostNames" />
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
            <span data-ttu-id="e17b1-107">Ruft den Hostnamen, denen das Zertifikat gilt, ab.</span><span class="sxs-lookup"><span data-stu-id="e17b1-107">Gets the host names the certificate applies to.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IssueDate">
      <MemberSignature Language="C#" Value="public DateTime IssueDate { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype System.DateTime IssueDate" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.IssueDate" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IssueDate As DateTime" />
      <MemberSignature Language="F#" Value="member this.IssueDate : DateTime" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.IssueDate" />
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
            <span data-ttu-id="e17b1-108">Ruft das Zertifikatsproblem Datum ab.</span><span class="sxs-lookup"><span data-stu-id="e17b1-108">Gets the certificate issue Date.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Issuer">
      <MemberSignature Language="C#" Value="public string Issuer { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Issuer" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.Issuer" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Issuer As String" />
      <MemberSignature Language="F#" Value="member this.Issuer : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.Issuer" />
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
            <span data-ttu-id="e17b1-109">Ruft den Aussteller des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="e17b1-109">Gets the certificate issuer.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Password">
      <MemberSignature Language="C#" Value="public string Password { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Password" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.Password" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Password As String" />
      <MemberSignature Language="F#" Value="member this.Password : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.Password" />
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
            <span data-ttu-id="e17b1-110">Ruft das Kennwort des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="e17b1-110">Gets the certificate password.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PfxBlob">
      <MemberSignature Language="C#" Value="public byte[] PfxBlob { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance unsigned int8[] PfxBlob" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.PfxBlob" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PfxBlob As Byte()" />
      <MemberSignature Language="F#" Value="member this.PfxBlob : byte[]" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.PfxBlob" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Byte[]</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            <span data-ttu-id="e17b1-111">Ruft das Pfx-Blob ab.</span><span class="sxs-lookup"><span data-stu-id="e17b1-111">Gets the pfx blob.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PublicKeyHash">
      <MemberSignature Language="C#" Value="public string PublicKeyHash { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string PublicKeyHash" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.PublicKeyHash" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PublicKeyHash As String" />
      <MemberSignature Language="F#" Value="member this.PublicKeyHash : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.PublicKeyHash" />
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
            <span data-ttu-id="e17b1-112">Ruft den Hash für öffentliche Schlüssel ab.</span><span class="sxs-lookup"><span data-stu-id="e17b1-112">Gets the public key hash.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SelfLink">
      <MemberSignature Language="C#" Value="public string SelfLink { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SelfLink" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.SelfLink" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SelfLink As String" />
      <MemberSignature Language="F#" Value="member this.SelfLink : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.SelfLink" />
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
            <span data-ttu-id="e17b1-113">Ruft ab, der Self-Link.</span><span class="sxs-lookup"><span data-stu-id="e17b1-113">Gets the self link.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SiteName">
      <MemberSignature Language="C#" Value="public string SiteName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SiteName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.SiteName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SiteName As String" />
      <MemberSignature Language="F#" Value="member this.SiteName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.SiteName" />
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
            <span data-ttu-id="e17b1-114">Ruft den Namen der app.</span><span class="sxs-lookup"><span data-stu-id="e17b1-114">Gets the app name.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="SubjectName">
      <MemberSignature Language="C#" Value="public string SubjectName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string SubjectName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.SubjectName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property SubjectName As String" />
      <MemberSignature Language="F#" Value="member this.SubjectName : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.SubjectName" />
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
            <span data-ttu-id="e17b1-115">Ruft den Antragstellernamen des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="e17b1-115">Gets the subject name of the certificate.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Thumbprint">
      <MemberSignature Language="C#" Value="public string Thumbprint { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string Thumbprint" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.Thumbprint" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Thumbprint As String" />
      <MemberSignature Language="F#" Value="member this.Thumbprint : string" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.Thumbprint" />
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
            <span data-ttu-id="e17b1-116">Ruft den Fingerabdruck des Zertifikats ab.</span><span class="sxs-lookup"><span data-stu-id="e17b1-116">Gets the certificate thumbprint.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Valid">
      <MemberSignature Language="C#" Value="public bool Valid { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool Valid" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.Valid" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Valid As Boolean" />
      <MemberSignature Language="F#" Value="member this.Valid : bool" Usage="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificate.Valid" />
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
            <span data-ttu-id="e17b1-117">Ruft ab, wenn das Zertifikat ungültig.</span><span class="sxs-lookup"><span data-stu-id="e17b1-117">Gets if the certificate valid.</span></span>
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>