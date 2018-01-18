<Type Name="IWithCertificate&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithCertificate&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithCertificate&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCertificate`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithCertificate`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCertificate(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithCertificate&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="05c7b-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="05c7b-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="05c7b-102">Die Stufe der ein Hostname SSL Bindungsdefinition ermöglicht Zertifikatinformationen angegeben werden.</span><span class="sxs-lookup"><span data-stu-id="05c7b-102">The stage of a hostname SSL binding definition allowing certificate information to be specified.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingAppServiceCertificateOrder">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;ParentT&gt; WithExistingAppServiceCertificateOrder (Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder certificateOrder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType`1&lt;!ParentT&gt; WithExistingAppServiceCertificateOrder(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder certificateOrder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithCertificate`1.WithExistingAppServiceCertificateOrder(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingAppServiceCertificateOrder (certificateOrder As IAppServiceCertificateOrder) As IWithSslType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingAppServiceCertificateOrder : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;'ParentT&gt;" Usage="iWithCertificate.WithExistingAppServiceCertificateOrder certificateOrder" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrder" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder" />
      </Parameters>
      <Docs>
        <param name="certificateOrder"><span data-ttu-id="05c7b-103">Die zertifikatreihenfolge kann jetzt zu verwendende.</span><span class="sxs-lookup"><span data-stu-id="05c7b-103">The ready-to-use certificate order.</span></span></param>
        <summary>
            <span data-ttu-id="05c7b-104">Gibt eine Bestellung kann jetzt zu verwendende Zertifikat zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="05c7b-104">Specifies a ready-to-use certificate order to use.</span></span> <span data-ttu-id="05c7b-105">Dies ist in der Regel für die Wiederverwendung von Platzhalterzertifikate hilfreich.</span><span class="sxs-lookup"><span data-stu-id="05c7b-105">This is usually useful for reusing wildcard certificates.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="05c7b-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="05c7b-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewStandardSslCertificateOrder">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithKeyVault&lt;ParentT&gt; WithNewStandardSslCertificateOrder (string certificateOrderName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithKeyVault`1&lt;!ParentT&gt; WithNewStandardSslCertificateOrder(string certificateOrderName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithCertificate`1.WithNewStandardSslCertificateOrder(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewStandardSslCertificateOrder (certificateOrderName As String) As IWithKeyVault(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewStandardSslCertificateOrder : string -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithKeyVault&lt;'ParentT&gt;" Usage="iWithCertificate.WithNewStandardSslCertificateOrder certificateOrderName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithKeyVault&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrderName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="certificateOrderName"><span data-ttu-id="05c7b-107">Der Name des Auftrags Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="05c7b-107">The name of the certificate order.</span></span></param>
        <summary>
            <span data-ttu-id="05c7b-108">Fügt eine neue Bestellung der App Service-Zertifikat für den Hostnamen zu verwenden.</span><span class="sxs-lookup"><span data-stu-id="05c7b-108">Places a new App Service certificate order to use for the hostname.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="05c7b-109">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="05c7b-109">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxCertificateToUpload">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;ParentT&gt; WithPfxCertificateToUpload (string pfxFile, string password);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType`1&lt;!ParentT&gt; WithPfxCertificateToUpload(string pfxFile, string password) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithCertificate`1.WithPfxCertificateToUpload(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxCertificateToUpload (pfxFile As String, password As String) As IWithSslType(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithPfxCertificateToUpload : string * string -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;'ParentT&gt;" Usage="iWithCertificate.WithPfxCertificateToUpload (pfxFile, password)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameSslBinding.Definition.IWithSslType&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFile" Type="System.String" />
        <Parameter Name="password" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="pfxFile"><span data-ttu-id="05c7b-110">Die PFX-Zertifikatdatei hochgeladen.</span><span class="sxs-lookup"><span data-stu-id="05c7b-110">The PFX certificate file to upload.</span></span></param>
        <param name="password"><span data-ttu-id="05c7b-111">Das Kennwort für das Zertifikat.</span><span class="sxs-lookup"><span data-stu-id="05c7b-111">The password to the certificate.</span></span></param>
        <summary>
            <span data-ttu-id="05c7b-112">Lädt eine PFX-Zertifikat hoch.</span><span class="sxs-lookup"><span data-stu-id="05c7b-112">Uploads a PFX certificate.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="05c7b-113">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="05c7b-113">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>