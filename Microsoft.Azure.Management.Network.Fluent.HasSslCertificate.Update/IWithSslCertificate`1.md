<Type Name="IWithSslCertificate&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslCertificate&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSslCertificate&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSslCertificate`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslCertificate`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSslCertificate(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithSslCertificate&lt;'ReturnT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ReturnT"><span data-ttu-id="1129c-101">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="1129c-101">The next stage of the update.</span></span></typeparam>
    <summary>
            <span data-ttu-id="1129c-102">Die Phase einer Ressource Update zu ermöglichen, geben Sie die SSL-Zertifikat zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="1129c-102">The stage of a resource update allowing to specify the SSL certificate to associate with it.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSslCertificate">
      <MemberSignature Language="C#" Value="public ReturnT WithSslCertificate (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithSslCertificate(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslCertificate`1.WithSslCertificate(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSslCertificate (name As String) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithSslCertificate : string -&gt; 'ReturnT" Usage="iWithSslCertificate.WithSslCertificate name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="1129c-103">Der Name eines vorhandenen SSL-Zertifikats, das diese Anwendungsgateway zugeordnet ist.</span><span class="sxs-lookup"><span data-stu-id="1129c-103">The name of an existing SSL certificate associated with this application gateway.</span></span></param>
        <summary>
            <span data-ttu-id="1129c-104">Gibt ein SSL-Zertifikat dieser Ressource zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="1129c-104">Specifies an SSL certificate to associate with this resource.</span></span>
            <span data-ttu-id="1129c-105">Wenn das Zertifikat noch nicht vorhanden ist, müssen sie das Update für die übergeordnete Ressource definiert werden.</span><span class="sxs-lookup"><span data-stu-id="1129c-105">If the certificate does not exist yet, it must be defined in the parent resource update.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="1129c-106">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="1129c-106">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSslCertificateFromPfxFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslPassword&lt;ReturnT&gt; WithSslCertificateFromPfxFile (System.IO.FileInfo pfxFile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslPassword`1&lt;!ReturnT&gt; WithSslCertificateFromPfxFile(class System.IO.FileInfo pfxFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslCertificate`1.WithSslCertificateFromPfxFile(System.IO.FileInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSslCertificateFromPfxFile (pfxFile As FileInfo) As IWithSslPassword(Of ReturnT)" />
      <MemberSignature Language="F#" Value="abstract member WithSslCertificateFromPfxFile : System.IO.FileInfo -&gt; Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslPassword&lt;'ReturnT&gt;" Usage="iWithSslCertificate.WithSslCertificateFromPfxFile pfxFile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.Update.IWithSslPassword&lt;ReturnT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFile" Type="System.IO.FileInfo" />
      </Parameters>
      <Docs>
        <param name="pfxFile"><span data-ttu-id="1129c-107">Eine vorhandene PFX-Datei.</span><span class="sxs-lookup"><span data-stu-id="1129c-107">An existing PFX file.</span></span></param>
        <summary>
            <span data-ttu-id="1129c-108">Gibt die PFX-Datei, um das SSL-Zertifikat von Importieren dieser Ressource zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="1129c-108">Specifies the PFX file to import the SSL certificate from to associate with this resource.</span></span>
            <span data-ttu-id="1129c-109">Das Zertifikat wird mit einem automatisch generierten Namen benannt.</span><span class="sxs-lookup"><span data-stu-id="1129c-109">The certificate will be named using an auto-generated name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws><span data-ttu-id="1129c-110">IOException bei Problemen mit der angegebenen Datei.</span><span class="sxs-lookup"><span data-stu-id="1129c-110">IOException when there are issues with the provided file.</span></span></throws>
        <return><span data-ttu-id="1129c-111">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="1129c-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>