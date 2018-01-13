<Type Name="IWithPrimaryNetwork" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryNetwork" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryNetwork" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryNetwork" />
  <TypeSignature Language="F#" Value="type IWithPrimaryNetwork = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der Definition der Netzwerk-Schnittstelle zum Angeben des virtuellen Netzwerks für die primäre IP-Konfiguration ermöglicht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet WithExistingPrimaryNetwork (Microsoft.Azure.Management.Network.Fluent.INetwork network);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet WithExistingPrimaryNetwork(class Microsoft.Azure.Management.Network.Fluent.INetwork network) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithExistingPrimaryNetwork(Microsoft.Azure.Management.Network.Fluent.INetwork)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingPrimaryNetwork (network As INetwork) As IWithPrimaryNetworkSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithExistingPrimaryNetwork : Microsoft.Azure.Management.Network.Fluent.INetwork -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet" Usage="iWithPrimaryNetwork.WithExistingPrimaryNetwork network" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetworkSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
      </Parameters>
      <Docs>
        <param name="network">Ein vorhandenes virtuelles Netzwerk.</param>
        <summary>
            Ordnen Sie die Netzwerkschnittstelle primäre IP-Konfiguration mit ein vorhandenes virtuelles Netzwerk.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithNewPrimaryNetwork(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetwork})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (creatable As ICreatable(Of INetwork)) As IWithPrimaryPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" Usage="iWithPrimaryNetwork.WithNewPrimaryNetwork creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Eine erstellbare Definition für ein neues virtuelles Netzwerk.</param>
        <summary>
            Erstellen Sie ein neues virtuelles Netzwerk, die Netzwerkschnittstelle primäre IP-Konfiguration, basierend auf der bereitgestellten Definition zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork (string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork(string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithNewPrimaryNetwork(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (addressSpace As String) As IWithPrimaryPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" Usage="iWithPrimaryNetwork.WithNewPrimaryNetwork addressSpace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="addressSpace">Der Adressraum für das virtuelle Netzwerk.</param>
        <summary>
            Erstellt ein neues virtuelles Netzwerk, die Netzwerkschnittstelle primäre IP-Konfiguration zugeordnet werden soll.
            In der gleichen Ressourcengruppe und Ihrer Region ab Netzwerkschnittstelle im virtuelle Netzwerk erstellt werden, er wird mit der angegebenen Adressraum und eine standardsubnetz abdecken der Netzwerk-IP-Adressbereich vollständig erstellt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewPrimaryNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork (string name, string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP WithNewPrimaryNetwork(string name, string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryNetwork.WithNewPrimaryNetwork(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPrimaryNetwork (name As String, addressSpace As String) As IWithPrimaryPrivateIP" />
      <MemberSignature Language="F#" Value="abstract member WithNewPrimaryNetwork : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP" Usage="iWithPrimaryNetwork.WithNewPrimaryNetwork (name, addressSpace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Definition.IWithPrimaryPrivateIP</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des neuen virtuellen Netzwerks.</param>
        <param name="addressSpace">Der Adressraum für das virtuelle Netzwerk Rhe.</param>
        <summary>
            Erstellt ein neues virtuelles Netzwerk, die Netzwerkschnittstelle primäre IP-Konfiguration zugeordnet werden soll.
            In der gleichen Ressourcengruppe und Ihrer Region ab Netzwerkschnittstelle im virtuelle Netzwerk erstellt werden, er wird mit der angegebenen Adressraum und eine standardsubnetz abdecken der Netzwerk-IP-Adressbereich vollständig erstellt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>