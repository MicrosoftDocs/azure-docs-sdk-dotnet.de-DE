<Type Name="IWithPrimaryPrivateIP" FullName="Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPrivateIP">
  <TypeSignature Language="C#" Value="public interface IWithPrimaryPrivateIP" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithPrimaryPrivateIP" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPrivateIP" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithPrimaryPrivateIP" />
  <TypeSignature Language="F#" Value="type IWithPrimaryPrivateIP = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Stufe der das Netzwerk Schnittstelle Update ermöglicht privaten IP-Adresse im Subnetz eines virtuellen Netzwerks anzugeben.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithPrimaryPrivateIPAddressDynamic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithPrimaryPrivateIPAddressDynamic ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithPrimaryPrivateIPAddressDynamic() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressDynamic" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryPrivateIPAddressDynamic () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryPrivateIPAddressDynamic : unit -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressDynamic " />
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
            Ermöglicht die dynamische private IP-Adresszuordnung innerhalb der angegebenen vorhandenen virtuellen Netzwerk-Subnetz für die Netzwerkschnittstelle primäre IP-Konfiguration.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Network-Interface-Update.</return>
      </Docs>
    </Member>
    <Member MemberName="WithPrimaryPrivateIPAddressStatic">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithPrimaryPrivateIPAddressStatic (string staticPrivateIPAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate WithPrimaryPrivateIPAddressStatic(string staticPrivateIPAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressStatic(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithPrimaryPrivateIPAddressStatic (staticPrivateIPAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithPrimaryPrivateIPAddressStatic : string -&gt; Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate" Usage="iWithPrimaryPrivateIP.WithPrimaryPrivateIPAddressStatic staticPrivateIPAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.NetworkInterface.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="staticPrivateIPAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="staticPrivateIPAddress">
            Die statische IP-Adresse im angegebenen Subnetz zugewiesen an die primäre IP-Konfiguration.
            </param>
        <summary>
            Weist die angegebene statische private IP-Adresse innerhalb der angegebenen vorhandenen Subnetz des virtuellen Netzwerks auf die Netzwerkschnittstelle primäre IP-Konfiguration.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase der Network-Interface-Update.</return>
      </Docs>
    </Member>
  </Members>
</Type>