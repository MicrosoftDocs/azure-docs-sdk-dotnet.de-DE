<Type Name="IVirtualMachineScaleSetNetworkInterfaces" FullName="Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterfaces">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineScaleSetNetworkInterfaces : Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineScaleSetNetworkInterfaces implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing`1&lt;class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterfaces" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineScaleSetNetworkInterfaces&#xA;Implements IHasInner(Of INetworkInterfacesOperations), IHasManager(Of INetworkManager), ISupportsListing(Of IVirtualMachineScaleSetNetworkInterface)" />
  <TypeSignature Language="F#" Value="type IVirtualMachineScaleSetNetworkInterfaces = interface&#xA;    interface ISupportsListing&lt;IVirtualMachineScaleSetNetworkInterface&gt;&#xA;    interface IHasInner&lt;INetworkInterfacesOperations&gt;&#xA;    interface IHasManager&lt;INetworkManager&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.CollectionActions.ISupportsListing&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterfacesOperations&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Network.Fluent.INetworkManager&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Der Einstiegspunkt für die virtuelle Maschine Scale Set Netzwerk Schnittstelle Verwaltungs-API.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="GetByVirtualMachineInstanceId">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetByVirtualMachineInstanceId (string instanceId, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetByVirtualMachineInstanceId(string instanceId, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterfaces.GetByVirtualMachineInstanceId(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetByVirtualMachineInstanceId (instanceId As String, name As String) As IVirtualMachineScaleSetNetworkInterface" />
      <MemberSignature Language="F#" Value="abstract member GetByVirtualMachineInstanceId : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface" Usage="iVirtualMachineScaleSetNetworkInterfaces.GetByVirtualMachineInstanceId (instanceId, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instanceId" Type="System.String" />
        <Parameter Name="name" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="instanceId">Die Vm-Instanz-Id im VM-Skalierungsgruppe.</param>
        <param name="name">Der Name des Netzwerk-Schnittstelle.</param>
        <summary>
            Ruft eine Netzwerkschnittstelle, die Instanz eines virtuellen Computers Skalierung Satz zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Netzwerkschnittstelle.</return>
      </Docs>
    </Member>
    <Member MemberName="ListByVirtualMachineInstanceId">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListByVirtualMachineInstanceId (string instanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListByVirtualMachineInstanceId(string instanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterfaces.ListByVirtualMachineInstanceId(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListByVirtualMachineInstanceId (instanceId As String) As IEnumerable(Of IVirtualMachineScaleSetNetworkInterface)" />
      <MemberSignature Language="F#" Value="abstract member ListByVirtualMachineInstanceId : string -&gt; seq&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;" Usage="iVirtualMachineScaleSetNetworkInterfaces.ListByVirtualMachineInstanceId instanceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="instanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="instanceId">VM-Skalierungsgruppe Instanz-Id des virtuellen Computers.</param>
        <summary>
            Listet alle Netzwerkschnittstellen, die für die zugeordnete Instanz eines virtuellen Computers in der Menge der Skala an.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Liste der Netzwerkschnittstellen.</return>
      </Docs>
    </Member>
  </Members>
</Type>