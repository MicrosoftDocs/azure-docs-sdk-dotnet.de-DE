<Type Name="IWithNewPublicIPAddress&lt;ReturnT&gt;" FullName="Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddress&lt;ReturnT&gt;">
  <TypeSignature Language="C#" Value="public interface IWithNewPublicIPAddress&lt;ReturnT&gt; : Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddressNoDnsLabel&lt;ReturnT&gt;" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithNewPublicIPAddress`1&lt;ReturnT&gt; implements class Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddressNoDnsLabel`1&lt;!ReturnT&gt;" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddress`1" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithNewPublicIPAddress(Of ReturnT)&#xA;Implements IWithNewPublicIPAddressNoDnsLabel(Of ReturnT)" />
  <TypeSignature Language="F#" Value="type IWithNewPublicIPAddress&lt;'ReturnT&gt; = interface&#xA;    interface IWithNewPublicIPAddressNoDnsLabel&lt;'ReturnT&gt;" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <TypeParameters>
    <TypeParameter Name="ReturnT" />
  </TypeParameters>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddressNoDnsLabel&lt;ReturnT&gt;</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <typeparam name="ReturnT">die nächste Phase der Definition.</typeparam>
    <summary>
            Die Phase des Updates, sodass eine neue öffentliche IP-Adresse die Ressource zugeordnet werden soll.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithNewPublicIPAddress">
      <MemberSignature Language="C#" Value="public ReturnT WithNewPublicIPAddress (string leafDnsLabel);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance !ReturnT WithNewPublicIPAddress(string leafDnsLabel) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.HasPublicIPAddress.Update.IWithNewPublicIPAddress`1.WithNewPublicIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithNewPublicIPAddress (leafDnsLabel As String) As ReturnT" />
      <MemberSignature Language="F#" Value="abstract member WithNewPublicIPAddress : string -&gt; 'ReturnT" Usage="iWithNewPublicIPAddress.WithNewPublicIPAddress leafDnsLabel" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>ReturnT</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="leafDnsLabel" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="leafDnsLabel">Die Blattebene des Domänennamens.</param>
        <summary>
            Erstellt eine neue öffentliche IP-Adresse in derselben Region und demselben Gruppe wie die Ressource, mit der angegebenen DNS-Bezeichnung, und ordnet die Ressource.
            Der interne Name für die öffentliche IP-Adresse wird von der DNS-Bezeichnung abgeleitet werden.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase der Definition.</return>
      </Docs>
    </Member>
  </Members>
</Type>