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
    <typeparam name="ReturnT">die nächste Phase des Updates.</typeparam>
    <summary>
            Die Phase einer Ressource Update zu ermöglichen, geben Sie die SSL-Zertifikat zugeordnet werden soll.
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
        <param name="name">Der Name eines vorhandenen SSL-Zertifikats, das diese Anwendungsgateway zugeordnet ist.</param>
        <summary>
            Gibt ein SSL-Zertifikat dieser Ressource zugeordnet werden soll.
            Wenn das Zertifikat noch nicht vorhanden ist, müssen sie das Update für die übergeordnete Ressource definiert werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
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
        <param name="pfxFile">Eine vorhandene PFX-Datei.</param>
        <summary>
            Gibt die PFX-Datei, um das SSL-Zertifikat von Importieren dieser Ressource zugeordnet werden soll.
            Das Zertifikat wird mit einem automatisch generierten Namen benannt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws>IOException bei Problemen mit der angegebenen Datei.</throws>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>