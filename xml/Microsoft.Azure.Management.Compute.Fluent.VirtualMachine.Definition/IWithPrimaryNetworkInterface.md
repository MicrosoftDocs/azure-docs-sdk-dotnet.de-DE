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
            <span data-ttu-id="c1fef-101">Die Phase der Definition eines virtuellen Computers, an die primäre Netzwerkschnittstelle ermöglicht.</span><span class="sxs-lookup"><span data-stu-id="c1fef-101">The stage of a virtual machine definition allowing to specify the primary network interface.</span></span>
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
        <param name="networkInterface"><span data-ttu-id="c1fef-102">Eine vorhandene Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="c1fef-102">An existing network interface.</span></span></param>
        <summary>
            <span data-ttu-id="c1fef-103">Ordnet eine vorhandene Netzwerkschnittstelle dem virtuellen Computer als ihre primäre Netzwerkschnittstellen.</span><span class="sxs-lookup"><span data-stu-id="c1fef-103">Associates an existing network interface with the virtual machine as its primary network interface.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c1fef-104">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c1fef-104">The next stage of the definition.</span></span></return>
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
        <param name="creatable"><span data-ttu-id="c1fef-105">Eine erstellbare Definition für eine neue Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="c1fef-105">A creatable definition for a new network interface.</span></span></param>
        <summary>
            <span data-ttu-id="c1fef-106">Erstellt eine neue Netzwerkschnittstelle, die virtuelle Maschine als ihre primäre Netzwerkschnittstellen, basierend auf der bereitgestellten Definition zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="c1fef-106">Creates a new network interface to associate with the virtual machine as its primary network interface, based on the provided definition.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="c1fef-107">die nächste Phase der Definition.</span><span class="sxs-lookup"><span data-stu-id="c1fef-107">The next stage of the definition.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>