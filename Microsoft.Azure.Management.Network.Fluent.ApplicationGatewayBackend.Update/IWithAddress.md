<Type Name="IWithAddress" FullName="Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress">
  <TypeSignature Language="C#" Value="public interface IWithAddress" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddress" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddress" />
  <TypeSignature Language="F#" Value="type IWithAddress = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Die Phase eines Application Gateway Back-End-Updates zulassen an das Back-End eine Adresse hinzuzufügen.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithFqdn (fqdn As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn">Einen vollständig qualifizierten Domänennamen (FQDN).</param>
        <summary>
            Fügt der angegebenen vorhandenen vollständig qualifizierten Domänennamen (FQDN) an den Back-End.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithIPAddress (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">Eine IP-Adresse.</param>
        <summary>
            Fügt die angegebene vorhandene IP-Adresse an den Back-End.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutAddress (Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress address);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutAddress(class Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress address) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithoutAddress(Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutAddress (address As ApplicationGatewayBackendAddress) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutAddress : Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithoutAddress address" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="address" Type="Microsoft.Azure.Management.Network.Fluent.Models.ApplicationGatewayBackendAddress" />
      </Parameters>
      <Docs>
        <param name="address">Eine vorhandene Adresse, die mit dem Back-End derzeit zugewiesen ist.</param>
        <summary>
            Stellen Sie sicher, dass die angegebene Adresse nicht mit diesem Back-End-verknüpft ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutFqdn">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutFqdn (string fqdn);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutFqdn(string fqdn) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithoutFqdn(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutFqdn (fqdn As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutFqdn : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithoutFqdn fqdn" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="fqdn" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="fqdn">Einen vollständig qualifizierten Domänennamen ein.</param>
        <summary>
            Stellt sicher, dass der angegebene vollqualifizierte Domänenname (FQDN) nicht mit diesem Back-End-verknüpft ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutIPAddress">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutIPAddress (string ipAddress);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate WithoutIPAddress(string ipAddress) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IWithAddress.WithoutIPAddress(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutIPAddress (ipAddress As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutIPAddress : string -&gt; Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate" Usage="iWithAddress.WithoutIPAddress ipAddress" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.ApplicationGatewayBackend.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="ipAddress" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="ipAddress">Eine IP-Adresse.</param>
        <summary>
            Stellt sicher, dass die angegebene IP-Adresse nicht mit diesem Back-End-verknüpft ist.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>die nächste Phase des Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>