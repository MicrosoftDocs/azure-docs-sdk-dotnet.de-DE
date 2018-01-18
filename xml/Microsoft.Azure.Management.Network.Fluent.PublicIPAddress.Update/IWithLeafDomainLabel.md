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
            <span data-ttu-id="64521-101">Eine öffentliche IP-Adresse Update so ändern Sie die Blattebene des Domänennamens, zulassen, sofern vorhanden.</span><span class="sxs-lookup"><span data-stu-id="64521-101">A public IP address update allowing to change the leaf domain label, if any.</span></span>
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
        <param name="dnsName"><span data-ttu-id="64521-102">die Blattebene Domäne Bezeichnung verwendet.</span><span class="sxs-lookup"><span data-stu-id="64521-102">The leaf domain label to use.</span></span> <span data-ttu-id="64521-103">Dies muss der erforderlichen Benennungskonvention für Endknoten Domänennamen folgen.</span><span class="sxs-lookup"><span data-stu-id="64521-103">This must follow the required naming convention for leaf domain names.</span></span></param>
        <summary>
            <span data-ttu-id="64521-104">Gibt die Bezeichnung des Endknoten-Domäne diese öffentliche IP-Adresse zugeordnet werden soll.</span><span class="sxs-lookup"><span data-stu-id="64521-104">Specifies the leaf domain label to associate with this public IP address.</span></span>
            <span data-ttu-id="64521-105">Der vollqualifizierte Domänenname (FQDN) wird automatisch erstellt werden, durch den Rest der Domäne auf diese Bezeichnung anhängen.</span><span class="sxs-lookup"><span data-stu-id="64521-105">The fully qualified domain name (FQDN) will be constructed automatically by appending the rest of the domain to this label.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="64521-106">Die nächste Phase des Ressource-Updates.</span><span class="sxs-lookup"><span data-stu-id="64521-106">The next stage of the resource update.</span></span></return>
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
            <span data-ttu-id="64521-107">Stellt sicher, dass keine Endknoten des Domänennamens verwendet wird.</span><span class="sxs-lookup"><span data-stu-id="64521-107">Ensures that no leaf domain label will be used.</span></span>
            <span data-ttu-id="64521-108">Dies bedeutet, dass diese öffentliche IP-Adresse nicht mit einem Domänennamen zugeordnet wird.</span><span class="sxs-lookup"><span data-stu-id="64521-108">This means that this public IP address will not be associated with a domain name.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="64521-109">Die nächste Phase des Ressource-Updates.</span><span class="sxs-lookup"><span data-stu-id="64521-109">The next stage of the resource update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>