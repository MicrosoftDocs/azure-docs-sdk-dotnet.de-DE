<Type Name="IWithCertificate" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate">
  <TypeSignature Language="C#" Value="public interface IWithCertificate" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCertificate" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCertificate" />
  <TypeSignature Language="F#" Value="type IWithCertificate = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine app Zertifikat Dienstdefinition PFX-Zertifikatdatei festgelegt werden können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingCertificateOrder">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate WithExistingCertificateOrder (Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder certificateOrder);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate WithExistingCertificateOrder(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder certificateOrder) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate.WithExistingCertificateOrder(Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingCertificateOrder (certificateOrder As IAppServiceCertificateOrder) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingCertificateOrder : Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate" Usage="iWithCertificate.WithExistingCertificateOrder certificateOrder" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="certificateOrder" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceCertificateOrder" />
      </Parameters>
      <Docs>
        <param name="certificateOrder">Die Reihenfolge der app Service-Zertifikat.</param>
        <summary>
            Gibt das app Service-Zertifikat.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxByteArray">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxByteArray (params byte[] pfxByteArray);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxByteArray(unsigned int8[] pfxByteArray) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate.WithPfxByteArray(System.Byte[])" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxByteArray (ParamArray pfxByteArray As Byte()) As IWithPfxFilePassword" />
      <MemberSignature Language="F#" Value="abstract member WithPfxByteArray : byte[] -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword" Usage="iWithCertificate.WithPfxByteArray pfxByteArray" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="pfxByteArray" Type="System.Byte[]">
          <Attributes>
            <Attribute>
              <AttributeName>System.ParamArray</AttributeName>
            </Attribute>
          </Attributes>
        </Parameter>
      </Parameters>
      <Docs>
        <param name="pfxByteArray">Das PFX-Bytearray.</param>
        <summary>
            Gibt das PFX-Bytearray hochladen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxFile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxFile (string file);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxFile(string file) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate.WithPfxFile(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxFile (file As String) As IWithPfxFilePassword" />
      <MemberSignature Language="F#" Value="abstract member WithPfxFile : string -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword" Usage="iWithCertificate.WithPfxFile file" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="file" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="file">Die PFX-Zertifikatdatei.</param>
        <summary>
            Gibt die PFX-Zertifikatdatei hochgeladen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPfxFileFromUrl">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxFileFromUrl (string url);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword WithPfxFileFromUrl(string url) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithCertificate.WithPfxFileFromUrl(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPfxFileFromUrl (url As String) As IWithPfxFilePassword" />
      <MemberSignature Language="F#" Value="abstract member WithPfxFileFromUrl : string -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword" Usage="iWithCertificate.WithPfxFileFromUrl url" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificate.Definition.IWithPfxFilePassword</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="url" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="url">die URL verweist auf die PFX-Datei.</param>
        <summary>
            Gibt die PFX-Datei von einer URL an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>