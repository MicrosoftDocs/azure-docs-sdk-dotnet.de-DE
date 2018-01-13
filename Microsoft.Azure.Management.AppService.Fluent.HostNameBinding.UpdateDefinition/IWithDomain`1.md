<Type Name="IWithDomain&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithDomain&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithDomain&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithDomain`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithDomain`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithDomain(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithDomain&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</typeparam>
    <summary>
            Die Stufe der ein Hostname Bindungsdefinition ermöglicht Domäne angegeben werden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAzureManagedDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithSubDomain&lt;ParentT&gt; WithAzureManagedDomain (Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithSubDomain`1&lt;!ParentT&gt; WithAzureManagedDomain(class Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithDomain`1.WithAzureManagedDomain(Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAzureManagedDomain (domain As IAppServiceDomain) As IWithSubDomain(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithAzureManagedDomain : Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithSubDomain&lt;'ParentT&gt;" Usage="iWithDomain.WithAzureManagedDomain domain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithSubDomain&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="Microsoft.Azure.Management.AppService.Fluent.IAppServiceDomain" />
      </Parameters>
      <Docs>
        <param name="domain">Die Domäne von Azure erworben wurde.</param>
        <summary>
            Bindet die zu einer Domäne von Azure erworben wurde.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithThirdPartyDomain">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithSubDomain&lt;ParentT&gt; WithThirdPartyDomain (string domain);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithSubDomain`1&lt;!ParentT&gt; WithThirdPartyDomain(string domain) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithDomain`1.WithThirdPartyDomain(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithThirdPartyDomain (domain As String) As IWithSubDomain(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithThirdPartyDomain : string -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithSubDomain&lt;'ParentT&gt;" Usage="iWithDomain.WithThirdPartyDomain domain" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithSubDomain&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="domain" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="domain">Der 3rd Party-Domänenname.</param>
        <summary>
            Um eine 3rd Domäne party bindet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>