<Type Name="IWithHostNameDnsRecordType&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithHostNameDnsRecordType&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithHostNameDnsRecordType&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithHostNameDnsRecordType`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithHostNameDnsRecordType`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithHostNameDnsRecordType(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithHostNameDnsRecordType&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT"><span data-ttu-id="85837-101">die Phase der Definition des übergeordneten wieder nach dem Anfügen dieser Definition.</span><span class="sxs-lookup"><span data-stu-id="85837-101">The stage of the parent definition to return to after attaching this definition.</span></span></typeparam>
    <summary>
            <span data-ttu-id="85837-102">Die Stufe der ein Hostname Bindungsdefinition ermöglicht DNS-Eintragstyp festgelegt werden.</span><span class="sxs-lookup"><span data-stu-id="85837-102">The stage of a hostname binding definition allowing DNS record type to be set.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithDnsRecordType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithAttach&lt;ParentT&gt; WithDnsRecordType (Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType hostNameDnsRecordType);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithAttach`1&lt;!ParentT&gt; WithDnsRecordType(valuetype Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType hostNameDnsRecordType) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithHostNameDnsRecordType`1.WithDnsRecordType(Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDnsRecordType (hostNameDnsRecordType As CustomHostNameDnsRecordType) As IWithAttach(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithDnsRecordType : Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType -&gt; Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithAttach&lt;'ParentT&gt;" Usage="iWithHostNameDnsRecordType.WithDnsRecordType hostNameDnsRecordType" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.AppService.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.AppService.Fluent.HostNameBinding.UpdateDefinition.IWithAttach&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="hostNameDnsRecordType" Type="Microsoft.Azure.Management.AppService.Fluent.Models.CustomHostNameDnsRecordType" />
      </Parameters>
      <Docs>
        <param name="hostNameDnsRecordType"><span data-ttu-id="85837-103">Der DNS-Eintragstyp.</span><span class="sxs-lookup"><span data-stu-id="85837-103">The DNS record type.</span></span></param>
        <summary>
            <span data-ttu-id="85837-104">Gibt den DNS-Eintragstyp.</span><span class="sxs-lookup"><span data-stu-id="85837-104">Specifies the DNS record type.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="85837-105">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="85837-105">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>