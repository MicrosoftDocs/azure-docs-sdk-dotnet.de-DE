<Type Name="IWithNetworkSecurityGroup" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup">
  <TypeSignature Language="C#" Value="public interface IWithNetworkSecurityGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetworkSecurityGroup" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetworkSecurityGroup" />
  <TypeSignature Language="F#" Value="type IWithNetworkSecurityGroup = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der netzwerkschnittstellendefinition ermöglicht eine Netzwerksicherheitsgruppe zugeordnet.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingNetworkSecurityGroup (Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup networkSecurityGroup);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithExistingNetworkSecurityGroup(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup networkSecurityGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup.WithExistingNetworkSecurityGroup(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingNetworkSecurityGroup (networkSecurityGroup As INetworkSecurityGroup) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingNetworkSecurityGroup : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithNetworkSecurityGroup.WithExistingNetworkSecurityGroup networkSecurityGroup" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="networkSecurityGroup" Type="Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup" />
      </Parameters>
      <Docs>
        <param name="networkSecurityGroup">Eine vorhandene Netzwerksicherheitsgruppe.</param>
        <summary>
            Ordnet eine vorhandene Netzwerksicherheitsgruppe der Netzwerkschnittstelle.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithNewNetworkSecurityGroup (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate WithNewNetworkSecurityGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithNetworkSecurityGroup.WithNewNetworkSecurityGroup(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetworkSecurityGroup (creatable As ICreatable(Of INetworkSecurityGroup)) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetworkSecurityGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate" Usage="iWithNetworkSecurityGroup.WithNewNetworkSecurityGroup creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Eine erstellbare Definition für eine neue Netzwerksicherheitsgruppe.</param>
        <summary>
            Erstellen Sie eine neue Netzwerksicherheitsgruppe Netzwerkschnittstelle, die auf Grundlage der bereitgestellten Definition zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>