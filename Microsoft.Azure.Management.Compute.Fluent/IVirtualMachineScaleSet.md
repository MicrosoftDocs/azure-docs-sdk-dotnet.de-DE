<Type Name="IVirtualMachineScaleSet" FullName="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet">
  <TypeSignature Language="C#" Value="public interface IVirtualMachineScaleSet : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryLoadBalancer&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IVirtualMachineScaleSet implements class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource`2&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager, class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasId, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner`1&lt;class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasName, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasResourceGroup, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IResource, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryLoadBalancer&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet" />
  <TypeSignature Language="VB.NET" Value="Public Interface IVirtualMachineScaleSet&#xA;Implements IBeta, IGroupableResource(Of IComputeManager, VirtualMachineScaleSetInner), IHasInner(Of VirtualMachineScaleSetInner), IHasManager(Of IComputeManager), IRefreshable(Of IVirtualMachineScaleSet), IUpdatable(Of IWithPrimaryLoadBalancer), IVirtualMachineScaleSetBeta" />
  <TypeSignature Language="F#" Value="type IVirtualMachineScaleSet = interface&#xA;    interface IGroupableResource&lt;IComputeManager, VirtualMachineScaleSetInner&gt;&#xA;    interface IResource&#xA;    interface IIndexable&#xA;    interface IHasId&#xA;    interface IHasName&#xA;    interface IHasResourceGroup&#xA;    interface IHasManager&lt;IComputeManager&gt;&#xA;    interface IHasInner&lt;VirtualMachineScaleSetInner&gt;&#xA;    interface IRefreshable&lt;IVirtualMachineScaleSet&gt;&#xA;    interface IUpdatable&lt;IWithPrimaryLoadBalancer&gt;&#xA;    interface IVirtualMachineScaleSetBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IGroupableResource&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager,Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasInner&lt;Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetInner&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IHasManager&lt;Microsoft.Azure.Management.Compute.Fluent.IComputeManager&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IRefreshable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IUpdatable&lt;Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSet.Update.IWithPrimaryLoadBalancer&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Eine unveränderliche clientseitige Darstellung einer Azure VM-Skalierungsgruppe festgelegt.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="Capacity">
      <MemberSignature Language="C#" Value="public int Capacity { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance int32 Capacity" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Capacity" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Capacity As Integer" />
      <MemberSignature Language="F#" Value="member this.Capacity : int" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Capacity" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Int32</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Anzahl der Instanzen virtueller Computer in der Menge der Skala.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ComputerNamePrefix">
      <MemberSignature Language="C#" Value="public string ComputerNamePrefix { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string ComputerNamePrefix" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ComputerNamePrefix" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property ComputerNamePrefix As String" />
      <MemberSignature Language="F#" Value="member this.ComputerNamePrefix : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ComputerNamePrefix" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Namenspräfix der virtuellen Computer in der Menge der Skala.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Deallocate">
      <MemberSignature Language="C#" Value="public void Deallocate ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Deallocate() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Deallocate" />
      <MemberSignature Language="VB.NET" Value="Public Sub Deallocate ()" />
      <MemberSignature Language="F#" Value="abstract member Deallocate : unit -&gt; unit" Usage="iVirtualMachineScaleSet.Deallocate " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Die virtuellen Computer in der Skalierungsgruppe heruntergefahren und seine Compute-Ressourcen frei.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="DeallocateAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task DeallocateAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task DeallocateAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.DeallocateAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member DeallocateAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSet.DeallocateAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Die virtuellen Computer in der Skalierungsgruppe heruntergefahren und asynchron die Compute-Ressourcen frei.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
    <Member MemberName="Extensions">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension&gt; Extensions { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension&gt; Extensions" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Extensions" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Extensions As IReadOnlyDictionary(Of String, IVirtualMachineScaleSetExtension)" />
      <MemberSignature Language="F#" Value="member this.Extensions : System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Extensions" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetExtension&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Erweiterungen, die die virtuellen Computer in der Skalierungsgruppe zugeordnet sind.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="GetNetworkInterfaceByInstanceId">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetNetworkInterfaceByInstanceId (string instanceId, string name);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface GetNetworkInterfaceByInstanceId(string instanceId, string name) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.GetNetworkInterfaceByInstanceId(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function GetNetworkInterfaceByInstanceId (instanceId As String, name As String) As IVirtualMachineScaleSetNetworkInterface" />
      <MemberSignature Language="F#" Value="abstract member GetNetworkInterfaceByInstanceId : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface" Usage="iVirtualMachineScaleSet.GetNetworkInterfaceByInstanceId (instanceId, name)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
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
        <param name="instanceId">Die VM-Skalierungsgruppe Vm-Instanz-ID.</param>
        <param name="name">Der Name des Netzwerk-Schnittstelle.</param>
        <summary>
            Ruft eine Netzwerkschnittstelle, die Instanz eines virtuellen Computers Skalierung Satz zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Netzwerkschnittstelle.</return>
      </Docs>
    </Member>
    <Member MemberName="GetPrimaryInternalLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancer GetPrimaryInternalLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer GetPrimaryInternalLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.GetPrimaryInternalLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPrimaryInternalLoadBalancer () As ILoadBalancer" />
      <MemberSignature Language="F#" Value="abstract member GetPrimaryInternalLoadBalancer : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" Usage="iVirtualMachineScaleSet.GetPrimaryInternalLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws>IOException die e/a-Ausnahme.</throws>
        <return>
            Legen Sie der internen Lastenausgleich, die der virtuellen Computer in die Skalierung der primären Netzwerkschnittstelle zugeordnet.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetPrimaryInternetFacingLoadBalancer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ILoadBalancer GetPrimaryInternetFacingLoadBalancer ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ILoadBalancer GetPrimaryInternetFacingLoadBalancer() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.GetPrimaryInternetFacingLoadBalancer" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPrimaryInternetFacingLoadBalancer () As ILoadBalancer" />
      <MemberSignature Language="F#" Value="abstract member GetPrimaryInternetFacingLoadBalancer : unit -&gt; Microsoft.Azure.Management.Network.Fluent.ILoadBalancer" Usage="iVirtualMachineScaleSet.GetPrimaryInternetFacingLoadBalancer " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ILoadBalancer</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws>IOException die e/a-Ausnahme.</throws>
        <return>
            der Internetzugriff Load Balancer zugeordnete primäre Netzwerkschnittstelle der virtuellen Computer in der Skala festlegen.
            </return>
      </Docs>
    </Member>
    <Member MemberName="GetPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.INetwork GetPrimaryNetwork ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.INetwork GetPrimaryNetwork() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.GetPrimaryNetwork" />
      <MemberSignature Language="VB.NET" Value="Public Function GetPrimaryNetwork () As INetwork" />
      <MemberSignature Language="F#" Value="abstract member GetPrimaryNetwork : unit -&gt; Microsoft.Azure.Management.Network.Fluent.INetwork" Usage="iVirtualMachineScaleSet.GetPrimaryNetwork " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.INetwork</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="IsManagedDiskEnabled">
      <MemberSignature Language="C#" Value="public bool IsManagedDiskEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool IsManagedDiskEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.IsManagedDiskEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property IsManagedDiskEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.IsManagedDiskEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.IsManagedDiskEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn verwaltete Datenträger für die VM-Skalierungsgruppe Datenträger (BS, Data) verwendet wird.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ListAvailableSkus">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku&gt; ListAvailableSkus ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku&gt; ListAvailableSkus() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListAvailableSkus" />
      <MemberSignature Language="VB.NET" Value="Public Function ListAvailableSkus () As IEnumerable(Of IVirtualMachineScaleSetSku)" />
      <MemberSignature Language="F#" Value="abstract member ListAvailableSkus : unit -&gt; seq&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku&gt;" Usage="iVirtualMachineScaleSet.ListAvailableSkus " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetSku&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>
            Verfügbare SKUs für die VM-Skalierungsgruppe, einschließlich minimalen und maximalen VM-Instanzen, die für eine bestimmte SKU zulässig.
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListNetworkInterfaces">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfaces ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfaces() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListNetworkInterfaces" />
      <MemberSignature Language="VB.NET" Value="Public Function ListNetworkInterfaces () As IEnumerable(Of IVirtualMachineScaleSetNetworkInterface)" />
      <MemberSignature Language="F#" Value="abstract member ListNetworkInterfaces : unit -&gt; seq&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;" Usage="iVirtualMachineScaleSet.ListNetworkInterfaces " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Netzwerkschnittstellen, die alle virtuelle Computerinstanzen in einem Satz Skala zugeordnet wird.</return>
      </Docs>
    </Member>
    <Member MemberName="ListNetworkInterfacesByInstanceId">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfacesByInstanceId (string virtualMachineInstanceId);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IEnumerable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt; ListNetworkInterfacesByInstanceId(string virtualMachineInstanceId) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListNetworkInterfacesByInstanceId(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function ListNetworkInterfacesByInstanceId (virtualMachineInstanceId As String) As IEnumerable(Of IVirtualMachineScaleSetNetworkInterface)" />
      <MemberSignature Language="F#" Value="abstract member ListNetworkInterfacesByInstanceId : string -&gt; seq&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;" Usage="iVirtualMachineScaleSet.ListNetworkInterfacesByInstanceId virtualMachineInstanceId" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IEnumerable&lt;Microsoft.Azure.Management.Network.Fluent.IVirtualMachineScaleSetNetworkInterface&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="virtualMachineInstanceId" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="virtualMachineInstanceId">Die Instanz-ID.</param>
        <summary>
            Listet die Netzwerkschnittstelle, die Instanz eines bestimmten virtuellen Maschine in der Skalierungsgruppe zugeordnet.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die Netzwerkschnittstellen.</return>
      </Docs>
    </Member>
    <Member MemberName="ListPrimaryInternalLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt; ListPrimaryInternalLoadBalancerBackends ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt; ListPrimaryInternalLoadBalancerBackends() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListPrimaryInternalLoadBalancerBackends" />
      <MemberSignature Language="VB.NET" Value="Public Function ListPrimaryInternalLoadBalancerBackends () As IReadOnlyDictionary(Of String, ILoadBalancerBackend)" />
      <MemberSignature Language="F#" Value="abstract member ListPrimaryInternalLoadBalancerBackends : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt;" Usage="iVirtualMachineScaleSet.ListPrimaryInternalLoadBalancerBackends " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws>IOException die e/a-Ausnahme.</throws>
        <return>
            Legen Sie den internen Lastenausgleich-Back-Ends der virtuellen Computer in die Skalierung der primären Netzwerkschnittstelle zugeordnet.
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListPrimaryInternalLoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt; ListPrimaryInternalLoadBalancerInboundNatPools ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt; ListPrimaryInternalLoadBalancerInboundNatPools() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListPrimaryInternalLoadBalancerInboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Function ListPrimaryInternalLoadBalancerInboundNatPools () As IReadOnlyDictionary(Of String, ILoadBalancerInboundNatPool)" />
      <MemberSignature Language="F#" Value="abstract member ListPrimaryInternalLoadBalancerInboundNatPools : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt;" Usage="iVirtualMachineScaleSet.ListPrimaryInternalLoadBalancerInboundNatPools " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws>IOException die e/a-Ausnahme.</throws>
        <return>
            die eingehende NAT-Pools des internen Lastenausgleichs primäre Netzwerkschnittstelle der virtuellen Computer in der Menge Skalierung ggf. zugeordnet.
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListPrimaryInternetFacingLoadBalancerBackends">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt; ListPrimaryInternetFacingLoadBalancerBackends ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt; ListPrimaryInternetFacingLoadBalancerBackends() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListPrimaryInternetFacingLoadBalancerBackends" />
      <MemberSignature Language="VB.NET" Value="Public Function ListPrimaryInternetFacingLoadBalancerBackends () As IReadOnlyDictionary(Of String, ILoadBalancerBackend)" />
      <MemberSignature Language="F#" Value="abstract member ListPrimaryInternetFacingLoadBalancerBackends : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt;" Usage="iVirtualMachineScaleSet.ListPrimaryInternetFacingLoadBalancerBackends " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerBackend&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws>IOException die e/a-Ausnahme.</throws>
        <return>
            Der Internetzugriff Load Balancer-Back-Ends zugeordnete primäre Netzwerkschnittstelle der virtuellen Computer in der Skala festlegen.
            </return>
      </Docs>
    </Member>
    <Member MemberName="ListPrimaryInternetFacingLoadBalancerInboundNatPools">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyDictionary&lt;string,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt; ListPrimaryInternetFacingLoadBalancerInboundNatPools ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Collections.Generic.IReadOnlyDictionary`2&lt;string, class Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt; ListPrimaryInternetFacingLoadBalancerInboundNatPools() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ListPrimaryInternetFacingLoadBalancerInboundNatPools" />
      <MemberSignature Language="VB.NET" Value="Public Function ListPrimaryInternetFacingLoadBalancerInboundNatPools () As IReadOnlyDictionary(Of String, ILoadBalancerInboundNatPool)" />
      <MemberSignature Language="F#" Value="abstract member ListPrimaryInternetFacingLoadBalancerInboundNatPools : unit -&gt; System.Collections.Generic.IReadOnlyDictionary&lt;string, Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt;" Usage="iVirtualMachineScaleSet.ListPrimaryInternetFacingLoadBalancerInboundNatPools " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyDictionary&lt;System.String,Microsoft.Azure.Management.Network.Fluent.ILoadBalancerInboundNatPool&gt;</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>To be added.</summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <throws>IOException die e/a-Ausnahme.</throws>
        <return>
            Der Internetzugriff laden Lastenausgleich des eingehenden NAT-Pool der virtuellen Computer in der Skalierungsgruppe der primären Netzwerkschnittstelle zugeordnet.
            </return>
      </Docs>
    </Member>
    <Member MemberName="NetworkProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetNetworkProfile NetworkProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetNetworkProfile NetworkProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.NetworkProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property NetworkProfile As VirtualMachineScaleSetNetworkProfile" />
      <MemberSignature Language="F#" Value="member this.NetworkProfile : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetNetworkProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.NetworkProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetNetworkProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Netzwerkprofil ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskCachingType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes OSDiskCachingType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes OSDiskCachingType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSDiskCachingType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskCachingType As CachingTypes" />
      <MemberSignature Language="F#" Value="member this.OSDiskCachingType : Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSDiskCachingType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.CachingTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Betriebssystem-Datenträger Typ Zwischenspeichern.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSDiskName">
      <MemberSignature Language="C#" Value="public string OSDiskName { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance string OSDiskName" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSDiskName" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSDiskName As String" />
      <MemberSignature Language="F#" Value="member this.OSDiskName : string" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSDiskName" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.String</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft den Namen der BS-Datenträger der virtuellen Computer in der Menge der Skalierung ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OSType">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes OSType" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSType" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OSType As OperatingSystemTypes" />
      <MemberSignature Language="F#" Value="member this.OSType : Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OSType" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.OperatingSystemTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Betriebssystem der virtuellen Computer in der Menge der Skala an.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="OverProvisionEnabled">
      <MemberSignature Language="C#" Value="public bool OverProvisionEnabled { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance bool OverProvisionEnabled" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OverProvisionEnabled" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property OverProvisionEnabled As Boolean" />
      <MemberSignature Language="F#" Value="member this.OverProvisionEnabled : bool" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.OverProvisionEnabled" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Boolean</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft "true", wenn über die Bereitstellung für die virtuellen Maschinen, "false" andernfalls aktiviert ist.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOff">
      <MemberSignature Language="C#" Value="public void PowerOff ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void PowerOff() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.PowerOff" />
      <MemberSignature Language="VB.NET" Value="Public Sub PowerOff ()" />
      <MemberSignature Language="F#" Value="abstract member PowerOff : unit -&gt; unit" Usage="iVirtualMachineScaleSet.PowerOff " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Schaltet (beendet) der virtuellen Computer in der Skala festlegen.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="PowerOffAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task PowerOffAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task PowerOffAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.PowerOffAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member PowerOffAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSet.PowerOffAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Schaltet (beendet) legen Sie die virtuellen Computer in der Skala asynchron.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
    <Member MemberName="PrimaryPublicIPAddressIds">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; PrimaryPublicIPAddressIds { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; PrimaryPublicIPAddressIds" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.PrimaryPublicIPAddressIds" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property PrimaryPublicIPAddressIds As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.PrimaryPublicIPAddressIds : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.PrimaryPublicIPAddressIds" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            IOException Ruft die e/a-Ausnahme ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
        <return>
            Ruft die Liste der IDs von die öffentlichen IP-Adressen, die die primären Internetzugriff-Load-Balancer vom scaleset zugeordnet.
            </return>
      </Docs>
    </Member>
    <Member MemberName="Reimage">
      <MemberSignature Language="C#" Value="public void Reimage ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Reimage() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Reimage" />
      <MemberSignature Language="VB.NET" Value="Public Sub Reimage ()" />
      <MemberSignature Language="F#" Value="abstract member Reimage : unit -&gt; unit" Usage="iVirtualMachineScaleSet.Reimage " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Ein Abbild (aktualisiert die Version des installierten Betriebssystems) die virtuellen Computer in der Menge der Skala.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="ReimageAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task ReimageAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task ReimageAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.ReimageAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member ReimageAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSet.ReimageAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Ein Abbild (aktualisiert die Version des installierten Betriebssystems) legen Sie die virtuellen Computer in der Skala asynchron.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
    <Member MemberName="Restart">
      <MemberSignature Language="C#" Value="public void Restart ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Restart() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Restart" />
      <MemberSignature Language="VB.NET" Value="Public Sub Restart ()" />
      <MemberSignature Language="F#" Value="abstract member Restart : unit -&gt; unit" Usage="iVirtualMachineScaleSet.Restart " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet den virtuellen Computern in der Skalierungsgruppe neu.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="RestartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task RestartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task RestartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.RestartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member RestartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSet.RestartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Startet den virtuellen Computern in das Scale set asynchron neu.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
    <Member MemberName="Sku">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes Sku { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes Sku" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Sku" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property Sku As VirtualMachineScaleSetSkuTypes" />
      <MemberSignature Language="F#" Value="member this.Sku : Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Sku" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachineScaleSetSkuTypes</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die SKU der virtuellen Computer in der Menge der Skala.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="Start">
      <MemberSignature Language="C#" Value="public void Start ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance void Start() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.Start" />
      <MemberSignature Language="VB.NET" Value="Public Sub Start ()" />
      <MemberSignature Language="F#" Value="abstract member Start : unit -&gt; unit" Usage="iVirtualMachineScaleSet.Start " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Void</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Startet den virtuellen Computern in der Menge der Skala an.
            </summary>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="StartAsync">
      <MemberSignature Language="C#" Value="public System.Threading.Tasks.Task StartAsync (System.Threading.CancellationToken cancellationToken = null);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class System.Threading.Tasks.Task StartAsync(valuetype System.Threading.CancellationToken cancellationToken) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.StartAsync(System.Threading.CancellationToken)" />
      <MemberSignature Language="F#" Value="abstract member StartAsync : System.Threading.CancellationToken -&gt; System.Threading.Tasks.Task" Usage="iVirtualMachineScaleSet.StartAsync cancellationToken" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Threading.Tasks.Task</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cancellationToken" Type="System.Threading.CancellationToken" />
      </Parameters>
      <Docs>
        <param name="cancellationToken">To be added.</param>
        <summary>
            Startet den virtuellen Computern in das Scale set asynchron.
            </summary>
        <returns>To be added.</returns>
        <remarks>
            (Beta: Diese Funktionalität ist in der Vorschau und als solche in nicht-abwärtskompatibel Möglichkeiten, die in zukünftigen Versionen, einschließlich Entfernung, unabhängig von der alle Anforderungen an die Kompatibilität, die Versionsnummer der enthaltenden Bibliothek festgelegt sind vorbehalten.).
            </remarks>
        <return>Eine Darstellung der verzögerten Berechnung dieses Aufrufs.</return>
      </Docs>
    </Member>
    <Member MemberName="StorageProfile">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile StorageProfile { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile StorageProfile" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.StorageProfile" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property StorageProfile As VirtualMachineScaleSetStorageProfile" />
      <MemberSignature Language="F#" Value="member this.StorageProfile : Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.StorageProfile" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.VirtualMachineScaleSetStorageProfile</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft das Speicherprofil ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="UpgradeModel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode UpgradeModel { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance valuetype Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode UpgradeModel" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.UpgradeModel" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property UpgradeModel As UpgradeMode" />
      <MemberSignature Language="F#" Value="member this.UpgradeModel : Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.UpgradeModel" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.Models.UpgradeMode</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die Upgrade-Modell ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VhdContainers">
      <MemberSignature Language="C#" Value="public System.Collections.Generic.IReadOnlyList&lt;string&gt; VhdContainers { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class System.Collections.Generic.IReadOnlyList`1&lt;string&gt; VhdContainers" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.VhdContainers" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VhdContainers As IReadOnlyList(Of String)" />
      <MemberSignature Language="F#" Value="member this.VhdContainers : System.Collections.Generic.IReadOnlyList&lt;string&gt;" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.VhdContainers" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>System.Collections.Generic.IReadOnlyList&lt;System.String&gt;</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft die URL-Speichercontainer, in denen die virtuellen Festplatten der virtuellen Computer in der Menge Dezimalstellen gespeichert.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
    <Member MemberName="VirtualMachines">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMs VirtualMachines { get; }" />
      <MemberSignature Language="ILAsm" Value=".property instance class Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMs VirtualMachines" />
      <MemberSignature Language="DocId" Value="P:Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.VirtualMachines" />
      <MemberSignature Language="VB.NET" Value="Public ReadOnly Property VirtualMachines As IVirtualMachineScaleSetVMs" />
      <MemberSignature Language="F#" Value="member this.VirtualMachines : Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMs" Usage="Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSet.VirtualMachines" />
      <MemberType>Property</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.IVirtualMachineScaleSetVMs</ReturnType>
      </ReturnValue>
      <Docs>
        <summary>
            Ruft Einstiegspunkt zum Verwalten von Instanzen der virtuellen Maschine in der Menge der Skala ab.
            </summary>
        <value>To be added.</value>
        <remarks>To be added.</remarks>
      </Docs>
    </Member>
  </Members>
</Type>