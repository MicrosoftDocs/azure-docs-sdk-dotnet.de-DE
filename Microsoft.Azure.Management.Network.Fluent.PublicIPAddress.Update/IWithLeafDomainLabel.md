<Type Name="IWithLeafDomainLabel" FullName="Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithLeafDomainLabel">
  <TypeSignature Language="C#" Value="public interface IWithLeafDomainLabel" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithLeafDomainLabel" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithLeafDomainLabel" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithLeafDomainLabel" />
  <TypeSignature Language="F#" Value="type IWithLeafDomainLabel = interface" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces />
  <Docs>
    <summary>
            Eine öffentliche IP-Adresse Update so ändern Sie die Blattebene des Domänennamens, zulassen, sofern vorhanden.
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithLeafDomainLabel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithLeafDomainLabel (string dnsName);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithLeafDomainLabel(string dnsName) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithLeafDomainLabel.WithLeafDomainLabel(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithLeafDomainLabel (dnsName As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithLeafDomainLabel : string -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithLeafDomainLabel.WithLeafDomainLabel dnsName" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="dnsName" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="dnsName">die Blattebene Domäne Bezeichnung verwendet. Dies muss der erforderlichen Benennungskonvention für Endknoten Domänennamen folgen.</param>
        <summary>
            Gibt die Bezeichnung des Endknoten-Domäne diese öffentliche IP-Adresse zugeordnet werden soll.
            Der vollqualifizierte Domänenname (FQDN) wird automatisch erstellt werden, durch den Rest der Domäne auf diese Bezeichnung anhängen.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Ressource-Updates.</return>
      </Docs>
    </Member>
    <Member MemberName="WithoutLeafDomainLabel">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithoutLeafDomainLabel ();" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate WithoutLeafDomainLabel() cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IWithLeafDomainLabel.WithoutLeafDomainLabel" />
      <MemberSignature Language="VB.NET" Value="Public Function WithoutLeafDomainLabel () As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithoutLeafDomainLabel : unit -&gt; Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate" Usage="iWithLeafDomainLabel.WithoutLeafDomainLabel " />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.PublicIPAddress.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters />
      <Docs>
        <summary>
            Stellt sicher, dass keine Endknoten des Domänennamens verwendet wird.
            Dies bedeutet, dass diese öffentliche IP-Adresse nicht mit einem Domänennamen zugeordnet wird.
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return>Die nächste Phase des Ressource-Updates.</return>
      </Docs>
    </Member>
  </Members>
</Type>