<Type Name="IWithSize" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSize">
  <TypeSignature Language="C#" Value="public interface IWithSize" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSize" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSize" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSize" />
  <TypeSignature Language="F#" Value="type IWithSize = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase einer Anwendung Gateway Update Möglichkeit zum Angeben der Größe.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSize">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithSize (Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName size);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate WithSize(class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName size) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithSize.WithSize(Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSize (size As ApplicationGatewaySkuName) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithSize : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate" Usage="iWithSize.WithSize size" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGateway.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="size" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewaySkuName" />
      </Parameters>
      <Docs>
        <param name="size">Eine Anwendung-Gateway-SKU-Name.</param>
        <summary>
            Gibt die Größe des Anwendungsgateways innerhalb des Kontexts für die ausgewählte Ebene zu erstellen.
            Standardmäßig ist die kleinste Größe verwendet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>