<Type Name="IWithCreate" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate">
  <TypeSignature Language="C#" Value="public interface IWithCreate : Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate&gt;, Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithCreate implements class Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags`1&lt;class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable`1&lt;class Microsoft.Azure.Management.Network.Fluent.INetwork&gt;, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.IIndexable" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithCreate&#xA;Implements ICreatable(Of INetwork), IDefinitionWithTags(Of IWithCreate)" />
  <TypeSignature Language="F#" Value="type IWithCreate = interface&#xA;    interface ICreatable&lt;INetwork&gt;&#xA;    interface IIndexable&#xA;    interface IDefinitionWithTags&lt;IWithCreate&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.Resource.Definition.IDefinitionWithTags&lt;Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate&gt;</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.ResourceActions.ICreatable&lt;Microsoft.Azure.Management.Network.Fluent.INetwork&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            Die Phase des virtuellen Netzwerks-Definition enthält alle minimale erforderlichen Eingaben für die Ressource erstellt werden (über WithCreate.create()), sondern auch für andere optionalen Einstellungen angegeben werden, mit Ausnahme von Subnetze hinzufügen,.
            Subnetze können nur über die Berechtigung hinzugefügt werden, nachdem der Adressraum explizit angegeben wird (Siehe WithCreate.withAddressSpace(String)). ist.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAddressSpace">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithAddressSpace (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet WithAddressSpace(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate.WithAddressSpace(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAddressSpace (cidr As String) As IWithCreateAndSubnet" />
      <MemberSignature Language="F#" Value="abstract member WithAddressSpace : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet" Usage="iWithCreate.WithAddressSpace cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreateAndSubnet</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr">Die CIDR-Darstellung des Adressraums werden soll.</param>
        <summary>
            Explizit Fügt einen Adressraum im virtuellen Netzwerk.
            Wenn keine Adressräume explizit angegeben werden, wird ein Standard-Adressraum mit der CIDR "10.0.0.0/16" im virtuellen Netzwerk zugewiesen werden.
            Beachten Sie, dass diese Methode Auswirkungen kumulativ, d. h. jedes Mal, die es verwendet wird, ein neuen Adressraum ist zum Netzwerk hinzugefügt.
            Diese Methode überprüft nicht auf Konflikte wenig oder überschneidet sich mit anderen Adressräume. Ein Konflikt vorliegt, kann eine Cloud-Ausnahme zum Zeitpunkt ausgelöst werden, wenn das Netzwerk erstellt wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
    <Member MemberName="WithDnsServer">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate WithDnsServer (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate WithDnsServer(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate.WithDnsServer(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithDnsServer (ipAddress As String) As IWithCreate" />
      <MemberSignature Language="F#" Value="abstract member WithDnsServer : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate" Usage="iWithCreate.WithDnsServer ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Definition.IWithCreate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">Die IP-Adresse des DNS-Servers.</param>
        <summary>
            Gibt die IP-Adresse eines vorhandenen DNS-Servers im virtuellen Netzwerk zugeordnet werden soll.
            Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedes Mal, die es verwendet wird, ein neuen DNS-Server ist zum Netzwerk hinzugefügt.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>