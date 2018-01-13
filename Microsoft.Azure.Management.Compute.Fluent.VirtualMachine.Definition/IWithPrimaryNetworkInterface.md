<Type Name="IWithPrimaryNetworkInterface" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryNetworkInterface" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryNetworkInterface" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryNetworkInterface" />
  <TypeSignature Language="F#" Value="type IWithPrimaryNetworkInterface = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines virtuellen Computers, an die primäre Netzwerkschnittstelle ermöglicht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithExistingPrimaryNetworkInterface (Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithExistingPrimaryNetworkInterface(class Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface.WithExistingPrimaryNetworkInterface(Microsoft.Azure.Management.Network.Fluent.INetworkInterface)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryNetworkInterface (networkInterface As INetworkInterface) As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryNetworkInterface : Microsoft.Azure.Management.Network.Fluent.INetworkInterface -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" Usage="iWithPrimaryNetworkInterface.WithExistingPrimaryNetworkInterface networkInterface" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="networkInterface" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterface" />
      </Parameters>
      <Docs>
        <param name="networkInterface">Eine vorhandene Netzwerkschnittstelle.</param>
        <summary>
            Ordnet eine vorhandene Netzwerkschnittstelle dem virtuellen Computer als ihre primäre Netzwerkschnittstellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithNewPrimaryNetworkInterface (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithNewPrimaryNetworkInterface(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPrimaryNetworkInterface.WithNewPrimaryNetworkInterface(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetworkInterface})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetworkInterface (creatable As ICreatable(Of INetworkInterface)) As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetworkInterface : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" Usage="iWithPrimaryNetworkInterface.WithNewPrimaryNetworkInterface creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Eine erstellbare Definition für eine neue Netzwerkschnittstelle.</param>
        <summary>
            Erstellt eine neue Netzwerkschnittstelle, die virtuelle Maschine als ihre primäre Netzwerkschnittstellen, basierend auf der bereitgestellten Definition zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>