<Type Name="IWithNetwork&lt;ParentT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork&lt;ParentT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNetwork&lt;ParentT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNetwork`1&lt;ParentT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNetwork(Of ParentT)" />
  <TypeSignature Language="F#" Value="type IWithNetwork&lt;'ParentT&gt; = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ParentT" />
  </TypeParameters>
  <Interfaces />
  <Docs>
    <typeparam name="ParentT">Der Rückgabetyp des endgültigen Attachable.attach().</typeparam>
    <summary>
            Die Stufe der Netzwerk-IP-Konfiguration Schnittstellendefinition an das virtuelle Netzwerk ermöglicht.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithExistingNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithSubnet&lt;ParentT&gt; WithExistingNetwork (Microsoft.Azure.Management.Network.Fluent.INetwork network);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithSubnet`1&lt;!ParentT&gt; WithExistingNetwork(class Microsoft.Azure.Management.Network.Fluent.INetwork network) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork`1.WithExistingNetwork(Microsoft.Azure.Management.Network.Fluent.INetwork)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithExistingNetwork (network As INetwork) As IWithSubnet(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithExistingNetwork : Microsoft.Azure.Management.Network.Fluent.INetwork -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithSubnet&lt;'ParentT&gt;" Usage="iWithNetwork.WithExistingNetwork network" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithSubnet&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="network" Type="Microsoft.Azure.Management.Network.Fluent.INetwork" />
      </Parameters>
      <Docs>
        <param name="network">Ein vorhandenes virtuelles Netzwerk.</param>
        <summary>
            Ordnen Sie ein vorhandenes virtuelles Netzwerk-IP-Konfiguration der Netzwerkschnittstelle.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt; WithNewNetwork (Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP`1&lt;!ParentT&gt; WithNewNetwork(class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt; creatable) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork`1.WithNewNetwork(Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable{Microsoft.Azure.Management.Network.Fluent.INetwork})" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetwork (creatable As ICreatable(Of INetwork)) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetwork : Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt; -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithNetwork.WithNewNetwork creatable" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="creatable" Type="Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
      </Parameters>
      <Docs>
        <param name="creatable">Eine erstellbare Definition für ein neues virtuelles Netzwerk.</param>
        <summary>
            Erstellen Sie ein neues virtuelles Netzwerk, IP-die Konfiguration der Netzwerkschnittstelle, basierend auf der bereitgestellten Definition zugeordnet werden soll.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt; WithNewNetwork (string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP`1&lt;!ParentT&gt; WithNewNetwork(string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork`1.WithNewNetwork(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetwork (addressSpace As String) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetwork : string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithNetwork.WithNewNetwork addressSpace" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="addressSpace">Der Adressraum für das virtuelle Netzwerk.</param>
        <summary>
            Erstellt ein neues virtuelles Netzwerk, IP-Konfiguration der Netzwerkschnittstelle zugeordnet werden soll.
            das virtuelle Netzwerk wird in derselben Ressourcengruppe und Region ab übergeordneten Netzwerkschnittstelle erstellt werden, wird mit der angegebenen Adressraum und eine standardsubnetz abdecken der Netzwerk-IP-Adressbereich vollständig erstellt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithNewNetwork">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt; WithNewNetwork (string name, string addressSpace);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP`1&lt;!ParentT&gt; WithNewNetwork(string name, string addressSpace) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithNetwork`1.WithNewNetwork(System.String,System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewNetwork (name As String, addressSpace As String) As IWithPrivateIP(Of ParentT)" />
      <MemberSignature Language="F#" Value="abstract member WithNewNetwork : string * string -&gt; Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;'ParentT&gt;" Usage="iWithNetwork.WithNewNetwork (name, addressSpace)" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NicIPConfiguration.Definition.IWithPrivateIP&lt;ParentT&gt;</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="name" Type="System.String" />
        <Parameter Name="addressSpace" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="name">Der Name des neuen virtuellen Netzwerks.</param>
        <param name="addressSpace">Der Adressraum für das virtuelle Netzwerk Rhe.</param>
        <summary>
            Erstellt ein neues virtuelles Netzwerk, IP-Konfiguration der Netzwerkschnittstelle zugeordnet werden soll.
            das virtuelle Netzwerk wird in derselben Ressourcengruppe und Region ab übergeordneten Netzwerkschnittstelle erstellt werden, wird mit der angegebenen Adressraum und eine standardsubnetz abdecken der Netzwerk-IP-Adressbereich vollständig erstellt werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>