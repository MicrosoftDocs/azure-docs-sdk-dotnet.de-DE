<Type Name="IWithNetworkSecurityGroup" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithNetworkSecurityGroup">
  <TypeSignature Language="C#" Value="public interface IWithNetworkSecurityGroup" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetworkSecurityGroup" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithNetworkSecurityGroup" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetworkSecurityGroup" />
  <TypeSignature Language="F#" Value="type IWithNetworkSecurityGroup = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase der Netzwerk Schnittstelle Update ermöglichen einer Netzwerksicherheitsgruppe zugeordnet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithExistingNetworkSecurityGroup (Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup networkSecurityGroup);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithExistingNetworkSecurityGroup(class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup networkSecurityGroup) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithNetworkSecurityGroup.WithExistingNetworkSecurityGroup(Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingNetworkSecurityGroup (networkSecurityGroup As INetworkSecurityGroup) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithExistingNetworkSecurityGroup : Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithNetworkSecurityGroup.WithExistingNetworkSecurityGroup networkSecurityGroup" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
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
        <return>Die nächste Phase des Netzwerk-Schnittstelle Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewNetworkSecurityGroup (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithNewNetworkSecurityGroup(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithNetworkSecurityGroup.WithNewNetworkSecurityGroup(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetworkSecurityGroup (creatable As ICreatable(Of INetworkSecurityGroup)) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetworkSecurityGroup : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetworkSecurityGroup&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithNetworkSecurityGroup.WithNewNetworkSecurityGroup creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
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
        <return>Die nächste Phase des Netzwerk-Schnittstelle Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutNetworkSecurityGroup">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutNetworkSecurityGroup ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithoutNetworkSecurityGroup() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithNetworkSecurityGroup.WithoutNetworkSecurityGroup" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutNetworkSecurityGroup () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutNetworkSecurityGroup : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithNetworkSecurityGroup.WithoutNetworkSecurityGroup " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Gibt an, dass der Netzwerkschnittstelle zugeordnete Netzwerksicherheitsgruppe entfernen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Netzwerk-Schnittstelle Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>