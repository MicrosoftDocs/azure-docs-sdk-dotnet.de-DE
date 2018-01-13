<Type Name="IWithPublicIPAddress" FullName="Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress">
  <TypeSignature Language="C#" Value="public interface IWithPublicIPAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPublicIPAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPublicIPAddress" />
  <TypeSignature Language="F#" Value="type IWithPublicIPAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Definition eines virtuellen Computers ermöglicht, seine primäre Netzwerkschnittstellen eine öffentliche IP-Adresse zugeordnet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithExistingPrimaryPublicIPAddress (Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithExistingPrimaryPublicIPAddress(class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress publicIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress.WithExistingPrimaryPublicIPAddress(Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryPublicIPAddress (publicIPAddress As IPublicIPAddress) As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryPublicIPAddress : Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" Usage="iWithPublicIPAddress.WithExistingPrimaryPublicIPAddress publicIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="publicIPAddress" Type="Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress" />
      </Parameters>
      <Docs>
        <param name="publicIPAddress">Eine vorhandene öffentliche IP-Adresse.</param>
        <summary>
            Ordnet eine vorhandene öffentliche IP-Adresse des virtuellen Computers primäre Netzwerkschnittstellen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithNewPrimaryPublicIPAddress (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithNewPrimaryPublicIPAddress(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress.WithNewPrimaryPublicIPAddress(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (creatable As ICreatable(Of IPublicIPAddress)) As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt; -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" Usage="iWithPublicIPAddress.WithNewPrimaryPublicIPAddress creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.IPublicIPAddress&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Eine erstellbare Definition für eine neue öffentliche IP-Adresse.</param>
        <summary>
            Erstellt eine neue öffentliche IP-Adresse des virtuellen Computers primären Netzwerkschnittstelle zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithNewPrimaryPublicIPAddress (string leafDnsLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithNewPrimaryPublicIPAddress(string leafDnsLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress.WithNewPrimaryPublicIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryPublicIPAddress (leafDnsLabel As String) As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryPublicIPAddress : string -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" Usage="iWithPublicIPAddress.WithNewPrimaryPublicIPAddress leafDnsLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leafDnsLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leafDnsLabel">Eine Blattebene des Domänennamens.</param>
        <summary>
            Erstellt eine neue öffentliche IP-Adresse in der gleichen Region und die Ressourcengruppe, wie die Ressource, mit der angegebenen DNS-Bezeichnung, und ordnet sie primäre Netzwerkschnittstellen des virtuellen Computers.
            Der interne Name für die öffentliche IP-Adresse wird von der DNS-Bezeichnung abgeleitet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutPrimaryPublicIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithoutPrimaryPublicIPAddress ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS WithoutPrimaryPublicIPAddress() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithPublicIPAddress.WithoutPrimaryPublicIPAddress" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutPrimaryPublicIPAddress () As IWithOS" />
      <MemberSignature Language="F#" Value="abstract member WithoutPrimaryPublicIPAddress : unit -&gt; Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS" Usage="iWithPublicIPAddress.WithoutPrimaryPublicIPAddress " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Compute.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Compute.Fluent.VirtualMachine.Definition.IWithOS</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass der virtuelle Computer eine öffentliche IP-Adresse nicht haben soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>