<Type Name="IWithIPAddress" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithIPAddress" />
  <TypeSignature Language="F#" Value="type IWithIPAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine öffentliche IP-Adresse aktualisieren, sodass so ändern Sie die IP-Zuordnungsmethode (statisch oder dynamisch).
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDynamicIP">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithDynamicIP ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithDynamicIP() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIPAddress.WithDynamicIP" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDynamicIP () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithDynamicIP : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithIPAddress.WithDynamicIP " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ermöglicht die dynamische Zuordnung von IP-Adresse.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Ressource-Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithStaticIP">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithStaticIP ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithStaticIP() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithIPAddress.WithStaticIP" />
      <MemberSignature Language="VB.NET" Value="Public Function WithStaticIP () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithStaticIP : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithIPAddress.WithStaticIP " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Können statische IP-Adresszuordnung.
            Verwenden Sie PublicIPAddress.ipAddress(), nachdem die öffentliche IP-Adresse aktualisiert wird, um die tatsächliche IP-Adresse für diese Ressource zugeordnet werden, von Azure zu erhalten.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Ressource-Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>