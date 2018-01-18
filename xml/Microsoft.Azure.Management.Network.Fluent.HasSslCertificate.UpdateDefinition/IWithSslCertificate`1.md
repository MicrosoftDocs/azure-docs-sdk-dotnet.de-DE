<Type Name="IWithSslCertificate&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslCertificate&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithSslCertificate&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSslCertificate`1&lt;ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslCertificate`1" />
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
    <typeparam name="ReturnT"><span data-ttu-id="8b716-101">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="8b716-101">The next stage of the definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="8b716-102">Die Stufe der einer Ressourcendefinition, sodass an SSL-Zertifikat zugeordnet.</span><span class="sxs-lookup"><span data-stu-id="8b716-102">The stage of a resource definition allowing to specify the SSL certificate to associate with it.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSslCertificate">
      <MemberSignature Language="C#" Value="public ReturnT WithSslCertificate (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithSslCertificate(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslCertificate`1.WithSslCertificate(System.String)" />
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
        <param name="name"><span data-ttu-id="8b716-103">der Name eines vorhandenen SSL-Zertifikats.</span><span class="sxs-lookup"><span data-stu-id="8b716-103">The name of an existing SSL certificate.</span></span></param>
        <summary>
            <span data-ttu-id="8b716-104">Gibt ein SSL-Zertifikat dieser Ressource zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="8b716-104">Specifies an SSL certificate to associate with this resource.</span></span>
            <span data-ttu-id="8b716-105">Wenn das Zertifikat noch nicht vorhanden ist, muss er in den optionalen Teil der Definition des übergeordneten Ressource definiert werden.</span><span class="sxs-lookup"><span data-stu-id="8b716-105">If the certificate does not exist yet, it must be defined in the optional part of the parent resource definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="8b716-106">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="8b716-106">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithSslCertificateFromPfxFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword&lt;ReturnT&gt; WithSslCertificateFromPfxFile (System.IO.FileInfo pfxFile);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword`1&lt;!ReturnT&gt; WithSslCertificateFromPfxFile(class System.IO.FileInfo pfxFile) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslCertificate`1.WithSslCertificateFromPfxFile(System.IO.FileInfo)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSslCertificateFromPfxFile (pfxFile As FileInfo) As IWithSslPassword(Of ReturnT)" />
      <MemberSignature Language="F#" Value="abstract member WithSslCertificateFromPfxFile : System.IO.FileInfo -&gt; Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword&lt;'ReturnT&gt;" Usage="iWithSslCertificate.WithSslCertificateFromPfxFile pfxFile" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.HasSslCertificate.UpdateDefinition.IWithSslPassword&lt;ReturnT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxFile" Type="System.IO.FileInfo" />
      </Parameters>
      <Docs>
        <param name="pfxFile"><span data-ttu-id="8b716-107">Eine vorhandene PFX-Datei.</span><span class="sxs-lookup"><span data-stu-id="8b716-107">An existing PFX file.</span></span></param>
        <summary>
            <span data-ttu-id="8b716-108">Gibt die PFX-Datei, um das SSL-Zertifikat aus, die in dieser Ressource zugeordneten importieren.</span><span class="sxs-lookup"><span data-stu-id="8b716-108">Specifies the PFX file to import the SSL certificate from to associated with this resource.</span></span>
            <span data-ttu-id="8b716-109">Das Zertifikat wird mit einem automatisch generierten Namen benannt.</span><span class="sxs-lookup"><span data-stu-id="8b716-109">The certificate will be named using an auto-generated name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws><span data-ttu-id="8b716-110">IOException bei Problemen mit der angegebenen Datei.</span><span class="sxs-lookup"><span data-stu-id="8b716-110">IOException when there are issues with the provided file.</span></span></throws>
        <return><span data-ttu-id="8b716-111">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="8b716-111">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>