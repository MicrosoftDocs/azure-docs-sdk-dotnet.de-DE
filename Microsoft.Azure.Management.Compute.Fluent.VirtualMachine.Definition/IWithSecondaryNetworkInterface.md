<Type Name="IWithSecondaryNetworkInterface" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface">
  <TypeSignature Language="C#" Value="public interface IWithSecondaryNetworkInterface" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithSecondaryNetworkInterface" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithSecondaryNetworkInterface" />
  <TypeSignature Language="F#" Value="type IWithSecondaryNetworkInterface = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines virtuellen Computer, sodass zusätzliche Netzwerkschnittstellen an.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingSecondaryNetworkInterface (Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithExistingSecondaryNetworkInterface(class Microsoft.Azure.Management.Network.Fluent.INetworkInterface networkInterface) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface.WithExistingSecondaryNetworkInterface(Microsoft.Azure.Management.Network.Fluent.INetworkInterface)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingSecondaryNetworkInterface (networkInterface As INetworkInterface) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingSecondaryNetworkInterface : Microsoft.Azure.Management.Network.Fluent.INetworkInterface -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithSecondaryNetworkInterface.WithExistingSecondaryNetworkInterface networkInterface" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="networkInterface" Type="Microsoft.Azure.Management.Network.Fluent.INetworkInterface" />
      </Parameters>
      <Docs>
        <param name="networkInterface">Eine vorhandene Netzwerkschnittstelle.</param>
        <summary>
            Ordnet eine vorhandene Netzwerkschnittstelle mit dem virtuellen Computer an.
            Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedem dient, die neue sekundäre Netzwerkschnittstelle hinzugefügt mit dem virtuellen Computer.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewSecondaryNetworkInterface">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewSecondaryNetworkInterface (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate WithNewSecondaryNetworkInterface(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithSecondaryNetworkInterface.WithNewSecondaryNetworkInterface(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetworkInterface})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewSecondaryNetworkInterface (creatable As ICreatable(Of INetworkInterface)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewSecondaryNetworkInterface : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate" Usage="iWithSecondaryNetworkInterface.WithNewSecondaryNetworkInterface creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkInterface&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Eine erstellbare Definition für eine neue Netzwerkschnittstelle.</param>
        <summary>
            Erstellt eine neue Netzwerkschnittstelle dem virtuellen Computer auf Grundlage der bereitgestellten Definition zugeordnet werden soll.
            Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedes Mal, die es verwendet wird, eine neue sekundäre Netzwerkschnittstelle hinzugefügt der virtuellen Maschine.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>