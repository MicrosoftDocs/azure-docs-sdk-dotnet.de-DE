<Type Name="IWithAddressSpace" FullName="Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithAddressSpace">
  <TypeSignature Language="C#" Value="public interface IWithAddressSpace : Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithAddressSpaceBeta, Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="ILAsm" Value=".class public interface auto ansi abstract IWithAddressSpace implements class Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithAddressSpaceBeta, class Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta" />
  <TypeSignature Language="DocId" Value="T:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithAddressSpace" />
  <TypeSignature Language="VB.NET" Value="Public Interface IWithAddressSpace&#xA;Implements IBeta, IWithAddressSpaceBeta" />
  <TypeSignature Language="F#" Value="type IWithAddressSpace = interface&#xA;    interface IWithAddressSpaceBeta&#xA;    interface IBeta" />
  <AssemblyInfo>
    <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
    <AssemblyVersion>1.0.0.60</AssemblyVersion>
  </AssemblyInfo>
  <Interfaces>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithAddressSpaceBeta</InterfaceName>
    </Interface>
    <Interface>
      <InterfaceName>Microsoft.Azure.Management.ResourceManager.Fluent.Core.IBeta</InterfaceName>
    </Interface>
  </Interfaces>
  <Docs>
    <summary>
            <span data-ttu-id="4b3e4-101">Die Stufe der virtuelles Netzwerk aktualisieren ermöglicht den Adressraum angeben.</span><span class="sxs-lookup"><span data-stu-id="4b3e4-101">The stage of the virtual network update allowing to specify the address space.</span></span>
            </summary>
    <remarks>To be added.</remarks>
  </Docs>
  <Members>
    <Member MemberName="WithAddressSpace">
      <MemberSignature Language="C#" Value="public Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithAddressSpace (string cidr);" />
      <MemberSignature Language="ILAsm" Value=".method public hidebysig newslot virtual instance class Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate WithAddressSpace(string cidr) cil managed" />
      <MemberSignature Language="DocId" Value="M:Microsoft.Azure.Management.Network.Fluent.Network.Update.IWithAddressSpace.WithAddressSpace(System.String)" />
      <MemberSignature Language="VB.NET" Value="Public Function WithAddressSpace (cidr As String) As IUpdate" />
      <MemberSignature Language="F#" Value="abstract member WithAddressSpace : string -&gt; Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate" Usage="iWithAddressSpace.WithAddressSpace cidr" />
      <MemberType>Method</MemberType>
      <AssemblyInfo>
        <AssemblyName>Microsoft.Azure.Management.Network.Fluent</AssemblyName>
        <AssemblyVersion>1.0.0.60</AssemblyVersion>
      </AssemblyInfo>
      <ReturnValue>
        <ReturnType>Microsoft.Azure.Management.Network.Fluent.Network.Update.IUpdate</ReturnType>
      </ReturnValue>
      <Parameters>
        <Parameter Name="cidr" Type="System.String" />
      </Parameters>
      <Docs>
        <param name="cidr"><span data-ttu-id="4b3e4-102">Die CIDR-Darstellung des Adressraums werden soll.</span><span class="sxs-lookup"><span data-stu-id="4b3e4-102">The CIDR representation of the address space.</span></span></param>
        <summary>
            <span data-ttu-id="4b3e4-103">Explizit Fügt einen Adressraum im virtuellen Netzwerk.</span><span class="sxs-lookup"><span data-stu-id="4b3e4-103">Explicitly adds an address space to the virtual network.</span></span>
            <span data-ttu-id="4b3e4-104">Beachten Sie, diese Methode Effekt ist kumulativ, d. h. jedes Mal, die es verwendet wird, ein neuen Adressraum ist zum Netzwerk hinzugefügt.</span><span class="sxs-lookup"><span data-stu-id="4b3e4-104">Note this method's effect is additive, i.e. each time it is used, a new address space is added to the network.</span></span>
            <span data-ttu-id="4b3e4-105">Diese Methode überprüft nicht auf Konflikte wenig oder überschneidet sich mit anderen Adressräume.</span><span class="sxs-lookup"><span data-stu-id="4b3e4-105">This method does not check for conflicts or overlaps with other address spaces.</span></span> <span data-ttu-id="4b3e4-106">Ein Konflikt vorliegt, kann eine Cloud-Ausnahme ausgelöst werden, nachdem das Update angewendet wird.</span><span class="sxs-lookup"><span data-stu-id="4b3e4-106">If there is a conflict, a cloud exception may be thrown after the update is applied.</span></span>
            </summary>
        <returns>To be added.</returns>
        <remarks>To be added.</remarks>
        <return><span data-ttu-id="4b3e4-107">Die nächste Phase des virtuellen Netzwerks Updates.</span><span class="sxs-lookup"><span data-stu-id="4b3e4-107">The next stage of the virtual network update.</span></span></return>
      </Docs>
    </Member>
  </Members>
</Type>