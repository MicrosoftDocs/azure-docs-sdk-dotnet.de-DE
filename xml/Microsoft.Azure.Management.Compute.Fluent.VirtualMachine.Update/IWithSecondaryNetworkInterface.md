<Type Name="IWithSecondaryNetworkInterface" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface">
  <TypeSignature Language="C#" Value="public interface IWithSecondaryNetworkInterface" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSecondaryNetworkInterface" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSecondaryNetworkInterface" />
  <TypeSignature Language="F#" Value="type IWithSecondaryNetworkInterface = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            <span data-ttu-id="f37fa-101">Die Stufe der ein Update der virtuellen Maschine können zusätzliche Netzwerkschnittstellen an.</span><span class="sxs-lookup"><span data-stu-id="f37fa-101">The stage of a virtual machine update allowing to specify additional network interfaces.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingSecondaryNetworkInterface (Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithExistingSecondaryNetworkInterface(class Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface.WithExistingSecondaryNetworkInterface(Microsoft.Azure.Management.Network.Fluent.INetworkInterface)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSecondaryNetworkInterface (networkInterface As INetworkInterface) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSecondaryNetworkInterface : Microsoft.Azure.Management.Network.Fluent.INetworkInterface -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithSecondaryNetworkInterface.WithExistingSecondaryNetworkInterface networkInterface" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="networkInterface" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterface" />
      </Parameters>
      <Docs>
        <param name="networkInterface"><span data-ttu-id="f37fa-102">Eine vorhandene Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="f37fa-102">An existing network interface.</span></span></param>
        <summary>
            <span data-ttu-id="f37fa-103">Ordnet eine vorhandene Netzwerkschnittstelle mit dem virtuellen Computer an.</span><span class="sxs-lookup"><span data-stu-id="f37fa-103">Associates an existing network interface with the virtual machine.</span></span>
            <span data-ttu-id="f37fa-104">Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedem dient, die neue sekundäre Netzwerkschnittstelle hinzugefügt mit dem virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="f37fa-104">Note this method's effect is additive, i.e. each time it is used, the new secondary network interface added to the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f37fa-105">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="f37fa-105">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewSecondaryNetworkInterface (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithNewSecondaryNetworkInterface(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface.WithNewSecondaryNetworkInterface(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetworkInterface})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSecondaryNetworkInterface (creatable As ICreatable(Of INetworkInterface)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSecondaryNetworkInterface : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithSecondaryNetworkInterface.WithNewSecondaryNetworkInterface creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable"><span data-ttu-id="f37fa-106">Eine erstellbare Definition für eine neue Netzwerkschnittstelle.</span><span class="sxs-lookup"><span data-stu-id="f37fa-106">A creatable definition for a new network interface.</span></span></param>
        <summary>
            <span data-ttu-id="f37fa-107">Erstellt eine neue Netzwerkschnittstelle dem virtuellen Computer zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="f37fa-107">Creates a new network interface to associate with the virtual machine.</span></span>
            <span data-ttu-id="f37fa-108">Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedem dient, die neue sekundäre Netzwerkschnittstelle hinzugefügt mit dem virtuellen Computer.</span><span class="sxs-lookup"><span data-stu-id="f37fa-108">Note this method's effect is additive, i.e. each time it is used, the new secondary network interface added to the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f37fa-109">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="f37fa-109">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
    <Member MemberName="WithoutSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutSecondaryNetworkInterface (string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate WithoutSecondaryNetworkInterface(string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IWithSecondaryNetworkInterface.WithoutSecondaryNetworkInterface(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutSecondaryNetworkInterface (name As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutSecondaryNetworkInterface : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate" Usage="iWithSecondaryNetworkInterface.WithoutSecondaryNetworkInterface name" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name"><span data-ttu-id="f37fa-110">Der Name einer sekundären Netzwerkschnittstelle entfernt.</span><span class="sxs-lookup"><span data-stu-id="f37fa-110">The name of a secondary network interface to remove.</span></span></param>
        <summary>
            <span data-ttu-id="f37fa-111">Entfernt eine sekundäre Netzwerkschnittstelle des virtuellen Computers an.</span><span class="sxs-lookup"><span data-stu-id="f37fa-111">Removes a secondary network interface from the virtual machine.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="f37fa-112">die nächste Phase des Updates.</span><span class="sxs-lookup"><span data-stu-id="f37fa-112">The next stage of the update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>