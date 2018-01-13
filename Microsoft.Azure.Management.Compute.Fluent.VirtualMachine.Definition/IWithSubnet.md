<Type Name="IWithSubnet" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet">
  <TypeSignature Language="C#" Value="public interface IWithSubnet" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSubnet" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSubnet" />
  <TypeSignature Language="F#" Value="type IWithSubnet = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines virtuellen Computers, ermöglicht das Subnetz des virtuellen Netzwerks für eine neue primäre Netzwerkschnittstelle an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithSubnet">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP WithSubnet (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP WithSubnet(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSubnet.WithSubnet(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithSubnet (name As String) As IWithPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithSubnet : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP" Usage="iWithSubnet.WithSubnet name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Subnetzname.</param>
        <summary>
            Ordnet primäre Netzwerkschnittstellen des virtuellen Computers ein Subnetz hinzu.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>