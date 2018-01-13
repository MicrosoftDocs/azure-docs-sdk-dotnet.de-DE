<Type Name="IWithPrivateIP" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP">
  <TypeSignature Language="C#" Value="public interface IWithPrivateIP" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrivateIP" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrivateIP" />
  <TypeSignature Language="F#" Value="type IWithPrivateIP = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines virtuellen Computers, an eine private IP-Adresse im Subnetz eines virtuellen Netzwerks ermöglicht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryPrivateIPAddressDynamic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress WithPrimaryPrivateIPAddressDynamic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress WithPrimaryPrivateIPAddressDynamic() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP.WithPrimaryPrivateIPAddressDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryPrivateIPAddressDynamic () As IWithPublicIPAddress" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryPrivateIPAddressDynamic : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress" Usage="iWithPrivateIP.WithPrimaryPrivateIPAddressDynamic " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ermöglicht die dynamische private IP-Adresszuordnung innerhalb des angegebenen vorhandenen virtuellen Netzwerk-Subnetzes für primäre Netzwerkschnittstellen des virtuellen Computers.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPrimaryPrivateIPAddressStatic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress WithPrimaryPrivateIPAddressStatic (string staticPrivateIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress WithPrimaryPrivateIPAddressStatic(string staticPrivateIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP.WithPrimaryPrivateIPAddressStatic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryPrivateIPAddressStatic (staticPrivateIPAddress As String) As IWithPublicIPAddress" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryPrivateIPAddressStatic : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress" Usage="iWithPrivateIP.WithPrimaryPrivateIPAddressStatic staticPrivateIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="staticPrivateIPAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="staticPrivateIPAddress">Eine statische IP-Adresse im angegebenen Subnetz.</param>
        <summary>
            Weist die angegebene statische private IP-Adresse innerhalb des angegebenen vorhandenen virtuellen Netzwerk-Subnetzes primären Netzwerkschnittstelle des virtuellen Computers an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>