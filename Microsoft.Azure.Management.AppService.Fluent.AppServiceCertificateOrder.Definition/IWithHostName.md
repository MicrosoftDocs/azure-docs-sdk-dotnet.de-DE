<Type Name="IWithHostName" FullName="Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithHostName">
  <TypeSignature Language="C#" Value="public interface IWithHostName" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithHostName" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithHostName" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithHostName" />
  <TypeSignature Language="F#" Value="type IWithHostName = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine app Zertifikat Reihenfolge Dienstdefinition Hostname festgelegt werden können.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithHostName">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku WithHostName (string hostName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku WithHostName(string hostName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithHostName.WithHostName(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithHostName (hostName As String) As IWithCertificateSku" />
      <MemberSignature Language="F#" Value="abstract member WithHostName : string -&gt; Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku" Usage="iWithHostName.WithHostName hostName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.AppServiceCertificateOrder.Definition.IWithCertificateSku</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="hostName">der bare Hostname ohne "Www". Verwenden. Präfix ist ein Platzhalter-Zertifikat.</param>
        <summary>
            Gibt den Hostnamen, dem das Zertifikat gebunden wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>